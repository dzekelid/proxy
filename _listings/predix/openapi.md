swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/proxy/signature:
    post:
      summary: Post Proxy Signature
      description: Post proxy signature.
      operationId: postV1ProxySignature
      x-api-path-slug: v1proxysignature-post
      parameters:
      - in: header
        name: Authorization
        description: token
      - in: header
        name: Predix-Zone-Id
        description: serviceInstanceId
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Signature
  /v1/proxy/signature/details:
    post:
      summary: Post Proxy Signature Details
      description: Post proxy signature details.
      operationId: postV1ProxySignatureDetails
      x-api-path-slug: v1proxysignaturedetails-post
      parameters:
      - in: header
        name: Authorization
        description: token
      - in: header
        name: Predix-Zone-Id
        description: serviceInstanceId
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Signature
      - Details
  /v1/proxy/signature/extension:
    post:
      summary: Post Proxy Signature Extension
      description: Post proxy signature extension.
      operationId: postV1ProxySignatureExtension
      x-api-path-slug: v1proxysignatureextension-post
      parameters:
      - in: header
        name: Authorization
        description: token
      - in: header
        name: Predix-Zone-Id
        description: serviceInstanceId
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Signature
      - Extension
  /v1/proxy/analyses:
    get:
      summary: Analyses List
      description: Get list of Analyses
      operationId: retrieveNewUsingGET
      x-api-path-slug: v1proxyanalyses-get
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Analyses
  /v1/proxy/anomalies/report:
    get:
      summary: Anomalies Report
      description: Retrieves Anomalies Report
      operationId: retrieveReportUsingGET
      x-api-path-slug: v1proxyanomaliesreport-get
      parameters:
      - in: query
        name: analysisId
        description: Analysis Id
      - in: query
        name: dataSourceName
        description: Data Source name
      - in: query
        name: fromAnomaly
        description: Fetch from Anomaly in Analysis
      - in: query
        name: numOfTopFeatures
        description: Number of top features to fetch
      - in: query
        name: toAnomaly
        description: Fetch up to Anomaly in Analysis
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Anomalies
      - Report
  /v1/proxy/clusters/report:
    get:
      summary: Clusters Report
      description: Get Clusters report
      operationId: getClustersReportUsingGET
      x-api-path-slug: v1proxyclustersreport-get
      parameters:
      - in: query
        name: analysisId
        description: Analysis Id
      - in: query
        name: dataSourceName
        description: Data Source name
      - in: query
        name: filterOnlyUsedToCluster
        description: Filter Anomalies used to set create Clusters
      - in: query
        name: fromAnomaly
        description: Filter from Anomaly in Analysis
      - in: query
        name: toAnomaly
        description: Filter to Anomaly in Analysis
      - in: query
        name: withMinClusterSize
        description: Get only Clusters with minimum size
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Clusters
      - Report
  /v1/proxy/datasources/datasources:
    get:
      summary: Data Sources List
      description: Get list of all Data Sources
      operationId: getDataSourcesUsingGET
      x-api-path-slug: v1proxydatasourcesdatasources-get
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Datasources
      - Datasources
  /v1/proxy/datasources/process:
    post:
      summary: Upload a file
      description: Upload a data file
      operationId: processUsingPOST
      x-api-path-slug: v1proxydatasourcesprocess-post
      parameters:
      - in: query
        name: dataSourceName
        description: Data source name - up to 15 chars
      - in: formData
        name: file
        description: The file
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Datasources
      - Process