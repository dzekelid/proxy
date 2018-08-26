---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
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
---