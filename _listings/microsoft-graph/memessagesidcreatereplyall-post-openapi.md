---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Message Create Reply All
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: memailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReply:
    post:
      summary: Message Create Reply
      description: 'message: createReply Create a draft of the Reply message. You
        can then update or send the draft.'
      operationId: Message:CreateReply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: memailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReplyAll:
    post:
      summary: Message Create Reply All
      description: 'message: createReplyAll Create a draft of the Reply All message.
        You can then update or send the draft.'
      operationId: Message:CreateReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: memailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply:
    post:
      summary: Message Reply
      description: 'message: reply Reply to the sender of a message. The message is
        then saved in the Sent Items folder.'
      operationId: Message:Reply
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreply-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/me/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersmemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /me/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: memailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll:
    post:
      summary: Message Reply All
      description: 'message: replyAll Reply to all recipients of a message. The message
        is then saved in the Sent Items folder.'
      operationId: Message:ReplyAll
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidreplyall-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Reply
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