---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Get Target HTTP Proxy
  description: Returns the specified TargetHttpProxy resource. Get a list of available
    target HTTP proxies by making a list() request.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/targetHttpProxies:
    get:
      summary: Get Target HTTP Proxies
      description: Retrieves the list of TargetHttpProxy resources available to the
        specified project.
      operationId: compute.targetHttpProxies.list
      x-api-path-slug: projectglobaltargethttpproxies-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Proxy
    post:
      summary: Create Target HTTP Proxy
      description: Creates a TargetHttpProxy resource in the specified project using
        the data included in the request.
      operationId: compute.targetHttpProxies.insert
      x-api-path-slug: projectglobaltargethttpproxies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Proxy
  /{project}/global/targetHttpProxies/{targetHttpProxy}:
    delete:
      summary: Delete Target HTTP Proxy
      description: Deletes the specified TargetHttpProxy resource.
      operationId: compute.targetHttpProxies.delete
      x-api-path-slug: projectglobaltargethttpproxiestargethttpproxy-delete
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: targetHttpProxy
        description: Name of the TargetHttpProxy resource to delete
      responses:
        200:
          description: OK
      tags:
      - Proxy
    get:
      summary: Get Target HTTP Proxy
      description: Returns the specified TargetHttpProxy resource. Get a list of available
        target HTTP proxies by making a list() request.
      operationId: compute.targetHttpProxies.get
      x-api-path-slug: projectglobaltargethttpproxiestargethttpproxy-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: targetHttpProxy
        description: Name of the TargetHttpProxy resource to return
      responses:
        200:
          description: OK
      tags:
      - Proxy
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