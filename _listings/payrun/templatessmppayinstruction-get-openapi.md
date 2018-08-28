---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Gets the smp pay instruction template
  description: Return the smp pay instruction data object template
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
    post:
      summary: Creates a new Pay Instruction
      description: Creates a new pay instruction object
      operationId: PostPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructions-post
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
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Pay
      - Instruction
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
    post:
      summary: Creates a new Reporting Instruction
      description: Creates a new reporting instruction object
      operationId: PostReportingInstruction
      x-api-path-slug: employeremployeridreportinginstructions-post
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
      - Creates
      - New
      - Reporting
      - Instruction
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
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}:
    delete:
      summary: Deletes a pay instruction
      description: Delete the specified pay instruction
      operationId: DeletePayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete
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
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
    get:
      summary: Gets the specified pay instruction from the employee
      description: Returns the specified pay instruction from employee
      operationId: GetPayInstructionFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get
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
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Instruction
      - From
      - Employee
    patch:
      summary: Sparse Update of a Pay Instruction
      description: Patches the specified pay instruction with the supplied values
      operationId: PatchPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch
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
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Sparse
      - ""
      - Of
      - Pay
      - Instruction
    put:
      summary: Update a Pay Instruction
      description: Updates the existing specified pay instruction object
      operationId: PutPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put
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
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
  /Employer/{EmployerId}/ReportingInstruction/{ReportingInstructionId}:
    delete:
      summary: Deletes a reporting instruction
      description: Delete the specified reporting instruction
      operationId: DeleteReportingInstruction
      x-api-path-slug: employeremployeridreportinginstructionreportinginstructionid-delete
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
      - in: path
        name: ReportingInstructionId
        description: The reporting instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Reporting
      - Instruction
    get:
      summary: Gets the specified reporting instruction from the employer
      description: Returns the specified pay instruction from employee
      operationId: GetReportingInstructionFromEmployer
      x-api-path-slug: employeremployeridreportinginstructionreportinginstructionid-get
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
      - in: path
        name: ReportingInstructionId
        description: The reporting instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Reporting
      - Instruction
      - From
      - Employer
    put:
      summary: Update a reporting Instruction
      description: Updates the existing specified reporting instruction object
      operationId: PutReportingInstruction
      x-api-path-slug: employeremployeridreportinginstructionreportinginstructionid-put
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
      - in: path
        name: ReportingInstructionId
        description: The reporting instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Reporting
      - Instruction
  /Templates/benefitpayinstruction:
    get:
      summary: Gets the benefit pay instruction template
      description: Return the benefit pay instruction data object template
      operationId: GetBenefitPayInstructionTemplate
      x-api-path-slug: templatesbenefitpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Benefit
      - Pay
      - Instruction
      - Template
  /Templates/benefitytdpayinstruction:
    get:
      summary: Gets the benefit YTD pay instruction template
      description: Return the benefit YTD pay instruction data object template
      operationId: GetBenefitYtdPayInstructionTemplate
      x-api-path-slug: templatesbenefitytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Benefit
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/niadjustmentpayinstruction:
    get:
      summary: Gets the NI adjustment pay instruction template
      description: Return the NI adjustment pay instruction data object template
      operationId: GetNiAdjustmentPayInstructionTemplate
      x-api-path-slug: templatesniadjustmentpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - Adjustment
      - Pay
      - Instruction
      - Template
  /Templates/nipayinstruction:
    get:
      summary: Gets the NI pay instruction template
      description: Return the NI pay instruction data object template
      operationId: GetNiPayInstructionTemplate
      x-api-path-slug: templatesnipayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - Pay
      - Instruction
      - Template
  /Templates/niytdpayinstruction:
    get:
      summary: Gets the NI YTD pay instruction template
      description: Return the NI YTD pay instruction data object template
      operationId: GetNiYtdPayInstructionTemplate
      x-api-path-slug: templatesniytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/p45payinstruction:
    get:
      summary: Gets the P45 pay instruction template
      description: Return the P45 pay instruction data object template
      operationId: GetP45PayInstructionTemplate
      x-api-path-slug: templatesp45payinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - P45
      - Pay
      - Instruction
      - Template
  /Templates/payinstruction:
    get:
      summary: Gets the pay instruction template
      description: Return the pay instruction data object template
      operationId: GetPayInstructionTemplate
      x-api-path-slug: templatespayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
      - Template
  /Templates/payrunjobinstruction:
    get:
      summary: Gets the pay run job instruction template
      description: Return the pay run job instruction data object template
      operationId: GetPayRunJobInstructionTemplate
      x-api-path-slug: templatespayrunjobinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Run
      - Job
      - Instruction
      - Template
  /Templates/pensionpayinstruction:
    get:
      summary: Gets the pension pay instruction template
      description: Return the pension pay instruction data object template
      operationId: GetPensionPayInstructionTemplate
      x-api-path-slug: templatespensionpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pension
      - Pay
      - Instruction
      - Template
  /Templates/pensionytdpayinstruction:
    get:
      summary: Gets the pension YTD pay instruction template
      description: Return the pension YTD pay instruction data object template
      operationId: GetPensionYtdPayInstructionTemplate
      x-api-path-slug: templatespensionytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pension
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/primitivepayinstruction:
    get:
      summary: Gets the primitive pay instruction template
      description: Return the primitive pay instruction data object template
      operationId: GetPrimitivePayInstructionTemplate
      x-api-path-slug: templatesprimitivepayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Primitive
      - Pay
      - Instruction
      - Template
  /Templates/rtijobinstruction:
    get:
      summary: Gets the rti job instruction template
      description: Return the rti job instruction data object template
      operationId: GetRtiJobInstructionTemplate
      x-api-path-slug: templatesrtijobinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Rti
      - Job
      - Instruction
      - Template
  /Templates/salarypayinstruction:
    get:
      summary: Gets the salary pay instruction template
      description: Return the salary pay instruction data object template
      operationId: GetSalaryPayInstructionTemplate
      x-api-path-slug: templatessalarypayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Salary
      - Pay
      - Instruction
      - Template
  /Templates/sappayinstruction:
    get:
      summary: Gets the sap pay instruction template
      description: Return the sap pay instruction data object template
      operationId: GetSapPayInstructionTemplate
      x-api-path-slug: templatessappayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Sap
      - Pay
      - Instruction
      - Template
  /Templates/sapytdpayinstruction:
    get:
      summary: Gets the sap YTD pay instruction template
      description: Return the sap YTD pay instruction data object template
      operationId: GetSapYtdPayInstructionTemplate
      x-api-path-slug: templatessapytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Sap
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/shpppayinstruction:
    get:
      summary: Gets the shpp pay instruction template
      description: Return the shpp pay instruction data object template
      operationId: GetShppPayInstructionTemplate
      x-api-path-slug: templatesshpppayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Shpp
      - Pay
      - Instruction
      - Template
  /Templates/shppytdpayinstruction:
    get:
      summary: Gets the shpp YTD pay instruction template
      description: Return the shpp YTD pay instruction data object template
      operationId: GetShppYtdPayInstructionTemplate
      x-api-path-slug: templatesshppytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Shpp
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/smppayinstruction:
    get:
      summary: Gets the smp pay instruction template
      description: Return the smp pay instruction data object template
      operationId: GetSmpPayInstructionTemplate
      x-api-path-slug: templatessmppayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Smp
      - Pay
      - Instruction
      - Template
  /Templates/smpytdpayinstruction:
    get:
      summary: Gets the smp YTD pay instruction template
      description: Return the smp YTD pay instruction data object template
      operationId: GetSmpYtdPayInstructionTemplate
      x-api-path-slug: templatessmpytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Smp
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/spppayinstruction:
    get:
      summary: Gets the spp pay instruction template
      description: Return the spp pay instruction data object template
      operationId: GetSppPayInstructionTemplate
      x-api-path-slug: templatesspppayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Spp
      - Pay
      - Instruction
      - Template
  /Templates/sppytdpayinstruction:
    get:
      summary: Gets the spp YTD pay instruction template
      description: Return the spp YTD pay instruction data object template
      operationId: GetSppYtdPayInstructionTemplate
      x-api-path-slug: templatessppytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Spp
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/ssppayinstruction:
    get:
      summary: Gets the ssp pay instruction template
      description: Return the ssp pay instruction data object template
      operationId: GetSspPayInstructionTemplate
      x-api-path-slug: templatesssppayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Ssp
      - Pay
      - Instruction
      - Template
  /Templates/sspytdpayinstruction:
    get:
      summary: Gets the ssp YTD pay instruction template
      description: Return the ssp YTD pay instruction data object template
      operationId: GetSspYtdPayInstructionTemplate
      x-api-path-slug: templatessspytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Ssp
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/studentloanpayinstruction:
    get:
      summary: Gets the student loan pay instruction template
      description: Return the student loan pay instruction data object template
      operationId: GetStudentLoanPayInstructionTemplate
      x-api-path-slug: templatesstudentloanpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Student
      - Loan
      - Pay
      - Instruction
      - Template
  /Templates/studentloanytdpayinstruction:
    get:
      summary: Gets the student loan YTD pay instruction template
      description: Return the student loan YTD pay instruction data object template
      operationId: GetStudentLoanYtdPayInstructionTemplate
      x-api-path-slug: templatesstudentloanytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Student
      - Loan
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/taxpayinstruction:
    get:
      summary: Gets the tax pay instruction template
      description: Return the tax pay instruction data object template
      operationId: GetTaxPayInstructionTemplate
      x-api-path-slug: templatestaxpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Tax
      - Pay
      - Instruction
      - Template
  /Templates/taxytdpayinstruction:
    get:
      summary: Gets the tax YTD pay instruction template
      description: Return the tax YTD pay instruction data object template
      operationId: GetTaxYtdPayInstructionTemplate
      x-api-path-slug: templatestaxytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Tax
      - YTD
      - Pay
      - Instruction
      - Template
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