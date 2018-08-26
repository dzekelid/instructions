---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Runs the active pay instructions report
  description: Returns the result of the executed active pay instructions report for
    the given query parameters
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayInstructions:
    get:
      summary: Gets the pay instructions from the specified employee
      description: Get links to all pay instructions for the specified employee
      operationId: GetPayInstructionsFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructions-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instructions
      - From
      - Specified
      - Employee
  /Employer/{EmployerId}/ReportingInstructions:
    get:
      summary: Gets the reporting instructions from the specified employer
      description: Get links to all pay instructions for the specified employee
      operationId: GetReportingInstructionsFromEmployer
      x-api-path-slug: employeremployeridreportinginstructions-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Reporting
      - Instructions
      - From
      - Specified
      - Employer
  /Report/ACTPAYINS/run:
    get:
      summary: Runs the active pay instructions report
      description: Returns the result of the executed active pay instructions report
        for the given query parameters
      operationId: GetActivePayInstructionsReportOutput
      x-api-path-slug: reportactpayinsrun-get
      parameters:
      - in: query
        name: ActiveOn
        description: The active date to consider
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: query
        name: EmployeeKey
        description: The employee unique key
      - in: query
        name: EmployerKey
        description: The employer unique key
      - in: query
        name: Type
        description: the data type to filter on
      responses:
        200:
          description: OK
      tags:
      - Runs
      - Active
      - Pay
      - Instructions
      - Report
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