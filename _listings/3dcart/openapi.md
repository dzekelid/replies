swagger: "2.0"
x-collection-name: 3dcart
x-complete: 1
info:
  title: _3dCartWebAPI
  version: 1.0.0
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CRM/savedreply/{id}:
    get:
      summary: Get a specific CRM Saved Reply
      description: Get a specific crm saved reply.
      operationId: CRM_GetCRMSavedReply
      x-api-path-slug: 3dcartwebapiv1crmsavedreplyid-get
      parameters:
      - in: path
        name: id
        description: CRM Saved Reply ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Specific
      - CRM
      - Saved
      - Reply
    put:
      summary: This method is used to update a single CRM SavedReply record in the
        database. The {id} parameter specifies which CRM SavedReply record to update.
      description: This method is used to update a single crm savedreply record in
        the database. the {id} parameter specifies which crm savedreply record to
        update..
      operationId: CRM_UpdateSavedReply
      x-api-path-slug: 3dcartwebapiv1crmsavedreplyid-put
      parameters:
      - in: path
        name: id
        description: SavedReply ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: savedreply
        description: A Json or XML object containing the new SavedReply
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - SavedReply
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - SavedReply
      - Record
      - To
      - Update
    delete:
      summary: Delete a CRM SavedReply in the system
      description: Delete a crm savedreply in the system.
      operationId: CRM_DeleteCRMSavedReply
      x-api-path-slug: 3dcartwebapiv1crmsavedreplyid-delete
      parameters:
      - in: path
        name: id
        description: SavedReplyID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - CRM
      - SavedReply
      - In
      - System
  /3dCartWebAPI/v1/CRM/savedreply:
    post:
      summary: Adds a new CRM SaveReply to the system
      description: Adds a new crm savereply to the system.
      operationId: CRM_PostSavedReply
      x-api-path-slug: 3dcartwebapiv1crmsavedreply-post
      parameters:
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: savereply
        description: A Json or XML object containing the new CRM SavedReply
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - CRM
      - SaveReply
      - To
      - System