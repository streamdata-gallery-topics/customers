---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Customers
  description: Retrieve a single customer..
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customer_categories/{id}/customers.json:
    delete:
      summary: Delete Customer Categories Customers
      description: Delete customers from an existing customercategory..
      operationId: deleteCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    get:
      summary: Get Customer Categories Customers
      description: Retrieves the customers in a customercategory..
      operationId: getCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    post:
      summary: Post Customer Categories Customers
      description: Adds customers to a customercategory..
      operationId: postCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
  /customers.json:
    get:
      summary: Get Customers
      description: Retrieve all customers..
      operationId: getCustomers.json
      x-api-path-slug: customers-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
    post:
      summary: Post Customers
      description: Create a new customer..
      operationId: postCustomers.json
      x-api-path-slug: customers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
  /customers/email/{email}.json:
    get:
      summary: Get Customers Email Email
      description: Retrieve a single customer..
      operationId: getCustomersEmailEmail.json
      x-api-path-slug: customersemailemail-json-get
      parameters:
      - in: path
        name: email
        description: Email of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Email
      - Email
      - Json
  /customers/{id}.json:
    delete:
      summary: Delete Customers
      description: Delete an existing category..
      operationId: deleteCustomers.json
      x-api-path-slug: customersid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
    get:
      summary: Get Customers
      description: Retrieve a single customer..
      operationId: getCustomers.json
      x-api-path-slug: customersid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
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