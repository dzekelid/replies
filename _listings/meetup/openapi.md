swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/events/:event_id/comments/:comment_id/likes:
    get:
      summary: Event Comment and Reply Likes
      description: Returns lists of likes for an event comment or reply
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcommentscomment-idlikes-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments