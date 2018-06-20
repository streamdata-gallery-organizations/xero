---
name: Xero
x-slug: xero
description: Xero is the QuickBooks alternative. Use Xero accounting software to manage
  invoicing, bank reconciliation, bookkeeping & more. Start a free trial today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
x-kinRank: "8"
x-alexaRank: "2158"
tags: Xero
created: "2018-06-19"
modified: "2018-06-19"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/apis.md
specificationVersion: "0.14"
apis:
- name: Clarity Accounting Get Accounts
  x-api-slug: clarity-accounting
  description: Retrieve the chart of accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accounts-get-openapi.md
- name: Clarity Accounting Post Accounts
  x-api-slug: clarity-accounting
  description: Post accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accounts-post-openapi.md
- name: Clarity Accounting Put Accounts
  x-api-slug: clarity-accounting
  description: Put accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accounts-put-openapi.md
- name: Clarity Accounting X-related-model Accounts
  x-api-slug: clarity-accounting
  description: X-related-model accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accounts-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Accounts
  x-api-slug: clarity-accounting
  description: Delete accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountid-delete-openapi.md
- name: Clarity Accounting Get Accounts
  x-api-slug: clarity-accounting
  description: Get accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountid-get-openapi.md
- name: Clarity Accounting Post Accounts
  x-api-slug: clarity-accounting
  description: Post accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountid-post-openapi.md
- name: Clarity Accounting X-related-model Accounts
  x-api-slug: clarity-accounting
  description: X-related-model accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Accounts Attachments
  x-api-slug: clarity-accounting
  description: Get accounts account attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments
  tags: Accounts,AccountID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountidattachments-get-openapi.md
- name: Clarity Accounting Get Accounts Attachments Filename
  x-api-slug: clarity-accounting
  description: Get accounts account attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments/{FileName}
  tags: Accounts,AccountID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Accounts Attachments Filename
  x-api-slug: clarity-accounting
  description: Post accounts account attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments/{FileName}
  tags: Accounts,AccountID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/accountsaccountidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Bank Transactions
  x-api-slug: clarity-accounting
  description: Get banktransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions
  tags: BankTransactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactions-get-openapi.md
- name: Clarity Accounting Post Bank Transactions
  x-api-slug: clarity-accounting
  description: Post banktransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions
  tags: BankTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactions-post-openapi.md
- name: Clarity Accounting Put Bank Transactions
  x-api-slug: clarity-accounting
  description: Put banktransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions
  tags: BankTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactions-put-openapi.md
- name: Clarity Accounting X-related-model Bank Transactions
  x-api-slug: clarity-accounting
  description: X-related-model banktransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions
  tags: BankTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactions-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Bank Transactions Banktransaction
  x-api-slug: clarity-accounting
  description: Get banktransactions banktransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}
  tags: BankTransactions,BankTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionid-get-openapi.md
- name: Clarity Accounting Post Bank Transactions Banktransaction
  x-api-slug: clarity-accounting
  description: Post banktransactions banktransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}
  tags: BankTransactions,BankTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionid-post-openapi.md
- name: Clarity Accounting X-related-model Bank Transactions Banktransaction
  x-api-slug: clarity-accounting
  description: X-related-model banktransactions banktransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}
  tags: BankTransactions,BankTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Bank Transactions Banktransaction Attachments
  x-api-slug: clarity-accounting
  description: Get banktransactions banktransaction attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}/Attachments
  tags: BankTransactions,BankTransactionID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionidattachments-get-openapi.md
- name: Clarity Accounting Get Bank Transactions Banktransaction Attachments Filename
  x-api-slug: clarity-accounting
  description: Get banktransactions banktransaction attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}/Attachments/{FileName}
  tags: BankTransactions,BankTransactionID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Bank Transactions Banktransaction Attachments Filename
  x-api-slug: clarity-accounting
  description: Post banktransactions banktransaction attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransactions/{BankTransactionID}/Attachments/{FileName}
  tags: BankTransactions,BankTransactionID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransactionsbanktransactionidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Banks Transfers
  x-api-slug: clarity-accounting
  description: Get banktransfers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers
  tags: BankTransfers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfers-get-openapi.md
- name: Clarity Accounting Put Banks Transfers
  x-api-slug: clarity-accounting
  description: Put banktransfers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers
  tags: BankTransfers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfers-put-openapi.md
- name: Clarity Accounting X-related-model Banks Transfers
  x-api-slug: clarity-accounting
  description: X-related-model banktransfers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers
  tags: BankTransfers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfers-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Banks Transfers
  x-api-slug: clarity-accounting
  description: Get banktransfers banktransfer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers/{BankTransferID}
  tags: BankTransfers,BankTransferID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfersbanktransferid-get-openapi.md
- name: Clarity Accounting X-related-model Banks Transfers
  x-api-slug: clarity-accounting
  description: X-related-model banktransfers banktransfer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers/{BankTransferID}
  tags: BankTransfers,BankTransferID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfersbanktransferid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Banks Transfers Attachments Filename
  x-api-slug: clarity-accounting
  description: Get banktransfers banktransfer attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers/{BankTransferID}/Attachments/{FileName}
  tags: BankTransfers,BankTransferID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfersbanktransferidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Banks Transfers Attachments Filename
  x-api-slug: clarity-accounting
  description: Post banktransfers banktransfer attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BankTransfers/{BankTransferID}/Attachments/{FileName}
  tags: BankTransfers,BankTransferID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/banktransfersbanktransferidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Brandingthemes
  x-api-slug: clarity-accounting
  description: Get brandingthemes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BrandingThemes
  tags: BrandingThemes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/brandingthemes-get-openapi.md
- name: Clarity Accounting X-related-model Brandingthemes
  x-api-slug: clarity-accounting
  description: X-related-model brandingthemes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BrandingThemes
  tags: BrandingThemes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/brandingthemes-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Brandingthemes Brandingtheme
  x-api-slug: clarity-accounting
  description: Get brandingthemes brandingtheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BrandingThemes/{BrandingThemeID}
  tags: BrandingThemes,BrandingThemeID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/brandingthemesbrandingthemeid-get-openapi.md
- name: Clarity Accounting X-related-model Brandingthemes Brandingtheme
  x-api-slug: clarity-accounting
  description: X-related-model brandingthemes brandingtheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//BrandingThemes/{BrandingThemeID}
  tags: BrandingThemes,BrandingThemeID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/brandingthemesbrandingthemeid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Contactgroups
  x-api-slug: clarity-accounting
  description: Get contactgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups
  tags: ContactGroups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroups-get-openapi.md
- name: Clarity Accounting Post Contactgroups
  x-api-slug: clarity-accounting
  description: Post contactgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups
  tags: ContactGroups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroups-post-openapi.md
- name: Clarity Accounting Put Contactgroups
  x-api-slug: clarity-accounting
  description: Put contactgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups
  tags: ContactGroups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroups-put-openapi.md
- name: Clarity Accounting X-related-model Contactgroups
  x-api-slug: clarity-accounting
  description: X-related-model contactgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups
  tags: ContactGroups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroups-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Contact Groups
  x-api-slug: clarity-accounting
  description: Delete contactgroups contactgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}
  tags: ContactGroups,ContactGroupID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupid-delete-openapi.md
- name: Clarity Accounting Get Contact Groups
  x-api-slug: clarity-accounting
  description: Get contactgroups contactgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}
  tags: ContactGroups,ContactGroupID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupid-get-openapi.md
- name: Clarity Accounting Post Contact Groups
  x-api-slug: clarity-accounting
  description: Post contactgroups contactgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}
  tags: ContactGroups,ContactGroupID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupid-post-openapi.md
- name: Clarity Accounting X-related-model Contact Groups
  x-api-slug: clarity-accounting
  description: X-related-model contactgroups contactgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}
  tags: ContactGroups,ContactGroupID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupid-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Contact Groups Contacts
  x-api-slug: clarity-accounting
  description: Delete contactgroups contactgroup contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}/Contacts
  tags: ContactGroups,ContactGroupID,Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontacts-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontacts-delete-openapi.md
- name: Clarity Accounting Put Contact Groups Contacts
  x-api-slug: clarity-accounting
  description: Put contactgroups contactgroup contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}/Contacts
  tags: ContactGroups,ContactGroupID,Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontacts-put-openapi.md
- name: Clarity Accounting X-related-model Contact Groups Contacts
  x-api-slug: clarity-accounting
  description: X-related-model contactgroups contactgroup contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}/Contacts
  tags: ContactGroups,ContactGroupID,Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontacts-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Contact Groups Contacts Contact
  x-api-slug: clarity-accounting
  description: Delete contactgroups contactgroup contacts contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}/Contacts/{ContactID}
  tags: ContactGroups,ContactGroupID,Contacts,ContactID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontactscontactid-delete-openapi.md
- name: Clarity Accounting X-related-model Contact Groups Contacts Contact
  x-api-slug: clarity-accounting
  description: X-related-model contactgroups contactgroup contacts contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ContactGroups/{ContactGroupID}/Contacts/{ContactID}
  tags: ContactGroups,ContactGroupID,Contacts,ContactID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactgroupscontactgroupidcontactscontactid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Contacts
  x-api-slug: clarity-accounting
  description: Get contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contacts-get-openapi.md
- name: Clarity Accounting Post Contacts
  x-api-slug: clarity-accounting
  description: Post contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contacts-post-openapi.md
- name: Clarity Accounting Put Contacts
  x-api-slug: clarity-accounting
  description: Put contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contacts-put-openapi.md
- name: Clarity Accounting X-related-model Contacts
  x-api-slug: clarity-accounting
  description: X-related-model contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contacts-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Contacts Contact
  x-api-slug: clarity-accounting
  description: Get contacts contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}
  tags: Contacts,ContactID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactid-get-openapi.md
- name: Clarity Accounting Post Contacts Contact
  x-api-slug: clarity-accounting
  description: Post contacts contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}
  tags: Contacts,ContactID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactid-post-openapi.md
- name: Clarity Accounting X-related-model Contacts Contact
  x-api-slug: clarity-accounting
  description: X-related-model contacts contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}
  tags: Contacts,ContactID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Contacts Contact Attachments
  x-api-slug: clarity-accounting
  description: Get contacts contact attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}/Attachments
  tags: Contacts,ContactID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactidattachments-get-openapi.md
- name: Clarity Accounting Get Contacts Contact Attachments Filename
  x-api-slug: clarity-accounting
  description: Get contacts contact attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}/Attachments/{FileName}
  tags: Contacts,ContactID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Contacts Contact Attachments Filename
  x-api-slug: clarity-accounting
  description: Post contacts contact attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Contacts/{ContactID}/Attachments/{FileName}
  tags: Contacts,ContactID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/contactscontactidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Creditnotes
  x-api-slug: clarity-accounting
  description: Get creditnotes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes
  tags: CreditNotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotes-get-openapi.md
- name: Clarity Accounting Post Creditnotes
  x-api-slug: clarity-accounting
  description: Post creditnotes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes
  tags: CreditNotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotes-post-openapi.md
- name: Clarity Accounting Put Creditnotes
  x-api-slug: clarity-accounting
  description: Put creditnotes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes
  tags: CreditNotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotes-put-openapi.md
- name: Clarity Accounting X-related-model Creditnotes
  x-api-slug: clarity-accounting
  description: X-related-model creditnotes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes
  tags: CreditNotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotes-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Creditnotes Creditnote
  x-api-slug: clarity-accounting
  description: Get creditnotes creditnote.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}
  tags: CreditNotes,CreditNoteID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteid-get-openapi.md
- name: Clarity Accounting Post Creditnotes Creditnote
  x-api-slug: clarity-accounting
  description: Post creditnotes creditnote.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}
  tags: CreditNotes,CreditNoteID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteid-post-openapi.md
- name: Clarity Accounting X-related-model Creditnotes Creditnote
  x-api-slug: clarity-accounting
  description: X-related-model creditnotes creditnote.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}
  tags: CreditNotes,CreditNoteID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteid-xrelatedmodel-openapi.md
- name: Clarity Accounting Put Creditnotes Creditnote Allocations
  x-api-slug: clarity-accounting
  description: Put creditnotes creditnote allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}/Allocations
  tags: CreditNotes,CreditNoteID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteidallocations-put-openapi.md
- name: Clarity Accounting X-related-model Creditnotes Creditnote Allocations
  x-api-slug: clarity-accounting
  description: X-related-model creditnotes creditnote allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}/Allocations
  tags: CreditNotes,CreditNoteID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteidallocations-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Creditnotes Creditnote Attachments
  x-api-slug: clarity-accounting
  description: Get creditnotes creditnote attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}/Attachments
  tags: CreditNotes,CreditNoteID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteidattachments-get-openapi.md
- name: Clarity Accounting Get Creditnotes Creditnote Attachments Filename
  x-api-slug: clarity-accounting
  description: Get creditnotes creditnote attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}/Attachments/{FileName}
  tags: CreditNotes,CreditNoteID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Creditnotes Creditnote Attachments Filename
  x-api-slug: clarity-accounting
  description: Post creditnotes creditnote attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//CreditNotes/{CreditNoteID}/Attachments/{FileName}
  tags: CreditNotes,CreditNoteID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/creditnotescreditnoteidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Currencies
  x-api-slug: clarity-accounting
  description: Get currencies.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Currencies
  tags: Currencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/currencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/currencies-get-openapi.md
- name: Clarity Accounting Put Currencies
  x-api-slug: clarity-accounting
  description: Put currencies.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Currencies
  tags: Currencies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/currencies-put-openapi.md
- name: Clarity Accounting X-related-model Currencies
  x-api-slug: clarity-accounting
  description: X-related-model currencies.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Currencies
  tags: Currencies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/currencies-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Employees
  x-api-slug: clarity-accounting
  description: Get employees.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees
  tags: Employees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employees-get-openapi.md
- name: Clarity Accounting Post Employees
  x-api-slug: clarity-accounting
  description: Post employees.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees
  tags: Employees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employees-post-openapi.md
- name: Clarity Accounting Put Employees
  x-api-slug: clarity-accounting
  description: Put employees.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees
  tags: Employees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employees-put-openapi.md
- name: Clarity Accounting X-related-model Employees
  x-api-slug: clarity-accounting
  description: X-related-model employees.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees
  tags: Employees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employees-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Employees Employee
  x-api-slug: clarity-accounting
  description: Get employees employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees/{EmployeeID}
  tags: Employees,EmployeeID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employeesemployeeid-get-openapi.md
- name: Clarity Accounting Post Employees Employee
  x-api-slug: clarity-accounting
  description: Post employees employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees/{EmployeeID}
  tags: Employees,EmployeeID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employeesemployeeid-post-openapi.md
- name: Clarity Accounting X-related-model Employees Employee
  x-api-slug: clarity-accounting
  description: X-related-model employees employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Employees/{EmployeeID}
  tags: Employees,EmployeeID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/employeesemployeeid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Expenseclaims
  x-api-slug: clarity-accounting
  description: Get expenseclaims.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims
  tags: ExpenseClaims
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaims-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaims-get-openapi.md
- name: Clarity Accounting Post Expenseclaims
  x-api-slug: clarity-accounting
  description: Post expenseclaims.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims
  tags: ExpenseClaims
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaims-post-openapi.md
- name: Clarity Accounting Put Expenseclaims
  x-api-slug: clarity-accounting
  description: Put expenseclaims.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims
  tags: ExpenseClaims
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaims-put-openapi.md
- name: Clarity Accounting X-related-model Expenseclaims
  x-api-slug: clarity-accounting
  description: X-related-model expenseclaims.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims
  tags: ExpenseClaims
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaims-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Expenseclaims Expenseclaim
  x-api-slug: clarity-accounting
  description: Get expenseclaims expenseclaim.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims/{ExpenseClaimID}
  tags: ExpenseClaims,ExpenseClaimID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaimsexpenseclaimid-get-openapi.md
- name: Clarity Accounting Post Expenseclaims Expenseclaim
  x-api-slug: clarity-accounting
  description: Post expenseclaims expenseclaim.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims/{ExpenseClaimID}
  tags: ExpenseClaims,ExpenseClaimID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaimsexpenseclaimid-post-openapi.md
- name: Clarity Accounting X-related-model Expenseclaims Expenseclaim
  x-api-slug: clarity-accounting
  description: X-related-model expenseclaims expenseclaim.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ExpenseClaims/{ExpenseClaimID}
  tags: ExpenseClaims,ExpenseClaimID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/expenseclaimsexpenseclaimid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Invoices
  x-api-slug: clarity-accounting
  description: Get invoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices
  tags: Invoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoices-get-openapi.md
- name: Clarity Accounting Post Invoices
  x-api-slug: clarity-accounting
  description: Post invoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices
  tags: Invoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoices-post-openapi.md
- name: Clarity Accounting Put Invoices
  x-api-slug: clarity-accounting
  description: Put invoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices
  tags: Invoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoices-put-openapi.md
- name: Clarity Accounting X-related-model Invoices
  x-api-slug: clarity-accounting
  description: X-related-model invoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices
  tags: Invoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoices-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Invoices Invoice
  x-api-slug: clarity-accounting
  description: Get invoices invoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}
  tags: Invoices,InvoiceID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceid-get-openapi.md
- name: Clarity Accounting Post Invoices Invoice
  x-api-slug: clarity-accounting
  description: Post invoices invoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}
  tags: Invoices,InvoiceID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceid-post-openapi.md
- name: Clarity Accounting X-related-model Invoices Invoice
  x-api-slug: clarity-accounting
  description: X-related-model invoices invoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}
  tags: Invoices,InvoiceID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Invoices Invoice Attachments
  x-api-slug: clarity-accounting
  description: Get invoices invoice attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}/Attachments
  tags: Invoices,InvoiceID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceidattachments-get-openapi.md
- name: Clarity Accounting Get Invoices Invoice Attachments Filename
  x-api-slug: clarity-accounting
  description: Get invoices invoice attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}/Attachments/{FileName}
  tags: Invoices,InvoiceID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Invoices Invoice Attachments Filename
  x-api-slug: clarity-accounting
  description: Post invoices invoice attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}/Attachments/{FileName}
  tags: Invoices,InvoiceID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Invoices Invoice Onlineinvoice
  x-api-slug: clarity-accounting
  description: Get invoices invoice onlineinvoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}/OnlineInvoice
  tags: Invoices,InvoiceID,OnlineInvoice
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceidonlineinvoice-get-openapi.md
- name: Clarity Accounting X-related-model Invoices Invoice Onlineinvoice
  x-api-slug: clarity-accounting
  description: X-related-model invoices invoice onlineinvoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Invoices/{InvoiceID}/OnlineInvoice
  tags: Invoices,InvoiceID,OnlineInvoice
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/invoicesinvoiceidonlineinvoice-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Items
  x-api-slug: clarity-accounting
  description: Get items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items
  tags: Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/items-get-openapi.md
- name: Clarity Accounting Post Items
  x-api-slug: clarity-accounting
  description: Post items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items
  tags: Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/items-post-openapi.md
- name: Clarity Accounting Put Items
  x-api-slug: clarity-accounting
  description: Put items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items
  tags: Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/items-put-openapi.md
- name: Clarity Accounting X-related-model Items
  x-api-slug: clarity-accounting
  description: X-related-model items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items
  tags: Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/items-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Items
  x-api-slug: clarity-accounting
  description: Delete items item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items/{ItemID}
  tags: Items,ItemID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/itemsitemid-delete-openapi.md
- name: Clarity Accounting Get Items
  x-api-slug: clarity-accounting
  description: Get items item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items/{ItemID}
  tags: Items,ItemID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/itemsitemid-get-openapi.md
- name: Clarity Accounting Post Items
  x-api-slug: clarity-accounting
  description: Post items item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items/{ItemID}
  tags: Items,ItemID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/itemsitemid-post-openapi.md
- name: Clarity Accounting X-related-model Items
  x-api-slug: clarity-accounting
  description: X-related-model items item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Items/{ItemID}
  tags: Items,ItemID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/itemsitemid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Journals
  x-api-slug: clarity-accounting
  description: Get journals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Journals
  tags: Journals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/journals-get-openapi.md
- name: Clarity Accounting X-related-model Journals
  x-api-slug: clarity-accounting
  description: X-related-model journals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Journals
  tags: Journals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/journals-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Journals Journal
  x-api-slug: clarity-accounting
  description: Get journals journal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Journals/{JournalID}
  tags: Journals,JournalID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/journalsjournalid-get-openapi.md
- name: Clarity Accounting X-related-model Journals Journal
  x-api-slug: clarity-accounting
  description: X-related-model journals journal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Journals/{JournalID}
  tags: Journals,JournalID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/journalsjournalid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Linkedtransactions
  x-api-slug: clarity-accounting
  description: Get linkedtransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions
  tags: LinkedTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactions-get-openapi.md
- name: Clarity Accounting Post Linkedtransactions
  x-api-slug: clarity-accounting
  description: Post linkedtransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions
  tags: LinkedTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactions-post-openapi.md
- name: Clarity Accounting Put Linkedtransactions
  x-api-slug: clarity-accounting
  description: Put linkedtransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions
  tags: LinkedTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactions-put-openapi.md
- name: Clarity Accounting X-related-model Linkedtransactions
  x-api-slug: clarity-accounting
  description: X-related-model linkedtransactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions
  tags: LinkedTransactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactions-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Linkedtransactions Linkedtransaction
  x-api-slug: clarity-accounting
  description: Delete linkedtransactions linkedtransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions/{LinkedTransactionID}
  tags: LinkedTransactions,LinkedTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactionslinkedtransactionid-delete-openapi.md
- name: Clarity Accounting Get Linkedtransactions Linkedtransaction
  x-api-slug: clarity-accounting
  description: Get linkedtransactions linkedtransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions/{LinkedTransactionID}
  tags: LinkedTransactions,LinkedTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactionslinkedtransactionid-get-openapi.md
- name: Clarity Accounting Post Linkedtransactions Linkedtransaction
  x-api-slug: clarity-accounting
  description: Post linkedtransactions linkedtransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions/{LinkedTransactionID}
  tags: LinkedTransactions,LinkedTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactionslinkedtransactionid-post-openapi.md
- name: Clarity Accounting X-related-model Linkedtransactions Linkedtransaction
  x-api-slug: clarity-accounting
  description: X-related-model linkedtransactions linkedtransaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//LinkedTransactions/{LinkedTransactionID}
  tags: LinkedTransactions,LinkedTransactionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/linkedtransactionslinkedtransactionid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Manualjournals
  x-api-slug: clarity-accounting
  description: Get manualjournals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals
  tags: ManualJournals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournals-get-openapi.md
- name: Clarity Accounting Post Manualjournals
  x-api-slug: clarity-accounting
  description: Post manualjournals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals
  tags: ManualJournals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournals-post-openapi.md
- name: Clarity Accounting Put Manualjournals
  x-api-slug: clarity-accounting
  description: Put manualjournals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals
  tags: ManualJournals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournals-put-openapi.md
- name: Clarity Accounting X-related-model Manualjournals
  x-api-slug: clarity-accounting
  description: X-related-model manualjournals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals
  tags: ManualJournals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournals-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Manualjournals Manualjournal
  x-api-slug: clarity-accounting
  description: Get manualjournals manualjournal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}
  tags: ManualJournals,ManualJournalID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalid-get-openapi.md
- name: Clarity Accounting Post Manualjournals Manualjournal
  x-api-slug: clarity-accounting
  description: Post manualjournals manualjournal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}
  tags: ManualJournals,ManualJournalID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalid-post-openapi.md
- name: Clarity Accounting X-related-model Manualjournals Manualjournal
  x-api-slug: clarity-accounting
  description: X-related-model manualjournals manualjournal.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}
  tags: ManualJournals,ManualJournalID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Manualjournals Manualjournal Attachments
  x-api-slug: clarity-accounting
  description: Get manualjournals manualjournal attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}/Attachments
  tags: ManualJournals,ManualJournalID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalidattachments-get-openapi.md
- name: Clarity Accounting Get Manualjournals Manualjournal Attachments Filename
  x-api-slug: clarity-accounting
  description: Get manualjournals manualjournal attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}/Attachments/{FileName}
  tags: ManualJournals,ManualJournalID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Manualjournals Manualjournal Attachments Filename
  x-api-slug: clarity-accounting
  description: Post manualjournals manualjournal attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//ManualJournals/{ManualJournalID}/Attachments/{FileName}
  tags: ManualJournals,ManualJournalID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/manualjournalsmanualjournalidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Organisation
  x-api-slug: clarity-accounting
  description: Get organisation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Organisation
  tags: Organisation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisation-get-openapi.md
- name: Clarity Accounting X-related-model Organisation
  x-api-slug: clarity-accounting
  description: X-related-model organisation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Organisation
  tags: Organisation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisation-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Organisation Shortcode
  x-api-slug: clarity-accounting
  description: Get organisation shortcode.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Organisation/{ShortCode}
  tags: Organisation,ShortCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisationshortcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisationshortcode-get-openapi.md
- name: Clarity Accounting X-related-model Organisation Shortcode
  x-api-slug: clarity-accounting
  description: X-related-model organisation shortcode.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Organisation/{ShortCode}
  tags: Organisation,ShortCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisationshortcode-xrelatedmodel-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/organisationshortcode-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Overpayments
  x-api-slug: clarity-accounting
  description: Get overpayments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments
  tags: Overpayments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpayments-get-openapi.md
- name: Clarity Accounting X-related-model Overpayments
  x-api-slug: clarity-accounting
  description: X-related-model overpayments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments
  tags: Overpayments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpayments-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Overpayments Overpayment
  x-api-slug: clarity-accounting
  description: Get overpayments overpayment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments/{OverpaymentID}
  tags: Overpayments,OverpaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpaymentsoverpaymentid-get-openapi.md
- name: Clarity Accounting X-related-model Overpayments Overpayment
  x-api-slug: clarity-accounting
  description: X-related-model overpayments overpayment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments/{OverpaymentID}
  tags: Overpayments,OverpaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpaymentsoverpaymentid-xrelatedmodel-openapi.md
- name: Clarity Accounting Put Overpayments Overpayment Allocations
  x-api-slug: clarity-accounting
  description: Put overpayments overpayment allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments/{OverpaymentID}/Allocations
  tags: Overpayments,OverpaymentID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpaymentsoverpaymentidallocations-put-openapi.md
- name: Clarity Accounting X-related-model Overpayments Overpayment Allocations
  x-api-slug: clarity-accounting
  description: X-related-model overpayments overpayment allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Overpayments/{OverpaymentID}/Allocations
  tags: Overpayments,OverpaymentID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/overpaymentsoverpaymentidallocations-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Payments
  x-api-slug: clarity-accounting
  description: Get payments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments
  tags: Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/payments-get-openapi.md
- name: Clarity Accounting Post Payments
  x-api-slug: clarity-accounting
  description: Post payments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments
  tags: Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/payments-post-openapi.md
- name: Clarity Accounting Put Payments
  x-api-slug: clarity-accounting
  description: Put payments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments
  tags: Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/payments-put-openapi.md
- name: Clarity Accounting X-related-model Payments
  x-api-slug: clarity-accounting
  description: X-related-model payments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments
  tags: Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/payments-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Payments Payment
  x-api-slug: clarity-accounting
  description: Get payments payment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments/{PaymentID}
  tags: Payments,PaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/paymentspaymentid-get-openapi.md
- name: Clarity Accounting Post Payments Payment
  x-api-slug: clarity-accounting
  description: Post payments payment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments/{PaymentID}
  tags: Payments,PaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/paymentspaymentid-post-openapi.md
- name: Clarity Accounting X-related-model Payments Payment
  x-api-slug: clarity-accounting
  description: X-related-model payments payment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Payments/{PaymentID}
  tags: Payments,PaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/paymentspaymentid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Prepayments
  x-api-slug: clarity-accounting
  description: Get prepayments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments
  tags: Prepayments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepayments-get-openapi.md
- name: Clarity Accounting X-related-model Prepayments
  x-api-slug: clarity-accounting
  description: X-related-model prepayments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments
  tags: Prepayments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepayments-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Prepayments Prepayment
  x-api-slug: clarity-accounting
  description: Get prepayments prepayment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments/{PrepaymentID}
  tags: Prepayments,PrepaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepaymentsprepaymentid-get-openapi.md
- name: Clarity Accounting X-related-model Prepayments Prepayment
  x-api-slug: clarity-accounting
  description: X-related-model prepayments prepayment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments/{PrepaymentID}
  tags: Prepayments,PrepaymentID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepaymentsprepaymentid-xrelatedmodel-openapi.md
- name: Clarity Accounting Put Prepayments Prepayment Allocations
  x-api-slug: clarity-accounting
  description: Put prepayments prepayment allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments/{PrepaymentID}/Allocations
  tags: Prepayments,PrepaymentID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepaymentsprepaymentidallocations-put-openapi.md
- name: Clarity Accounting X-related-model Prepayments Prepayment Allocations
  x-api-slug: clarity-accounting
  description: X-related-model prepayments prepayment allocations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Prepayments/{PrepaymentID}/Allocations
  tags: Prepayments,PrepaymentID,Ocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/prepaymentsprepaymentidallocations-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Purchaseorders
  x-api-slug: clarity-accounting
  description: Get purchaseorders.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders
  tags: PurchaseOrders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorders-get-openapi.md
- name: Clarity Accounting Post Purchaseorders
  x-api-slug: clarity-accounting
  description: Post purchaseorders.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders
  tags: PurchaseOrders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorders-post-openapi.md
- name: Clarity Accounting Put Purchaseorders
  x-api-slug: clarity-accounting
  description: Put purchaseorders.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders
  tags: PurchaseOrders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorders-put-openapi.md
- name: Clarity Accounting X-related-model Purchaseorders
  x-api-slug: clarity-accounting
  description: X-related-model purchaseorders.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders
  tags: PurchaseOrders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorders-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Purchaseorders Purchaseorder
  x-api-slug: clarity-accounting
  description: Get purchaseorders purchaseorder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}
  tags: PurchaseOrders,PurchaseOrderID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderid-get-openapi.md
- name: Clarity Accounting Post Purchaseorders Purchaseorder
  x-api-slug: clarity-accounting
  description: Post purchaseorders purchaseorder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}
  tags: PurchaseOrders,PurchaseOrderID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderid-post-openapi.md
- name: Clarity Accounting X-related-model Purchaseorders Purchaseorder
  x-api-slug: clarity-accounting
  description: X-related-model purchaseorders purchaseorder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}
  tags: PurchaseOrders,PurchaseOrderID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Purchaseorders Purchaseorder Attachments
  x-api-slug: clarity-accounting
  description: Get purchaseorders purchaseorder attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}/Attachments
  tags: PurchaseOrders,PurchaseOrderID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderidattachments-get-openapi.md
- name: Clarity Accounting Get Purchaseorders Purchaseorder Attachments Filename
  x-api-slug: clarity-accounting
  description: Get purchaseorders purchaseorder attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName}
  tags: PurchaseOrders,PurchaseOrderID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Purchaseorders Purchaseorder Attachments Filename
  x-api-slug: clarity-accounting
  description: Post purchaseorders purchaseorder attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName}
  tags: PurchaseOrders,PurchaseOrderID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/purchaseorderspurchaseorderidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Receipts
  x-api-slug: clarity-accounting
  description: Get receipts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts
  tags: Receipts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receipts-get-openapi.md
- name: Clarity Accounting Post Receipts
  x-api-slug: clarity-accounting
  description: Post receipts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts
  tags: Receipts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receipts-post-openapi.md
- name: Clarity Accounting Put Receipts
  x-api-slug: clarity-accounting
  description: Put receipts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts
  tags: Receipts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receipts-put-openapi.md
- name: Clarity Accounting X-related-model Receipts
  x-api-slug: clarity-accounting
  description: X-related-model receipts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts
  tags: Receipts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receipts-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Receipts Receipt
  x-api-slug: clarity-accounting
  description: Get receipts receipt.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}
  tags: Receipts,ReceiptID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptid-get-openapi.md
- name: Clarity Accounting Post Receipts Receipt
  x-api-slug: clarity-accounting
  description: Post receipts receipt.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}
  tags: Receipts,ReceiptID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptid-post-openapi.md
- name: Clarity Accounting X-related-model Receipts Receipt
  x-api-slug: clarity-accounting
  description: X-related-model receipts receipt.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}
  tags: Receipts,ReceiptID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Receipts Receipt Attachments
  x-api-slug: clarity-accounting
  description: Get receipts receipt attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}/Attachments
  tags: Receipts,ReceiptID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptidattachments-get-openapi.md
- name: Clarity Accounting Get Receipts Receipt Attachments Filename
  x-api-slug: clarity-accounting
  description: Get receipts receipt attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}/Attachments/{FileName}
  tags: Receipts,ReceiptID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Receipts Receipt Attachments Filename
  x-api-slug: clarity-accounting
  description: Post receipts receipt attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Receipts/{ReceiptID}/Attachments/{FileName}
  tags: Receipts,ReceiptID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/receiptsreceiptidattachmentsfilename-post-openapi.md
- name: Clarity Accounting Get Repeatinginvoices
  x-api-slug: clarity-accounting
  description: Get repeatinginvoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices
  tags: RepeatingInvoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoices-get-openapi.md
- name: Clarity Accounting X-related-model Repeatinginvoices
  x-api-slug: clarity-accounting
  description: X-related-model repeatinginvoices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices
  tags: RepeatingInvoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoices-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Repeatinginvoices Repeatinginvoice
  x-api-slug: clarity-accounting
  description: Get repeatinginvoices repeatinginvoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices/{RepeatingInvoiceID}
  tags: RepeatingInvoices,RepeatingInvoiceID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoicesrepeatinginvoiceid-get-openapi.md
- name: Clarity Accounting X-related-model Repeatinginvoices Repeatinginvoice
  x-api-slug: clarity-accounting
  description: X-related-model repeatinginvoices repeatinginvoice.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices/{RepeatingInvoiceID}
  tags: RepeatingInvoices,RepeatingInvoiceID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoicesrepeatinginvoiceid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Repeatinginvoices Repeatinginvoice Attachments
  x-api-slug: clarity-accounting
  description: Get repeatinginvoices repeatinginvoice attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices/{RepeatingInvoiceID}/Attachments
  tags: RepeatingInvoices,RepeatingInvoiceID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoicesrepeatinginvoiceidattachments-get-openapi.md
- name: Clarity Accounting Get Repeatinginvoices Repeatinginvoice Attachments Filename
  x-api-slug: clarity-accounting
  description: Get repeatinginvoices repeatinginvoice attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName}
  tags: RepeatingInvoices,RepeatingInvoiceID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/repeatinginvoicesrepeatinginvoiceidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Get Reports
  x-api-slug: clarity-accounting
  description: Get reports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports
  tags: Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reports-get-openapi.md
- name: Clarity Accounting X-related-model Reports
  x-api-slug: clarity-accounting
  description: X-related-model reports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports
  tags: Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reports-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Agedpayablesbycontact
  x-api-slug: clarity-accounting
  description: Get reports agedpayablesbycontact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/AgedPayablesByContact
  tags: Reports,AgedPayablesByContact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsagedpayablesbycontact-get-openapi.md
- name: Clarity Accounting X-related-model Reports Agedpayablesbycontact
  x-api-slug: clarity-accounting
  description: X-related-model reports agedpayablesbycontact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/AgedPayablesByContact
  tags: Reports,AgedPayablesByContact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsagedpayablesbycontact-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Agedreceivablesbycontact
  x-api-slug: clarity-accounting
  description: Get reports agedreceivablesbycontact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/AgedReceivablesByContact
  tags: Reports,AgedReceivablesByContact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsagedreceivablesbycontact-get-openapi.md
- name: Clarity Accounting X-related-model Reports Agedreceivablesbycontact
  x-api-slug: clarity-accounting
  description: X-related-model reports agedreceivablesbycontact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/AgedReceivablesByContact
  tags: Reports,AgedReceivablesByContact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsagedreceivablesbycontact-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Balancesheet
  x-api-slug: clarity-accounting
  description: Get reports balancesheet.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BalanceSheet
  tags: Reports,BalanceSheet
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbalancesheet-get-openapi.md
- name: Clarity Accounting X-related-model Reports Balancesheet
  x-api-slug: clarity-accounting
  description: X-related-model reports balancesheet.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BalanceSheet
  tags: Reports,BalanceSheet
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbalancesheet-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Bankstatement
  x-api-slug: clarity-accounting
  description: Get reports bankstatement.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BankStatement
  tags: Reports,BankStatement
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbankstatement-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbankstatement-get-openapi.md
- name: Clarity Accounting X-related-model Reports Bankstatement
  x-api-slug: clarity-accounting
  description: X-related-model reports bankstatement.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BankStatement
  tags: Reports,BankStatement
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbankstatement-xrelatedmodel-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbankstatement-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Banksummary
  x-api-slug: clarity-accounting
  description: Get reports banksummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BankSummary
  tags: Reports,BankSummary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbanksummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbanksummary-get-openapi.md
- name: Clarity Accounting X-related-model Reports Banksummary
  x-api-slug: clarity-accounting
  description: X-related-model reports banksummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BankSummary
  tags: Reports,BankSummary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbanksummary-xrelatedmodel-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbanksummary-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Budgetsummary
  x-api-slug: clarity-accounting
  description: Get reports budgetsummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BudgetSummary
  tags: Reports,BudgetSummary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbudgetsummary-get-openapi.md
- name: Clarity Accounting X-related-model Reports Budgetsummary
  x-api-slug: clarity-accounting
  description: X-related-model reports budgetsummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/BudgetSummary
  tags: Reports,BudgetSummary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsbudgetsummary-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Executivesummary
  x-api-slug: clarity-accounting
  description: Get reports executivesummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/ExecutiveSummary
  tags: Reports,ExecutiveSummary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsexecutivesummary-get-openapi.md
- name: Clarity Accounting X-related-model Reports Executivesummary
  x-api-slug: clarity-accounting
  description: X-related-model reports executivesummary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/ExecutiveSummary
  tags: Reports,ExecutiveSummary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsexecutivesummary-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Profitandloss
  x-api-slug: clarity-accounting
  description: Get reports profitandloss.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/ProfitAndLoss
  tags: Reports,ProfitAndLoss
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsprofitandloss-get-openapi.md
- name: Clarity Accounting X-related-model Reports Profitandloss
  x-api-slug: clarity-accounting
  description: X-related-model reports profitandloss.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/ProfitAndLoss
  tags: Reports,ProfitAndLoss
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsprofitandloss-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Tenninetynine
  x-api-slug: clarity-accounting
  description: Get reports tenninetynine.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/TenNinetyNine
  tags: Reports,TenNinetyNine
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportstenninetynine-get-openapi.md
- name: Clarity Accounting X-related-model Reports Tenninetynine
  x-api-slug: clarity-accounting
  description: X-related-model reports tenninetynine.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/TenNinetyNine
  tags: Reports,TenNinetyNine
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportstenninetynine-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Trialbalance
  x-api-slug: clarity-accounting
  description: Get reports trialbalance.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/TrialBalance
  tags: Reports,TrialBalance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportstrialbalance-get-openapi.md
- name: Clarity Accounting X-related-model Reports Trialbalance
  x-api-slug: clarity-accounting
  description: X-related-model reports trialbalance.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/TrialBalance
  tags: Reports,TrialBalance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportstrialbalance-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Reports Report
  x-api-slug: clarity-accounting
  description: Get reports report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/{ReportID}
  tags: Reports,ReportID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsreportid-get-openapi.md
- name: Clarity Accounting X-related-model Reports Report
  x-api-slug: clarity-accounting
  description: X-related-model reports report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Reports/{ReportID}
  tags: Reports,ReportID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/reportsreportid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Taxrates
  x-api-slug: clarity-accounting
  description: Get taxrates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TaxRates
  tags: TaxRates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/taxrates-get-openapi.md
- name: Clarity Accounting Post Taxrates
  x-api-slug: clarity-accounting
  description: Post taxrates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TaxRates
  tags: TaxRates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/taxrates-post-openapi.md
- name: Clarity Accounting Put Taxrates
  x-api-slug: clarity-accounting
  description: Put taxrates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TaxRates
  tags: TaxRates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/taxrates-put-openapi.md
- name: Clarity Accounting X-related-model Taxrates
  x-api-slug: clarity-accounting
  description: X-related-model taxrates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TaxRates
  tags: TaxRates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/taxrates-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Tracking Categories
  x-api-slug: clarity-accounting
  description: Get trackingcategories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories
  tags: TrackingCategories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategories-get-openapi.md
- name: Clarity Accounting Post Tracking Categories
  x-api-slug: clarity-accounting
  description: Post trackingcategories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories
  tags: TrackingCategories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategories-post-openapi.md
- name: Clarity Accounting Put Tracking Categories
  x-api-slug: clarity-accounting
  description: Put trackingcategories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories
  tags: TrackingCategories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategories-put-openapi.md
- name: Clarity Accounting X-related-model Tracking Categories
  x-api-slug: clarity-accounting
  description: X-related-model trackingcategories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories
  tags: TrackingCategories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategories-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Tracking Categories Trackingcategory
  x-api-slug: clarity-accounting
  description: Delete trackingcategories trackingcategory.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}
  tags: TrackingCategories,TrackingCategoryID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryid-delete-openapi.md
- name: Clarity Accounting Get Tracking Categories Trackingcategory
  x-api-slug: clarity-accounting
  description: Get trackingcategories trackingcategory.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}
  tags: TrackingCategories,TrackingCategoryID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryid-get-openapi.md
- name: Clarity Accounting Post Tracking Categories Trackingcategory
  x-api-slug: clarity-accounting
  description: Post trackingcategories trackingcategory.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}
  tags: TrackingCategories,TrackingCategoryID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryid-post-openapi.md
- name: Clarity Accounting X-related-model Tracking Categories Trackingcategory
  x-api-slug: clarity-accounting
  description: X-related-model trackingcategories trackingcategory.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}
  tags: TrackingCategories,TrackingCategoryID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryid-xrelatedmodel-openapi.md
- name: Clarity Accounting Put Tracking Categories Trackingcategory Options
  x-api-slug: clarity-accounting
  description: Put trackingcategories trackingcategory options.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}/Options
  tags: TrackingCategories,TrackingCategoryID,Options
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryidoptions-put-openapi.md
- name: Clarity Accounting X-related-model Tracking Categories Trackingcategory Options
  x-api-slug: clarity-accounting
  description: X-related-model trackingcategories trackingcategory options.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}/Options
  tags: TrackingCategories,TrackingCategoryID,Options
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryidoptions-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Tracking Categories Trackingcategory Options Trackingoption
  x-api-slug: clarity-accounting
  description: Delete trackingcategories trackingcategory options trackingoption.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID}
  tags: TrackingCategories,TrackingCategoryID,Options,TrackingOptionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryidoptionstrackingoptionid-delete-openapi.md
- name: Clarity Accounting X-related-model Tracking Categories Trackingcategory Options
    Trackingoption
  x-api-slug: clarity-accounting
  description: X-related-model trackingcategories trackingcategory options trackingoption.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID}
  tags: TrackingCategories,TrackingCategoryID,Options,TrackingOptionID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/trackingcategoriestrackingcategoryidoptionstrackingoptionid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Users
  x-api-slug: clarity-accounting
  description: Get users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/users-get-openapi.md
- name: Clarity Accounting X-related-model Users
  x-api-slug: clarity-accounting
  description: X-related-model users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/users-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Users User
  x-api-slug: clarity-accounting
  description: Get users user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Users/{UserID}
  tags: Users,UserID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/usersuserid-get-openapi.md
- name: Clarity Accounting X-related-model Users User
  x-api-slug: clarity-accounting
  description: X-related-model users user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Users/{UserID}
  tags: Users,UserID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/usersuserid-xrelatedmodel-openapi.md
- name: Clarity Accounting
  x-api-slug: clarity-accounting
  description: Xero is the QuickBooks alternative. Use Xero accounting software to
    manage invoicing, bank reconciliation, bookkeeping & more. Start a free trial
    today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0
  tags: Xero
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/xero/master/_listings/xero/openapi.md
x-common:
- type: x-base
  url: https://api.xero.com
- type: x-blog
  url: http://blog.xero.com
- type: x-blog
  url: https://devblog.xero.com/
- type: x-blog-rss
  url: https://devblog.xero.com/feed
- type: x-blog-rss
  url: http://feeds.feedburner.com/xerolive
- type: x-crunchbase
  url: http://www.crunchbase.com/company/xero
- type: x-crunchbase
  url: https://crunchbase.com/organization/xero
- type: x-developer
  url: http://developer.xero.com/
- type: x-email
  url: support@xero.com
- type: x-email
  url: sales@xero.com
- type: x-email
  url: careers@xero.com
- type: x-email
  url: privacy@xero.com
- type: x-email
  url: phishing@xero.com
- type: x-email
  url: press@xero.com
- type: x-email
  url: AUpress@xero.com
- type: x-email
  url: UKpress@xero.com
- type: x-email
  url: USpress@xero.com
- type: x-github
  url: https://github.com/XeroAPI
- type: x-partners
  url: http://developer.xero.com/partner/
- type: x-pricing
  url: https://www.xero.com/us/pricing/
- type: x-twitter
  url: https://twitter.com/xero
- type: x-website
  url: http://www.xero.com/
- type: x-website
  url: http://xero.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---