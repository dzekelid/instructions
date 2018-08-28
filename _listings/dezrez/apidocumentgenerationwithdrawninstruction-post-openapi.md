---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Generates a Withdrawn Instruction letter correspondence to the vendor
    of a particular marketing role
  version: 1.0.0
  description: Generates a withdrawn instruction letter correspondence to the vendor
    of a particular marketing role.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/instruction:
    post:
      summary: Generates a Instruction letter correspondence to the vendor of a particular
        marketing role
      description: Generates a instruction letter correspondence to the vendor of
        a particular marketing role.
      operationId: DocumentGeneration_GenerateInstructionLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationinstruction-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Instruction
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/documentgeneration/withdrawninstruction:
    post:
      summary: Generates a Withdrawn Instruction letter correspondence to the vendor
        of a particular marketing role
      description: Generates a withdrawn instruction letter correspondence to the
        vendor of a particular marketing role.
      operationId: DocumentGeneration_GenerateWithdrawnInstructionLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationwithdrawninstruction-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Withdrawn
      - Instruction
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/progression/auction/instructforauction:
    post:
      summary: Instructs a role to be let
      description: Instructs a role to be let.
      operationId: AuctionProgression_InstructForAuctionByinstructToSellCommandDataContract
      x-api-path-slug: apiprogressionauctioninstructforauction-post
      parameters:
      - in: body
        name: instructToSellCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Let
  /api/progression/lettings/instructtolet:
    post:
      summary: Instructs a role to be let
      description: Instructs a role to be let.
      operationId: LettingsProgression_InstructToLetByinstructToLetCommandDataContract
      x-api-path-slug: apiprogressionlettingsinstructtolet-post
      parameters:
      - in: body
        name: instructToLetCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Let
  /api/progression/sales/instructtosell:
    post:
      summary: Instructs a role to be sold
      description: Instructs a role to be sold.
      operationId: SalesProgression_InstructToSellByinstructToSellCommandDataContract
      x-api-path-slug: apiprogressionsalesinstructtosell-post
      parameters:
      - in: body
        name: instructToSellCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Sold
  /api/progression/lettings/withdrawInstruction:
    post:
      summary: Withdraw a letting at the end of let
      description: Withdraw a letting at the end of let.
      operationId: LettingsProgression_WithdrawInstructionBylettingInstructionCommandData
      x-api-path-slug: apiprogressionlettingswithdrawinstruction-post
      parameters:
      - in: body
        name: lettingInstructionCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Withdraw
      - Letting
      - At
      - End
      - Of
      - Let
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