---
swagger: "2.0"
x-collection-name: Kubernetes
x-complete: 1
info:
  title: Kubernetes
  version: 1.0.0
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
    post:
      summary: Post Proxy Nodes Name
      description: Proxy post requests to node.
      operationId: proxyPOSTNode
      x-api-path-slug: apiv1beta3proxynodesname-post
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
    put:
      summary: Put Proxy Nodes Name
      description: Proxy put requests to node.
      operationId: proxyPUTNode
      x-api-path-slug: apiv1beta3proxynodesname-put
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
  /api/v1beta3/proxy/nodes/{name}/{path:*}:
    delete:
      summary: Delete Proxy Nodes Name Path *
      description: Proxy delete requests to node.
      operationId: proxyDELETENode
      x-api-path-slug: apiv1beta3proxynodesnamepath-delete
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
      - Path
      - '*'
    get:
      summary: Get Proxy Nodes Name Path *
      description: Proxy get requests to node.
      operationId: proxyGETNode
      x-api-path-slug: apiv1beta3proxynodesnamepath-get
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
      - Path
      - '*'
    post:
      summary: Post Proxy Nodes Name Path *
      description: Proxy post requests to node.
      operationId: proxyPOSTNode
      x-api-path-slug: apiv1beta3proxynodesnamepath-post
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
      - Path
      - '*'
    put:
      summary: Put Proxy Nodes Name Path *
      description: Proxy put requests to node.
      operationId: proxyPUTNode
      x-api-path-slug: apiv1beta3proxynodesnamepath-put
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
      - Path
      - '*'
---