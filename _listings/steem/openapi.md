swagger: "2.0"
x-collection-name: Steem
x-complete: 1
info:
  title: Interactive Steem API
  description: interactive-steem-api-lets-you-interact-with-steem-blockchain-and-make-a-request-get-output-and-start-implementing-new-apps-apis-have-default-parameters-set-to-get-you-started-and-see-how-request-works--api-list-is-compiled-from-steem-githubhttpsgithub-comsteemitsteem-1httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappapi-hpp-and-2httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappdatabase-api-hpp--if-you-want-to-contribute-documenting-detail-of-properties-and-output-contact-goodkarmahttpssteemit-chatdirectgoodkarma--you-can-also-check-full-list-here-steem-jshttpssteemjs-com
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_content_replies:
    get:
      summary: get content replies
      description: get content replies
      operationId: get-content-replies
      x-api-path-slug: get-content-replies-get
      parameters:
      - in: query
        name: author
        description: author
      - in: query
        name: permlink
        description: permlink
      responses:
        200:
          description: OK
      tags:
      - Get
      - Content
      - Replies
  /get_replies_by_last_update:
    get:
      summary: get_replies_by_last_update
      description: get_replies_by_last_update
      operationId: get-replies-by-last-update
      x-api-path-slug: get-replies-by-last-update-get
      parameters:
      - in: query
        name: limit
        description: limit query
      - in: query
        name: startAuthor
        description: account name
      - in: query
        name: startPermlink
        description: permlink of post
      responses:
        200:
          description: OK
      tags:
      - Get
      - Replies
      - By
      - Last
      - Update