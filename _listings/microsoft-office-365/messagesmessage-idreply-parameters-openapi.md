---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Parameters Messages Message Reply
  description: Parameters messages message  reply
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Messages{message_id}/Reply:
    post:
      summary: Add Messages Message Reply
      description: Post messages message  reply
      operationId: postMessagesMessageReply
      x-api-path-slug: messagesmessage-idreply-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Reply
    parameters:
      summary: Parameters Messages Message Reply
      description: Parameters messages message  reply
      operationId: parametersMessagesMessageReply
      x-api-path-slug: messagesmessage-idreply-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Reply
  /Messages{message_id}/ReplyAll:
    post:
      summary: Add Messages Message Replyall
      description: Post messages message  replyall
      operationId: postMessagesMessageReplyall
      x-api-path-slug: messagesmessage-idreplyall-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Replyall
    parameters:
      summary: Parameters Messages Message Replyall
      description: Parameters messages message  replyall
      operationId: parametersMessagesMessageReplyall
      x-api-path-slug: messagesmessage-idreplyall-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Replyall
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