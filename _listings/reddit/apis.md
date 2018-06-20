---
name: Reddit
x-slug: reddit
description: Reddit is a community of millions of users engaging in the creation of
  content and the sharing of conversation across tens of thousands of topics.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
x-kinRank: "9"
x-alexaRank: "6"
tags: Subreddits
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/apis.md
specificationVersion: "0.14"
apis:
- name: Reddit Add Search Subreddits
  x-api-slug: reddit
  description: List subreddits that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////search_subreddits
  tags: Search, Subreddits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/search-subreddits-postnbsp-openapi.md
- name: Reddit Get New Subreddits
  x-api-slug: reddit
  description: Returns new subreddits.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////subreddits/new.json
  tags: Subreddits, New
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditsnew-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditsnew-json-get-openapi.md
- name: Reddit Get Subreddits Mine Where
  x-api-slug: reddit
  description: Get subreddits the user has a relationship with.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////subreddits/mine/where
  tags: Subreddits, Mine, Where
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditsminewhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditsminewhere-getnbsp-openapi.md
- name: Reddit Get Subreddits Search
  x-api-slug: reddit
  description: Search subreddits by title and description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////subreddits/search.json
  tags: Subreddits, Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditssearch-json-get-openapi.md
- name: Reddit Get Subreddits Where
  x-api-slug: reddit
  description: Get all subreddits.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////subreddits/popular.json
  tags: Subreddits, Where
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditspopular-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/subredditspopular-json-get-openapi.md
- name: Reddit
  x-api-slug: reddit
  description: Reddit is a community of millions of users engaging in the creation
    of content and the sharing of conversation across tens of thousands of topics.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Subreddits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/subreddits/master/_listings/reddit/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/reddit/reddit/wiki/OAuth2
- type: x-base
  url: https://www.reddit.com/
- type: x-best-practices
  url: https://github.com/reddit/reddit/wiki/API
- type: x-blog
  url: http://www.redditblog.com/
- type: x-blog-rss
  url: https://www.reddit.com/r/datasets/.rss
- type: x-blog-rss
  url: http://www.redditblog.com/feeds/posts/default?alt=rss
- type: x-code-libraries
  url: https://github.com/reddit/reddit/wiki/API-Wrappers
- type: x-console
  url: https://apigee.com/console/reddit
- type: x-crunchbase
  url: https://crunchbase.com/organization/reddit
- type: x-developer
  url: http://www.reddit.com/dev/api
- type: x-email
  url: legal@reddit.com
- type: x-github
  url: https://github.com/reddit
- type: x-privacy
  url: https://www.reddit.com/help/privacypolicy
- type: x-security
  url: https://www.reddit.com/help/privacypolicy#section_security
- type: x-support
  url: https://www.reddit.com/contact/
- type: x-terms-of-service
  url: http://www.reddit.com/help/useragreement
- type: x-transparency-report
  url: https://www.reddit.com/wiki/transparency
- type: x-twitter
  url: https://twitter.com/reddit
- type: x-website
  url: http://www.reddit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---