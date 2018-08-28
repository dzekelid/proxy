---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Delete Target SSL Proxy
  description: Deletes the specified TargetSslProxy resource.
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
  /{project}/global/targetHttpsProxies:
    get:
      summary: Get Target HTTPS Proxies
      description: Retrieves the list of TargetHttpsProxy resources available to the
        specified project.
      operationId: compute.targetHttpsProxies.list
      x-api-path-slug: projectglobaltargethttpsproxies-get
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
      summary: Create Target HTTPS Proxy
      description: Creates a TargetHttpsProxy resource in the specified project using
        the data included in the request.
      operationId: compute.targetHttpsProxies.insert
      x-api-path-slug: projectglobaltargethttpsproxies-post
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
  /{project}/global/targetHttpsProxies/{targetHttpsProxy}:
    delete:
      summary: Delete Target HTTPS Proxy
      description: Deletes the specified TargetHttpsProxy resource.
      operationId: compute.targetHttpsProxies.delete
      x-api-path-slug: projectglobaltargethttpsproxiestargethttpsproxy-delete
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: targetHttpsProxy
        description: Name of the TargetHttpsProxy resource to delete
      responses:
        200:
          description: OK
      tags:
      - Proxy
    get:
      summary: Get Target HTTPS Proxy
      description: Returns the specified TargetHttpsProxy resource. Get a list of
        available target HTTPS proxies by making a list() request.
      operationId: compute.targetHttpsProxies.get
      x-api-path-slug: projectglobaltargethttpsproxiestargethttpsproxy-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: targetHttpsProxy
        description: Name of the TargetHttpsProxy resource to return
      responses:
        200:
          description: OK
      tags:
      - Proxy
  /{project}/global/targetSslProxies:
    get:
      summary: Get Target SSL Proxies
      description: Retrieves the list of TargetSslProxy resources available to the
        specified project.
      operationId: compute.targetSslProxies.list
      x-api-path-slug: projectglobaltargetsslproxies-get
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
      summary: Create Target SSL Proxy
      description: Creates a TargetSslProxy resource in the specified project using
        the data included in the request.
      operationId: compute.targetSslProxies.insert
      x-api-path-slug: projectglobaltargetsslproxies-post
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
  /{project}/global/targetSslProxies/{targetSslProxy}:
    delete:
      summary: Delete Target SSL Proxy
      description: Deletes the specified TargetSslProxy resource.
      operationId: compute.targetSslProxies.delete
      x-api-path-slug: projectglobaltargetsslproxiestargetsslproxy-delete
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: targetSslProxy
        description: Name of the TargetSslProxy resource to delete
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