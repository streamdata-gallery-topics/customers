---
swagger: "2.0"
info:
  title: Akamai API List Customers
  description: List Customers
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-saas-registration/v1/customers/:
    get:
      summary: List Customers
      description: List Customers
      operationId: configsaasregistrationv1customerscontractid
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - saas
      - registration
      - customers
      - contract
definitions: []
x-collection-name: Akamai
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