---
name: PayRun
x-slug: payrun
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Instructions
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO - Gets the pay instructions from the specified employee
  x-api-slug: employeremployeridemployeeemployeeidpayinstructions-get
  description: Get links to all pay instructions for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-get-openapi.md
- name: Pay Run.IO - Gets the reporting instructions from the specified employer
  x-api-slug: employeremployeridreportinginstructions-get
  description: Get links to all pay instructions for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructions-get-openapi.md
- name: Pay Run.IO - Runs the active pay instructions report
  x-api-slug: reportactpayinsrun-get
  description: Returns the result of the executed active pay instructions report for
    the given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/reportactpayinsrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/reportactpayinsrun-get-openapi.md
- name: Pay Run.IO - Deletes a pay instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete
  description: Delete the specified pay instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete-openapi.md
- name: Pay Run.IO - Gets the specified pay instruction from the employee
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get-openapi.md
- name: Pay Run.IO - Sparse Update of a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch
  description: Patches the specified pay instruction with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch-openapi.md
- name: Pay Run.IO - Update a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put
  description: Updates the existing specified pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put-openapi.md
- name: Pay Run.IO - Creates a new Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructions-post
  description: Creates a new pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-post-openapi.md
- name: Pay Run.IO - Deletes a reporting instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-delete
  description: Delete the specified reporting instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-delete-openapi.md
- name: Pay Run.IO - Gets the specified reporting instruction from the employer
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-get-openapi.md
- name: Pay Run.IO - Update a reporting Instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-put
  description: Updates the existing specified reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-put-openapi.md
- name: Pay Run.IO - Creates a new Reporting Instruction
  x-api-slug: employeremployeridreportinginstructions-post
  description: Creates a new reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructions-post-openapi.md
- name: Pay Run.IO - Gets the benefit pay instruction template
  x-api-slug: templatesbenefitpayinstruction-get
  description: Return the benefit pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the benefit YTD pay instruction template
  x-api-slug: templatesbenefitytdpayinstruction-get
  description: Return the benefit YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI adjustment pay instruction template
  x-api-slug: templatesniadjustmentpayinstruction-get
  description: Return the NI adjustment pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniadjustmentpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI pay instruction template
  x-api-slug: templatesnipayinstruction-get
  description: Return the NI pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesnipayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI YTD pay instruction template
  x-api-slug: templatesniytdpayinstruction-get
  description: Return the NI YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the P45 pay instruction template
  x-api-slug: templatesp45payinstruction-get
  description: Return the P45 pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesp45payinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay instruction template
  x-api-slug: templatespayinstruction-get
  description: Return the pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay run job instruction template
  x-api-slug: templatespayrunjobinstruction-get
  description: Return the pay run job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayrunjobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension pay instruction template
  x-api-slug: templatespensionpayinstruction-get
  description: Return the pension pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension YTD pay instruction template
  x-api-slug: templatespensionytdpayinstruction-get
  description: Return the pension YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the primitive pay instruction template
  x-api-slug: templatesprimitivepayinstruction-get
  description: Return the primitive pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesprimitivepayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the rti job instruction template
  x-api-slug: templatesrtijobinstruction-get
  description: Return the rti job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesrtijobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the salary pay instruction template
  x-api-slug: templatessalarypayinstruction-get
  description: Return the salary pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessalarypayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap pay instruction template
  x-api-slug: templatessappayinstruction-get
  description: Return the sap pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessappayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap YTD pay instruction template
  x-api-slug: templatessapytdpayinstruction-get
  description: Return the sap YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessapytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp pay instruction template
  x-api-slug: templatesshpppayinstruction-get
  description: Return the shpp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshpppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp YTD pay instruction template
  x-api-slug: templatesshppytdpayinstruction-get
  description: Return the shpp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp pay instruction template
  x-api-slug: templatessmppayinstruction-get
  description: Return the smp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp YTD pay instruction template
  x-api-slug: templatessmpytdpayinstruction-get
  description: Return the smp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmpytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp pay instruction template
  x-api-slug: templatesspppayinstruction-get
  description: Return the spp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesspppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp YTD pay instruction template
  x-api-slug: templatessppytdpayinstruction-get
  description: Return the spp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp pay instruction template
  x-api-slug: templatesssppayinstruction-get
  description: Return the ssp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesssppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp YTD pay instruction template
  x-api-slug: templatessspytdpayinstruction-get
  description: Return the ssp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessspytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan pay instruction template
  x-api-slug: templatesstudentloanpayinstruction-get
  description: Return the student loan pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan YTD pay instruction template
  x-api-slug: templatesstudentloanytdpayinstruction-get
  description: Return the student loan YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax pay instruction template
  x-api-slug: templatestaxpayinstruction-get
  description: Return the tax pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax YTD pay instruction template
  x-api-slug: templatestaxytdpayinstruction-get
  description: Return the tax YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Deletes a pay instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete
  description: Delete the specified pay instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete-openapi.md
- name: Pay Run.IO - Gets the specified pay instruction from the employee
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get-openapi.md
- name: Pay Run.IO - Sparse Update of a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch
  description: Patches the specified pay instruction with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch-openapi.md
- name: Pay Run.IO - Update a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put
  description: Updates the existing specified pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put-openapi.md
- name: Pay Run.IO - Creates a new Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructions-post
  description: Creates a new pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-post-openapi.md
- name: Pay Run.IO - Deletes a reporting instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-delete
  description: Delete the specified reporting instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-delete-openapi.md
- name: Pay Run.IO - Gets the specified reporting instruction from the employer
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-get-openapi.md
- name: Pay Run.IO - Update a reporting Instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-put
  description: Updates the existing specified reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-put-openapi.md
- name: Pay Run.IO - Creates a new Reporting Instruction
  x-api-slug: employeremployeridreportinginstructions-post
  description: Creates a new reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructions-post-openapi.md
- name: Pay Run.IO - Gets the benefit pay instruction template
  x-api-slug: templatesbenefitpayinstruction-get
  description: Return the benefit pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the benefit YTD pay instruction template
  x-api-slug: templatesbenefitytdpayinstruction-get
  description: Return the benefit YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI adjustment pay instruction template
  x-api-slug: templatesniadjustmentpayinstruction-get
  description: Return the NI adjustment pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniadjustmentpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI pay instruction template
  x-api-slug: templatesnipayinstruction-get
  description: Return the NI pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesnipayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI YTD pay instruction template
  x-api-slug: templatesniytdpayinstruction-get
  description: Return the NI YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the P45 pay instruction template
  x-api-slug: templatesp45payinstruction-get
  description: Return the P45 pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesp45payinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay instruction template
  x-api-slug: templatespayinstruction-get
  description: Return the pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay run job instruction template
  x-api-slug: templatespayrunjobinstruction-get
  description: Return the pay run job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayrunjobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension pay instruction template
  x-api-slug: templatespensionpayinstruction-get
  description: Return the pension pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension YTD pay instruction template
  x-api-slug: templatespensionytdpayinstruction-get
  description: Return the pension YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the primitive pay instruction template
  x-api-slug: templatesprimitivepayinstruction-get
  description: Return the primitive pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesprimitivepayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the rti job instruction template
  x-api-slug: templatesrtijobinstruction-get
  description: Return the rti job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesrtijobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the salary pay instruction template
  x-api-slug: templatessalarypayinstruction-get
  description: Return the salary pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessalarypayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap pay instruction template
  x-api-slug: templatessappayinstruction-get
  description: Return the sap pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessappayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap YTD pay instruction template
  x-api-slug: templatessapytdpayinstruction-get
  description: Return the sap YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessapytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp pay instruction template
  x-api-slug: templatesshpppayinstruction-get
  description: Return the shpp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshpppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp YTD pay instruction template
  x-api-slug: templatesshppytdpayinstruction-get
  description: Return the shpp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp pay instruction template
  x-api-slug: templatessmppayinstruction-get
  description: Return the smp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp YTD pay instruction template
  x-api-slug: templatessmpytdpayinstruction-get
  description: Return the smp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmpytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp pay instruction template
  x-api-slug: templatesspppayinstruction-get
  description: Return the spp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesspppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp YTD pay instruction template
  x-api-slug: templatessppytdpayinstruction-get
  description: Return the spp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp pay instruction template
  x-api-slug: templatesssppayinstruction-get
  description: Return the ssp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesssppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp YTD pay instruction template
  x-api-slug: templatessspytdpayinstruction-get
  description: Return the ssp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessspytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan pay instruction template
  x-api-slug: templatesstudentloanpayinstruction-get
  description: Return the student loan pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan YTD pay instruction template
  x-api-slug: templatesstudentloanytdpayinstruction-get
  description: Return the student loan YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax pay instruction template
  x-api-slug: templatestaxpayinstruction-get
  description: Return the tax pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax YTD pay instruction template
  x-api-slug: templatestaxytdpayinstruction-get
  description: Return the tax YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax YTD pay instruction template
  x-api-slug: templatestaxytdpayinstruction-get
  description: Return the tax YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the tax pay instruction template
  x-api-slug: templatestaxpayinstruction-get
  description: Return the tax pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatestaxpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan YTD pay instruction template
  x-api-slug: templatesstudentloanytdpayinstruction-get
  description: Return the student loan YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the student loan pay instruction template
  x-api-slug: templatesstudentloanpayinstruction-get
  description: Return the student loan pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesstudentloanpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp YTD pay instruction template
  x-api-slug: templatessspytdpayinstruction-get
  description: Return the ssp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessspytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the ssp pay instruction template
  x-api-slug: templatesssppayinstruction-get
  description: Return the ssp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesssppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp YTD pay instruction template
  x-api-slug: templatessppytdpayinstruction-get
  description: Return the spp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the spp pay instruction template
  x-api-slug: templatesspppayinstruction-get
  description: Return the spp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesspppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp YTD pay instruction template
  x-api-slug: templatessmpytdpayinstruction-get
  description: Return the smp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmpytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the smp pay instruction template
  x-api-slug: templatessmppayinstruction-get
  description: Return the smp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessmppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp YTD pay instruction template
  x-api-slug: templatesshppytdpayinstruction-get
  description: Return the shpp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshppytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the shpp pay instruction template
  x-api-slug: templatesshpppayinstruction-get
  description: Return the shpp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesshpppayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap YTD pay instruction template
  x-api-slug: templatessapytdpayinstruction-get
  description: Return the sap YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessapytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the sap pay instruction template
  x-api-slug: templatessappayinstruction-get
  description: Return the sap pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessappayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the salary pay instruction template
  x-api-slug: templatessalarypayinstruction-get
  description: Return the salary pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatessalarypayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the rti job instruction template
  x-api-slug: templatesrtijobinstruction-get
  description: Return the rti job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesrtijobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the primitive pay instruction template
  x-api-slug: templatesprimitivepayinstruction-get
  description: Return the primitive pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesprimitivepayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension YTD pay instruction template
  x-api-slug: templatespensionytdpayinstruction-get
  description: Return the pension YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pension pay instruction template
  x-api-slug: templatespensionpayinstruction-get
  description: Return the pension pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespensionpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay run job instruction template
  x-api-slug: templatespayrunjobinstruction-get
  description: Return the pay run job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayrunjobinstruction-get-openapi.md
- name: Pay Run.IO - Gets the pay instruction template
  x-api-slug: templatespayinstruction-get
  description: Return the pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatespayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the P45 pay instruction template
  x-api-slug: templatesp45payinstruction-get
  description: Return the P45 pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesp45payinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI YTD pay instruction template
  x-api-slug: templatesniytdpayinstruction-get
  description: Return the NI YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI pay instruction template
  x-api-slug: templatesnipayinstruction-get
  description: Return the NI pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesnipayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the NI adjustment pay instruction template
  x-api-slug: templatesniadjustmentpayinstruction-get
  description: Return the NI adjustment pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesniadjustmentpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the benefit YTD pay instruction template
  x-api-slug: templatesbenefitytdpayinstruction-get
  description: Return the benefit YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitytdpayinstruction-get-openapi.md
- name: Pay Run.IO - Gets the benefit pay instruction template
  x-api-slug: templatesbenefitpayinstruction-get
  description: Return the benefit pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/templatesbenefitpayinstruction-get-openapi.md
- name: Pay Run.IO - Creates a new Reporting Instruction
  x-api-slug: employeremployeridreportinginstructions-post
  description: Creates a new reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructions-post-openapi.md
- name: Pay Run.IO - Update a reporting Instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-put
  description: Updates the existing specified reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-put-openapi.md
- name: Pay Run.IO - Gets the specified reporting instruction from the employer
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-get-openapi.md
- name: Pay Run.IO - Deletes a reporting instruction
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-delete
  description: Delete the specified reporting instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-delete-openapi.md
- name: Pay Run.IO - Creates a new Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructions-post
  description: Creates a new pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-post-openapi.md
- name: Pay Run.IO - Update a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put
  description: Updates the existing specified pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put-openapi.md
- name: Pay Run.IO - Sparse Update of a Pay Instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch
  description: Patches the specified pay instruction with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch-openapi.md
- name: Pay Run.IO - Gets the specified pay instruction from the employee
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get-openapi.md
- name: Pay Run.IO - Deletes a pay instruction
  x-api-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete
  description: Delete the specified pay instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/instructions/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete-openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-api-gallery
  url: http://paypal.api.gallery.streamdata.io
- type: x-api-stack
  url: http://payrun.stack.network
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---