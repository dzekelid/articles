---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get Articles Slug
  description: Display a single article
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /articles:
    get:
      summary: Get Articles
      description: Get articles.
      operationId: getArticles
      x-api-path-slug: articles-get
      parameters:
      - in: query
        name: exclude_featured
        description: Number of featured articles to exclude
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: query
        description: Whats being searched for
      responses:
        200:
          description: OK
      tags:
      - Articles
  /my/follows/articles:
    get:
      summary: Get My Follows Articles
      description: Returns a user's ArticleCategoryFollows
      operationId: getMyFollowsArticles
      x-api-path-slug: myfollowsarticles-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Articles
    post:
      summary: Post My Follows Articles
      description: Set a user's ArticleCategoryFollows
      operationId: postMyFollowsArticles
      x-api-path-slug: myfollowsarticles-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Articles
  /articles/featured:
    get:
      summary: Get Articles Featured
      description: See featured Reverb blog posts
      operationId: getArticlesFeatured
      x-api-path-slug: articlesfeatured-get
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Featured
  /articles/recently_featured:
    get:
      summary: Get Articles Recently Featured
      description: Get articles recently featured.
      operationId: getArticlesRecentlyFeatured
      x-api-path-slug: articlesrecently-featured-get
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Recently
      - Featured
  /articles/{slug}:
    get:
      summary: Get Articles Slug
      description: Display a single article
      operationId: getArticlesSlug
      x-api-path-slug: articlesslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Slug
  /articles/{slug}/related-listings:
    get:
      summary: Get Articles Slug Related Listings
      description: Find listings related to an article
      operationId: getArticlesSlugRelatedListings
      x-api-path-slug: articlesslugrelatedlistings-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Slug
      - Related-listings
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---