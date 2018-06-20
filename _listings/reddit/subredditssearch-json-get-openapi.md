---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Subreddits Search
  description: Search subreddits by title and description.
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search_subreddits:
    post&nbsp;:
      summary: Add Search Subreddits
      description: List subreddits that begin with a query string.
      operationId: post&nbsp;SearchSubreddits
      x-api-path-slug: search-subreddits-postnbsp
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Subreddits
  /subreddits/new.json:
    get:
      summary: Get New Subreddits
      description: Returns new subreddits.
      operationId: getNewSubreddit
      x-api-path-slug: subredditsnew-json-get
      parameters:
      - in: query
        name: query
        description: a string no longer than 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - New
  /subreddits/mine/where:
    get&nbsp;:
      summary: Get Subreddits Mine Where
      description: Get subreddits the user has a relationship with.
      operationId: get&nbsp;SubredditsMineWhere
      x-api-path-slug: subredditsminewhere-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - Mine
      - Where
  /subreddits/search.json:
    get:
      summary: Get Subreddits Search
      description: Search subreddits by title and description.
      operationId: get&nbsp;SubredditsSearch
      x-api-path-slug: subredditssearch-json-get
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: q
        description: a search query
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sort
        description: one of (relevance, activity)
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - Search
x-streamrank:
  polling_total_time_average: "0.8"
  polling_size_download_average: "413017.3"
  streaming_total_time_average: "0.48"
  streaming_size_download_average: "208446.11"
  change_yes: "101"
  change_no: "101"
  time_percentage: "40"
  size_percentage: "50"
  change_percentage: "50"
  last_run: "2018-05-06"
  days_run: "1"
  minute_run: "0"
---