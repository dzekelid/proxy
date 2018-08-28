---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Add a fraud risk for Proxy detection
  description: Add a fraud risk for proxy detection.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/orders/4602125518/risks.json:
    post:
      summary: Add a fraud risk for Proxy detection
      description: Add a fraud risk for proxy detection.
      operationId: postAdminOrders4602125518Risks.json
      x-api-path-slug: adminorders4602125518risks-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fraud
      - RiskProxy
      - Detection
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