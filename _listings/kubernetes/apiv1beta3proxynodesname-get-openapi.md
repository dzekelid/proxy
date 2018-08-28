---
swagger: "2.0"
x-collection-name: Kubernetes
x-complete: 0
info:
  title: Kubernetes Get Proxy Nodes Name
  version: 1.0.0
  description: Proxy get requests to node.
host: /api/v1beta3
basePath: 127.0.0.1:6443
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1beta3/proxy/namespaces/{namespaces}/pods/{name}:
    delete:
      summary: Delete Proxy Namespaces Pods Name
      description: Proxy delete requests to pod.
      operationId: proxyDELETEPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsname-delete
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
    get:
      summary: Get Proxy Namespaces Pods Name
      description: Proxy get requests to pod.
      operationId: proxyGETPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsname-get
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
    post:
      summary: Post Proxy Namespaces Pods Name
      description: Proxy post requests to pod.
      operationId: proxyPOSTPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsname-post
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
    put:
      summary: Put Proxy Namespaces Pods Name
      description: Proxy put requests to pod.
      operationId: proxyPUTPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsname-put
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
  /api/v1beta3/proxy/namespaces/{namespaces}/pods/{name}/{path:*}:
    delete:
      summary: Delete Proxy Namespaces Pods Name Path *
      description: Proxy delete requests to pod.
      operationId: proxyDELETEPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsnamepath-delete
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
      - Path
      - '*'
    get:
      summary: Get Proxy Namespaces Pods Name Path *
      description: Proxy get requests to pod.
      operationId: proxyGETPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsnamepath-get
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
      - Path
      - '*'
    post:
      summary: Post Proxy Namespaces Pods Name Path *
      description: Proxy post requests to pod.
      operationId: proxyPOSTPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsnamepath-post
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
      - Path
      - '*'
    put:
      summary: Put Proxy Namespaces Pods Name Path *
      description: Proxy put requests to pod.
      operationId: proxyPUTPod
      x-api-path-slug: apiv1beta3proxynamespacesnamespacespodsnamepath-put
      parameters:
      - in: path
        name: name
        description: name of the Pod
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Pods
      - Name
      - Path
      - '*'
  /api/v1beta3/proxy/namespaces/{namespaces}/services/{name}:
    delete:
      summary: Delete Proxy Namespaces Services Name
      description: Proxy delete requests to service.
      operationId: proxyDELETEService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesname-delete
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
    get:
      summary: Get Proxy Namespaces Services Name
      description: Proxy get requests to service.
      operationId: proxyGETService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesname-get
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
    post:
      summary: Post Proxy Namespaces Services Name
      description: Proxy post requests to service.
      operationId: proxyPOSTService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesname-post
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
    put:
      summary: Put Proxy Namespaces Services Name
      description: Proxy put requests to service.
      operationId: proxyPUTService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesname-put
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
  /api/v1beta3/proxy/namespaces/{namespaces}/services/{name}/{path:*}:
    delete:
      summary: Delete Proxy Namespaces Services Name Path *
      description: Proxy delete requests to service.
      operationId: proxyDELETEService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-delete
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
      - Path
      - '*'
    get:
      summary: Get Proxy Namespaces Services Name Path *
      description: Proxy get requests to service.
      operationId: proxyGETService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-get
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
      - Path
      - '*'
    post:
      summary: Post Proxy Namespaces Services Name Path *
      description: Proxy post requests to service.
      operationId: proxyPOSTService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-post
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
      - Path
      - '*'
    put:
      summary: Put Proxy Namespaces Services Name Path *
      description: Proxy put requests to service.
      operationId: proxyPUTService
      x-api-path-slug: apiv1beta3proxynamespacesnamespacesservicesnamepath-put
      parameters:
      - in: path
        name: name
        description: name of the Service
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Namespaces
      - Services
      - Name
      - Path
      - '*'
  /api/v1beta3/proxy/nodes/{name}:
    delete:
      summary: Delete Proxy Nodes Name
      description: Proxy delete requests to node.
      operationId: proxyDELETENode
      x-api-path-slug: apiv1beta3proxynodesname-delete
      parameters:
      - in: path
        name: name
        description: name of the Node
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Nodes
      - Name
    get:
      summary: Get Proxy Nodes Name
      description: Proxy get requests to node.
      operationId: proxyGETNode
      x-api-path-slug: apiv1beta3proxynodesname-get
      parameters:
      - in: path
        name: name
        description: name of the Node
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Nodes
      - Name
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