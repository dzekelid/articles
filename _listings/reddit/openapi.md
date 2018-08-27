swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{/r/subreddit}/comments/article':
    get&nbsp;:
      summary: Get Subreddit Comments Article
      description: Get the comment tree for a given Link article.
      operationId: get&nbsp;RSubredditCommentsArticle
      x-api-path-slug: rsubredditcommentsarticle-getnbsp
      parameters:
      - in: query
        name: article
        description: ID36 of a link
        type: string
      - in: query
        name: comment
        description: (optional) ID36 of a comment
        type: string
      - in: query
        name: context
        description: an integer between 0 and 8
        type: string
      - in: query
        name: depth
        description: (optional) an integer
        type: string
      - in: query
        name: limit
        description: (optional) an integer
        type: string
      - in: query
        name: showedits
        description: boolean value
        type: string
      - in: query
        name: showmore
        description: boolean value
        type: string
      - in: query
        name: sort
        description: one of (confidence, top, new, controversial, old, random, qa,
          live)
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      - in: query
        name: threaded
        description: boolean value
        type: string
      - in: query
        name: truncate
        description: an integer between 0 and 50
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Comments
      - Article
  /duplicates/article:
    get&nbsp;:
      summary: Get Duplicates Article
      description: Return a list of other submissions of the same URL
      operationId: get&nbsp;DuplicatesArticle
      x-api-path-slug: duplicatesarticle-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: article
        description: The base 36 ID of a Link
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Duplicates
      - Article