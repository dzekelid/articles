---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API Get a representation of an article.
  description: Get JSON which represents the structure of an article.
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /article:
    get:
      summary: List articles.
      description: List the articles, 20 per page.
      operationId: list-the-articles-20-per-page
      x-api-path-slug: article-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the articles
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Articles
  /article/{article_identifier}:
    get:
      summary: Get a representation of an article.
      description: Get JSON which represents the structure of an article.
      operationId: get-json-which-represents-the-structure-of-an-article
      x-api-path-slug: articlearticle-identifier-get
      parameters:
      - in: path
        name: article_identifier
        description: article_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the article
      - in: query
        name: with_regions
        description: Include regions associated with the article
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Article
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