---
name: BigOven
x-slug: bigoven
description: Free recipe app for home cooks. Create a meal plan, grocery list and
  more from your favorite recipes. Organize your recipe collection and take it anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
x-kinRank: "8"
x-alexaRank: "117577"
tags: Replies
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/apis.md
specificationVersion: "0.14"
apis:
- name: Big Oven DELETE a reply to a given review. Authenticated user must be the
    one who originally posted the reply.
  x-api-slug: big-oven
  description: Delete a reply to a given review. authenticated user must be the one
    who originally posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipe/review/replies/{replyId}
  tags: Recipes,Recipe,Review,Replies,ReplyId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/recipereviewrepliesreplyid-delete-openapi.md
- name: Big Oven Update (PUT) a reply to a given review. Authenticated user must be
    the original one that posted the reply.
  x-api-slug: big-oven
  description: Update (put) a reply to a given review. authenticated user must be
    the original one that posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipe/review/replies/{replyId}
  tags: Recipes,Recipe,Review,Replies,ReplyId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/recipereviewrepliesreplyid-put-openapi.md
- name: Big Oven Get a paged list of replies for a given review.
  x-api-slug: big-oven
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipe/review/{reviewId}/replies
  tags: Recipes,Recipe,Review,ReviewId,Replies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven POST a reply to a given review. The date will be set by server. Note
    that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: big-oven
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipe/review/{reviewId}/replies
  tags: Recipes,Recipe,Review,ReviewId,Replies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven
  x-api-slug: big-oven
  description: Free recipe app for home cooks. Create a meal plan, grocery list and
    more from your favorite recipes. Organize your recipe collection and take it anywhere.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Replies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/replies/master/_listings/bigoven/openapi.md
x-common:
- type: x-website
  url: http://www.bigoven.com
- type: x-base
  url: http://api.bigoven.com/
- type: x-blog
  url: http://blog.bigoven.com/
- type: x-blog-rss
  url: http://blog.bigoven.com/index.php/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/bigoven
- type: x-crunchbase
  url: http://www.crunchbase.com/company/bigoven
- type: x-developer
  url: http://api.bigoven.com
- type: x-documentation
  url: http://api2.bigoven.com/
- type: x-email
  url: support@bigoven.com
- type: x-twitter
  url: https://twitter.com/bigoven
- type: x-website
  url: http://bigoven.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---