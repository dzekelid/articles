---
swagger: "2.0"
info:
  title: Healthcare.gov Get API Articles Media Type Extension
  version: 1.0.0
  description: Returns pages content.
host: www.healthcare.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/articles{mediaTypeExtension}:
    get:
      summary: Get API Articles Media Type Extension
      description: Returns pages content
      operationId: returns-pages-content
      parameters:
      - in: path
        name: mediaTypeExtension
        description: Omiting the param causes html to be returned
      responses:
        200:
          description: OK
      tags:
      - insurance
      - articles
      - media
      - type
      - extension
definitions:
  articlesList:
    properties:
      articles:
        description: This is a default description.
        type: get
  blogList:
    properties:
      blog:
        description: This is a default description.
        type: get
  blogPage:
    properties:
      categories:
        description: This is a default description.
        type: get
      content:
        description: This is a default description.
        type: get
      date:
        description: This is a default description.
        type: get
      excerpt:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      lang:
        description: This is a default description.
        type: get
      layout:
        description: This is a default description.
        type: get
      meta-description:
        description: This is a default description.
        type: get
      meta-title:
        description: This is a default description.
        type: get
      path:
        description: This is a default description.
        type: get
  glossaryList:
    properties:
      glossary:
        description: This is a default description.
        type: get
  glossaryPage:
    properties:
      categories:
        description: This is a default description.
        type: get
      content:
        description: This is a default description.
        type: get
      date:
        description: This is a default description.
        type: get
      excerpt:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      lang:
        description: This is a default description.
        type: get
      layout:
        description: This is a default description.
        type: get
      path:
        description: This is a default description.
        type: get
      published:
        description: This is a default description.
        type: get
      sort:
        description: This is a default description.
        type: get
  page:
    properties:
      categories:
        description: This is a default description.
        type: get
      content:
        description: This is a default description.
        type: get
      date:
        description: This is a default description.
        type: get
      excerpt:
        description: This is a default description.
        type: get
      experience:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      lang:
        description: This is a default description.
        type: get
      layout:
        description: This is a default description.
        type: get
      path:
        description: This is a default description.
        type: get
      published:
        description: This is a default description.
        type: get
  questionPage:
    properties:
      categories:
        description: This is a default description.
        type: get
      content:
        description: This is a default description.
        type: get
      date:
        description: This is a default description.
        type: get
      excerpt:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      lang:
        description: This is a default description.
        type: get
      path:
        description: This is a default description.
        type: get
      published:
        description: This is a default description.
        type: get
      sort:
        description: This is a default description.
        type: get
      tags:
        description: This is a default description.
        type: get
  questionsList:
    properties:
      questions:
        description: This is a default description.
        type: get
  statePage:
    properties:
      categories:
        description: This is a default description.
        type: get
      content:
        description: This is a default description.
        type: get
      date:
        description: This is a default description.
        type: get
      excerpt:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      lang:
        description: This is a default description.
        type: get
      path:
        description: This is a default description.
        type: get
      sort:
        description: This is a default description.
        type: get
      stateurl:
        description: This is a default description.
        type: get
      tags:
        description: This is a default description.
        type: get
  statesList:
    properties:
      states:
        description: This is a default description.
        type: get
  topicsList:
    properties:
      topics:
        description: This is a default description.
        type: get
x-collection-name: Healthcare.gov
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