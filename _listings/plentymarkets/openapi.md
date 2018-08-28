swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/feedbacks/feedback/replies/{feedbackId}:
    get:
      summary: List feedback replies
      description: Lists feedback replies. The ID of the feedback must be specified.
      operationId: getRestFeedbacksFeedbackRepliesFeedback
      x-api-path-slug: restfeedbacksfeedbackrepliesfeedbackid-get
      parameters:
      - in: path
        name: feedbackId
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedback
      - Replies