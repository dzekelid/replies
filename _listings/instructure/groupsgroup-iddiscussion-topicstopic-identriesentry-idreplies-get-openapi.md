---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Groups API List entry replies
  description: List entry replies.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/discussion_topics/topic_id/entries/{entry_id}/replies:
    get:
      summary: List entry replies
      description: List entry replies.
      operationId: list-entry-replies
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idreplies-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Replies
    post:
      summary: Post a reply
      description: Post a reply.
      operationId: post-a-reply
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idreplies-post
      parameters:
      - in: query
        name: attachment
        description: a multipart/form-data form-field-style attachment
      - in: query
        name: message
        description: The body of the entry
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Replies
  /groups/{group_id}/discussion_topics/topic_id/entries/{entry_id}/replies:
    get:
      summary: List entry replies
      description: List entry replies.
      operationId: list-entry-replies
      x-api-path-slug: groupsgroup-iddiscussion-topicstopic-identriesentry-idreplies-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Replies
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