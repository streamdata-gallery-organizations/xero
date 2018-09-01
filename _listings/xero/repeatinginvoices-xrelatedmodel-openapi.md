---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting X-related-model Repeatinginvoices
  description: X-related-model repeatinginvoices.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts:
    get:
      summary: Get Accounts
      description: Retrieve the chart of accounts
      operationId: getAccounts
      x-api-path-slug: accounts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Accounts
    post:
      summary: Post Accounts
      description: Post accounts.
      operationId: postAccounts
      x-api-path-slug: accounts-post
      parameters:
      - in: body
        name: Accounts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounts
    put:
      summary: Put Accounts
      description: Put accounts.
      operationId: putAccounts
      x-api-path-slug: accounts-put
      parameters:
      - in: body
        name: Accounts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounts
    x-related-model:
      summary: X-related-model Accounts
      description: X-related-model accounts.
      operationId: x-related-modelAccounts
      x-api-path-slug: accounts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /Accounts/{AccountID}:
    delete:
      summary: Delete Accounts
      description: Delete accounts account.
      operationId: deleteAccountsAccount
      x-api-path-slug: accountsaccountid-delete
      parameters:
      - in: path
        name: AccountID
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
    get:
      summary: Get Accounts
      description: Get accounts account.
      operationId: getAccountsAccount
      x-api-path-slug: accountsaccountid-get
      parameters:
      - in: path
        name: AccountID
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
    post:
      summary: Post Accounts
      description: Post accounts account.
      operationId: postAccountsAccount
      x-api-path-slug: accountsaccountid-post
      parameters:
      - in: path
        name: AccountID
      - in: body
        name: Accounts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
    x-related-model:
      summary: X-related-model Accounts
      description: X-related-model accounts account.
      operationId: x-related-modelAccountsAccount
      x-api-path-slug: accountsaccountid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
  /Accounts/{AccountID}/Attachments:
    get:
      summary: Get Accounts Attachments
      description: Get accounts account attachments.
      operationId: getAccountsAccountAttachments
      x-api-path-slug: accountsaccountidattachments-get
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
  /Accounts/{AccountID}/Attachments/{FileName}:
    get:
      summary: Get Accounts Attachments Filename
      description: Get accounts account attachments filename.
      operationId: getAccountsAccountAttachmentsFilename
      x-api-path-slug: accountsaccountidattachmentsfilename-get
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
      - FileName
    post:
      summary: Post Accounts Attachments Filename
      description: Post accounts account attachments filename.
      operationId: postAccountsAccountAttachmentsFilename
      x-api-path-slug: accountsaccountidattachmentsfilename-post
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
      - FileName
  /BankTransactions:
    get:
      summary: Get Bank Transactions
      description: Get banktransactions.
      operationId: getBanktransactions
      x-api-path-slug: banktransactions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    post:
      summary: Post Bank Transactions
      description: Post banktransactions.
      operationId: postBanktransactions
      x-api-path-slug: banktransactions-post
      parameters:
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    put:
      summary: Put Bank Transactions
      description: Put banktransactions.
      operationId: putBanktransactions
      x-api-path-slug: banktransactions-put
      parameters:
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    x-related-model:
      summary: X-related-model Bank Transactions
      description: X-related-model banktransactions.
      operationId: x-related-modelBanktransactions
      x-api-path-slug: banktransactions-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
  /BankTransactions/{BankTransactionID}:
    get:
      summary: Get Bank Transactions Banktransaction
      description: Get banktransactions banktransaction.
      operationId: getBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-get
      parameters:
      - in: path
        name: BankTransactionID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
    post:
      summary: Post Bank Transactions Banktransaction
      description: Post banktransactions banktransaction.
      operationId: postBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-post
      parameters:
      - in: path
        name: BankTransactionID
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
    x-related-model:
      summary: X-related-model Bank Transactions Banktransaction
      description: X-related-model banktransactions banktransaction.
      operationId: x-related-modelBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
  /BankTransactions/{BankTransactionID}/Attachments:
    get:
      summary: Get Bank Transactions Banktransaction Attachments
      description: Get banktransactions banktransaction attachments.
      operationId: getBanktransactionsBanktransactionAttachments
      x-api-path-slug: banktransactionsbanktransactionidattachments-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
  /BankTransactions/{BankTransactionID}/Attachments/{FileName}:
    get:
      summary: Get Bank Transactions Banktransaction Attachments Filename
      description: Get banktransactions banktransaction attachments filename.
      operationId: getBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
    post:
      summary: Post Bank Transactions Banktransaction Attachments Filename
      description: Post banktransactions banktransaction attachments filename.
      operationId: postBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
  /BankTransfers:
    get:
      summary: Get Banks Transfers
      description: Get banktransfers.
      operationId: getBanktransfers
      x-api-path-slug: banktransfers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
    put:
      summary: Put Banks Transfers
      description: Put banktransfers.
      operationId: putBanktransfers
      x-api-path-slug: banktransfers-put
      parameters:
      - in: body
        name: BankTransfers
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
    x-related-model:
      summary: X-related-model Banks Transfers
      description: X-related-model banktransfers.
      operationId: x-related-modelBanktransfers
      x-api-path-slug: banktransfers-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
  /BankTransfers/{BankTransferID}:
    get:
      summary: Get Banks Transfers
      description: Get banktransfers banktransfer.
      operationId: getBanktransfersBanktransfer
      x-api-path-slug: banktransfersbanktransferid-get
      parameters:
      - in: path
        name: BankTransferID
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
    x-related-model:
      summary: X-related-model Banks Transfers
      description: X-related-model banktransfers banktransfer.
      operationId: x-related-modelBanktransfersBanktransfer
      x-api-path-slug: banktransfersbanktransferid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
  /BankTransfers/{BankTransferID}/Attachments/{FileName}:
    get:
      summary: Get Banks Transfers Attachments Filename
      description: Get banktransfers banktransfer attachments filename.
      operationId: getBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for an BankTransfer
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
    post:
      summary: Post Banks Transfers Attachments Filename
      description: Post banktransfers banktransfer attachments filename.
      operationId: postBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for a BankTransfer
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
  /BrandingThemes:
    get:
      summary: Get Brandingthemes
      description: Get brandingthemes.
      operationId: getBrandingthemes
      x-api-path-slug: brandingthemes-get
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
    x-related-model:
      summary: X-related-model Brandingthemes
      description: X-related-model brandingthemes.
      operationId: x-related-modelBrandingthemes
      x-api-path-slug: brandingthemes-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
  /BrandingThemes/{BrandingThemeID}:
    get:
      summary: Get Brandingthemes Brandingtheme
      description: Get brandingthemes brandingtheme.
      operationId: getBrandingthemesBrandingtheme
      x-api-path-slug: brandingthemesbrandingthemeid-get
      parameters:
      - in: path
        name: BrandingThemeID
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
      - BrandingThemeID
    x-related-model:
      summary: X-related-model Brandingthemes Brandingtheme
      description: X-related-model brandingthemes brandingtheme.
      operationId: x-related-modelBrandingthemesBrandingtheme
      x-api-path-slug: brandingthemesbrandingthemeid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
      - BrandingThemeID
  /ContactGroups:
    get:
      summary: Get Contactgroups
      description: Get contactgroups.
      operationId: getContactgroups
      x-api-path-slug: contactgroups-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
    post:
      summary: Post Contactgroups
      description: Post contactgroups.
      operationId: postContactgroups
      x-api-path-slug: contactgroups-post
      parameters:
      - in: body
        name: ContactGroups
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
    put:
      summary: Put Contactgroups
      description: Put contactgroups.
      operationId: putContactgroups
      x-api-path-slug: contactgroups-put
      parameters:
      - in: body
        name: ContactGroups
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
    x-related-model:
      summary: X-related-model Contactgroups
      description: X-related-model contactgroups.
      operationId: x-related-modelContactgroups
      x-api-path-slug: contactgroups-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
  /ContactGroups/{ContactGroupID}:
    delete:
      summary: Delete Contact Groups
      description: Delete contactgroups contactgroup.
      operationId: deleteContactgroupsContactgroup
      x-api-path-slug: contactgroupscontactgroupid-delete
      parameters:
      - in: path
        name: ContactGroupID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
    get:
      summary: Get Contact Groups
      description: Get contactgroups contactgroup.
      operationId: getContactgroupsContactgroup
      x-api-path-slug: contactgroupscontactgroupid-get
      parameters:
      - in: path
        name: ContactGroupID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
    post:
      summary: Post Contact Groups
      description: Post contactgroups contactgroup.
      operationId: postContactgroupsContactgroup
      x-api-path-slug: contactgroupscontactgroupid-post
      parameters:
      - in: path
        name: ContactGroupID
      - in: body
        name: ContactGroups
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
    x-related-model:
      summary: X-related-model Contact Groups
      description: X-related-model contactgroups contactgroup.
      operationId: x-related-modelContactgroupsContactgroup
      x-api-path-slug: contactgroupscontactgroupid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
  /ContactGroups/{ContactGroupID}/Contacts:
    delete:
      summary: Delete Contact Groups Contacts
      description: Delete contactgroups contactgroup contacts.
      operationId: deleteContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-delete
      parameters:
      - in: path
        name: ContactGroupID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
    put:
      summary: Put Contact Groups Contacts
      description: Put contactgroups contactgroup contacts.
      operationId: putContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-put
      parameters:
      - in: path
        name: ContactGroupID
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
    x-related-model:
      summary: X-related-model Contact Groups Contacts
      description: X-related-model contactgroups contactgroup contacts.
      operationId: x-related-modelContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
  /ContactGroups/{ContactGroupID}/Contacts/{ContactID}:
    delete:
      summary: Delete Contact Groups Contacts Contact
      description: Delete contactgroups contactgroup contacts contact.
      operationId: deleteContactgroupsContactgroupContactsContact
      x-api-path-slug: contactgroupscontactgroupidcontactscontactid-delete
      parameters:
      - in: path
        name: ContactGroupID
      - in: path
        name: ContactID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
      - ContactID
    x-related-model:
      summary: X-related-model Contact Groups Contacts Contact
      description: X-related-model contactgroups contactgroup contacts contact.
      operationId: x-related-modelContactgroupsContactgroupContactsContact
      x-api-path-slug: contactgroupscontactgroupidcontactscontactid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
      - ContactID
  /Contacts:
    get:
      summary: Get Contacts
      description: Get contacts.
      operationId: getContacts
      x-api-path-slug: contacts-get
      parameters:
      - in: query
        name: IDs
        description: Filter by a comma-separated list of ContactIDs
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
    post:
      summary: Post Contacts
      description: Post contacts.
      operationId: postContacts
      x-api-path-slug: contacts-post
      parameters:
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
    put:
      summary: Put Contacts
      description: Put contacts.
      operationId: putContacts
      x-api-path-slug: contacts-put
      parameters:
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
    x-related-model:
      summary: X-related-model Contacts
      description: X-related-model contacts.
      operationId: x-related-modelContacts
      x-api-path-slug: contacts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Contacts
  /Contacts/{ContactID}:
    get:
      summary: Get Contacts Contact
      description: Get contacts contact.
      operationId: getContactsContact
      x-api-path-slug: contactscontactid-get
      parameters:
      - in: path
        name: ContactID
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
    post:
      summary: Post Contacts Contact
      description: Post contacts contact.
      operationId: postContactsContact
      x-api-path-slug: contactscontactid-post
      parameters:
      - in: path
        name: ContactID
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
    x-related-model:
      summary: X-related-model Contacts Contact
      description: X-related-model contacts contact.
      operationId: x-related-modelContactsContact
      x-api-path-slug: contactscontactid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
  /Contacts/{ContactID}/Attachments:
    get:
      summary: Get Contacts Contact Attachments
      description: Get contacts contact attachments.
      operationId: getContactsContactAttachments
      x-api-path-slug: contactscontactidattachments-get
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
  /Contacts/{ContactID}/Attachments/{FileName}:
    get:
      summary: Get Contacts Contact Attachments Filename
      description: Get contacts contact attachments filename.
      operationId: getContactsContactAttachmentsFilename
      x-api-path-slug: contactscontactidattachmentsfilename-get
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
      - FileName
    post:
      summary: Post Contacts Contact Attachments Filename
      description: Post contacts contact attachments filename.
      operationId: postContactsContactAttachmentsFilename
      x-api-path-slug: contactscontactidattachmentsfilename-post
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
      - FileName
  /CreditNotes:
    get:
      summary: Get Creditnotes
      description: Get creditnotes.
      operationId: getCreditnotes
      x-api-path-slug: creditnotes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    post:
      summary: Post Creditnotes
      description: Post creditnotes.
      operationId: postCreditnotes
      x-api-path-slug: creditnotes-post
      parameters:
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    put:
      summary: Put Creditnotes
      description: Put creditnotes.
      operationId: putCreditnotes
      x-api-path-slug: creditnotes-put
      parameters:
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    x-related-model:
      summary: X-related-model Creditnotes
      description: X-related-model creditnotes.
      operationId: x-related-modelCreditnotes
      x-api-path-slug: creditnotes-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
  /CreditNotes/{CreditNoteID}:
    get:
      summary: Get Creditnotes Creditnote
      description: Get creditnotes creditnote.
      operationId: getCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-get
      parameters:
      - in: path
        name: CreditNoteID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
    post:
      summary: Post Creditnotes Creditnote
      description: Post creditnotes creditnote.
      operationId: postCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-post
      parameters:
      - in: path
        name: CreditNoteID
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
    x-related-model:
      summary: X-related-model Creditnotes Creditnote
      description: X-related-model creditnotes creditnote.
      operationId: x-related-modelCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
  /CreditNotes/{CreditNoteID}/Allocations:
    put:
      summary: Put Creditnotes Creditnote Allocations
      description: Put creditnotes creditnote allocations.
      operationId: putCreditnotesCreditnoteAllocations
      x-api-path-slug: creditnotescreditnoteidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: CreditNoteID
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Ocations
    x-related-model:
      summary: X-related-model Creditnotes Creditnote Allocations
      description: X-related-model creditnotes creditnote allocations.
      operationId: x-related-modelCreditnotesCreditnoteAllocations
      x-api-path-slug: creditnotescreditnoteidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Ocations
  /CreditNotes/{CreditNoteID}/Attachments:
    get:
      summary: Get Creditnotes Creditnote Attachments
      description: Get creditnotes creditnote attachments.
      operationId: getCreditnotesCreditnoteAttachments
      x-api-path-slug: creditnotescreditnoteidattachments-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
  /CreditNotes/{CreditNoteID}/Attachments/{FileName}:
    get:
      summary: Get Creditnotes Creditnote Attachments Filename
      description: Get creditnotes creditnote attachments filename.
      operationId: getCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
    post:
      summary: Post Creditnotes Creditnote Attachments Filename
      description: Post creditnotes creditnote attachments filename.
      operationId: postCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
  /Currencies:
    get:
      summary: Get Currencies
      description: Get currencies.
      operationId: getCurrencies
      x-api-path-slug: currencies-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
    put:
      summary: Put Currencies
      description: Put currencies.
      operationId: putCurrencies
      x-api-path-slug: currencies-put
      parameters:
      - in: body
        name: Currencies
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
    x-related-model:
      summary: X-related-model Currencies
      description: X-related-model currencies.
      operationId: x-related-modelCurrencies
      x-api-path-slug: currencies-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Currencies
  /Employees:
    get:
      summary: Get Employees
      description: Get employees.
      operationId: getEmployees
      x-api-path-slug: employees-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Employees
    post:
      summary: Post Employees
      description: Post employees.
      operationId: postEmployees
      x-api-path-slug: employees-post
      parameters:
      - in: body
        name: Employees
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Employees
    put:
      summary: Put Employees
      description: Put employees.
      operationId: putEmployees
      x-api-path-slug: employees-put
      parameters:
      - in: body
        name: Employees
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Employees
    x-related-model:
      summary: X-related-model Employees
      description: X-related-model employees.
      operationId: x-related-modelEmployees
      x-api-path-slug: employees-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Employees
  /Employees/{EmployeeID}:
    get:
      summary: Get Employees Employee
      description: Get employees employee.
      operationId: getEmployeesEmployee
      x-api-path-slug: employeesemployeeid-get
      parameters:
      - in: path
        name: EmployeeID
      responses:
        200:
          description: OK
      tags:
      - Employees
      - EmployeeID
    post:
      summary: Post Employees Employee
      description: Post employees employee.
      operationId: postEmployeesEmployee
      x-api-path-slug: employeesemployeeid-post
      parameters:
      - in: path
        name: EmployeeID
      - in: body
        name: Employees
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Employees
      - EmployeeID
    x-related-model:
      summary: X-related-model Employees Employee
      description: X-related-model employees employee.
      operationId: x-related-modelEmployeesEmployee
      x-api-path-slug: employeesemployeeid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Employees
      - EmployeeID
  /ExpenseClaims:
    get:
      summary: Get Expenseclaims
      description: Get expenseclaims.
      operationId: getExpenseclaims
      x-api-path-slug: expenseclaims-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
    post:
      summary: Post Expenseclaims
      description: Post expenseclaims.
      operationId: postExpenseclaims
      x-api-path-slug: expenseclaims-post
      parameters:
      - in: body
        name: ExpenseClaims
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
    put:
      summary: Put Expenseclaims
      description: Put expenseclaims.
      operationId: putExpenseclaims
      x-api-path-slug: expenseclaims-put
      parameters:
      - in: body
        name: ExpenseClaims
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
    x-related-model:
      summary: X-related-model Expenseclaims
      description: X-related-model expenseclaims.
      operationId: x-related-modelExpenseclaims
      x-api-path-slug: expenseclaims-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
  /ExpenseClaims/{ExpenseClaimID}:
    get:
      summary: Get Expenseclaims Expenseclaim
      description: Get expenseclaims expenseclaim.
      operationId: getExpenseclaimsExpenseclaim
      x-api-path-slug: expenseclaimsexpenseclaimid-get
      parameters:
      - in: path
        name: ExpenseClaimID
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
      - ExpenseClaimID
    post:
      summary: Post Expenseclaims Expenseclaim
      description: Post expenseclaims expenseclaim.
      operationId: postExpenseclaimsExpenseclaim
      x-api-path-slug: expenseclaimsexpenseclaimid-post
      parameters:
      - in: path
        name: ExpenseClaimID
      - in: body
        name: ExpenseClaims
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
      - ExpenseClaimID
    x-related-model:
      summary: X-related-model Expenseclaims Expenseclaim
      description: X-related-model expenseclaims expenseclaim.
      operationId: x-related-modelExpenseclaimsExpenseclaim
      x-api-path-slug: expenseclaimsexpenseclaimid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ExpenseClaims
      - ExpenseClaimID
  /Invoices:
    get:
      summary: Get Invoices
      description: Get invoices.
      operationId: getInvoices
      x-api-path-slug: invoices-get
      parameters:
      - in: query
        name: ContactIDs
        description: Filter by a comma-separated list of ContactIDs
      - in: query
        name: IDs
        description: Filter by a comma-separated list of InvoiceIDs
      - in: query
        name: InvoiceNumbers
        description: Filter by a comma-separated list of InvoiceNumbers
      - in: query
        name: No Name
      - in: query
        name: Statuses
        description: Filter by a comma-separated list of Statuses
      responses:
        200:
          description: OK
      tags:
      - Invoices
    post:
      summary: Post Invoices
      description: Post invoices.
      operationId: postInvoices
      x-api-path-slug: invoices-post
      parameters:
      - in: body
        name: Invoices
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
    put:
      summary: Put Invoices
      description: Put invoices.
      operationId: putInvoices
      x-api-path-slug: invoices-put
      parameters:
      - in: body
        name: Invoices
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
    x-related-model:
      summary: X-related-model Invoices
      description: X-related-model invoices.
      operationId: x-related-modelInvoices
      x-api-path-slug: invoices-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Invoices
  /Invoices/{InvoiceID}:
    get:
      summary: Get Invoices Invoice
      description: Get invoices invoice.
      operationId: getInvoicesInvoice
      x-api-path-slug: invoicesinvoiceid-get
      parameters:
      - in: path
        name: InvoiceID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
    post:
      summary: Post Invoices Invoice
      description: Post invoices invoice.
      operationId: postInvoicesInvoice
      x-api-path-slug: invoicesinvoiceid-post
      parameters:
      - in: path
        name: InvoiceID
      - in: body
        name: Invoices
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
    x-related-model:
      summary: X-related-model Invoices Invoice
      description: X-related-model invoices invoice.
      operationId: x-related-modelInvoicesInvoice
      x-api-path-slug: invoicesinvoiceid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
  /Invoices/{InvoiceID}/Attachments:
    get:
      summary: Get Invoices Invoice Attachments
      description: Get invoices invoice attachments.
      operationId: getInvoicesInvoiceAttachments
      x-api-path-slug: invoicesinvoiceidattachments-get
      parameters:
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
  /Invoices/{InvoiceID}/Attachments/{FileName}:
    get:
      summary: Get Invoices Invoice Attachments Filename
      description: Get invoices invoice attachments filename.
      operationId: getInvoicesInvoiceAttachmentsFilename
      x-api-path-slug: invoicesinvoiceidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
      - FileName
    post:
      summary: Post Invoices Invoice Attachments Filename
      description: Post invoices invoice attachments filename.
      operationId: postInvoicesInvoiceAttachmentsFilename
      x-api-path-slug: invoicesinvoiceidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
      - FileName
  /Invoices/{InvoiceID}/OnlineInvoice:
    get:
      summary: Get Invoices Invoice Onlineinvoice
      description: Get invoices invoice onlineinvoice.
      operationId: getInvoicesInvoiceOnlineinvoice
      x-api-path-slug: invoicesinvoiceidonlineinvoice-get
      parameters:
      - in: path
        name: InvoiceID
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - OnlineInvoice
    x-related-model:
      summary: X-related-model Invoices Invoice Onlineinvoice
      description: X-related-model invoices invoice onlineinvoice.
      operationId: x-related-modelInvoicesInvoiceOnlineinvoice
      x-api-path-slug: invoicesinvoiceidonlineinvoice-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - OnlineInvoice
  /Items:
    get:
      summary: Get Items
      description: Get items.
      operationId: getItems
      x-api-path-slug: items-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Items
    post:
      summary: Post Items
      description: Post items.
      operationId: postItems
      x-api-path-slug: items-post
      parameters:
      - in: body
        name: Items
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Items
    put:
      summary: Put Items
      description: Put items.
      operationId: putItems
      x-api-path-slug: items-put
      parameters:
      - in: body
        name: Items
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Items
    x-related-model:
      summary: X-related-model Items
      description: X-related-model items.
      operationId: x-related-modelItems
      x-api-path-slug: items-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Items
  /Items/{ItemID}:
    delete:
      summary: Delete Items
      description: Delete items item.
      operationId: deleteItemsItem
      x-api-path-slug: itemsitemid-delete
      parameters:
      - in: path
        name: ItemID
      responses:
        200:
          description: OK
      tags:
      - Items
      - ItemID
    get:
      summary: Get Items
      description: Get items item.
      operationId: getItemsItem
      x-api-path-slug: itemsitemid-get
      parameters:
      - in: path
        name: ItemID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Items
      - ItemID
    post:
      summary: Post Items
      description: Post items item.
      operationId: postItemsItem
      x-api-path-slug: itemsitemid-post
      parameters:
      - in: path
        name: ItemID
      - in: body
        name: Items
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Items
      - ItemID
    x-related-model:
      summary: X-related-model Items
      description: X-related-model items item.
      operationId: x-related-modelItemsItem
      x-api-path-slug: itemsitemid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Items
      - ItemID
  /Journals:
    get:
      summary: Get Journals
      description: Get journals.
      operationId: getJournals
      x-api-path-slug: journals-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Journals
    x-related-model:
      summary: X-related-model Journals
      description: X-related-model journals.
      operationId: x-related-modelJournals
      x-api-path-slug: journals-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Journals
  /Journals/{JournalID}:
    get:
      summary: Get Journals Journal
      description: Get journals journal.
      operationId: getJournalsJournal
      x-api-path-slug: journalsjournalid-get
      parameters:
      - in: path
        name: JournalID
      responses:
        200:
          description: OK
      tags:
      - Journals
      - JournalID
    x-related-model:
      summary: X-related-model Journals Journal
      description: X-related-model journals journal.
      operationId: x-related-modelJournalsJournal
      x-api-path-slug: journalsjournalid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Journals
      - JournalID
  /LinkedTransactions:
    get:
      summary: Get Linkedtransactions
      description: Get linkedtransactions.
      operationId: getLinkedtransactions
      x-api-path-slug: linkedtransactions-get
      parameters:
      - in: query
        name: ContactID
        description: Filter by the ContactID
      - in: query
        name: No Name
      - in: query
        name: SourceTransactionID
        description: Filter by the SourceTransactionID
      - in: query
        name: Status
        description: Filter by the combination of ContactID and Status
      - in: query
        name: TargetTransactionID
        description: Filter by the TargetTransactionID
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
    post:
      summary: Post Linkedtransactions
      description: Post linkedtransactions.
      operationId: postLinkedtransactions
      x-api-path-slug: linkedtransactions-post
      parameters:
      - in: body
        name: LinkedTransactions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
    put:
      summary: Put Linkedtransactions
      description: Put linkedtransactions.
      operationId: putLinkedtransactions
      x-api-path-slug: linkedtransactions-put
      parameters:
      - in: body
        name: LinkedTransactions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
    x-related-model:
      summary: X-related-model Linkedtransactions
      description: X-related-model linkedtransactions.
      operationId: x-related-modelLinkedtransactions
      x-api-path-slug: linkedtransactions-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
  /LinkedTransactions/{LinkedTransactionID}:
    delete:
      summary: Delete Linkedtransactions Linkedtransaction
      description: Delete linkedtransactions linkedtransaction.
      operationId: deleteLinkedtransactionsLinkedtransaction
      x-api-path-slug: linkedtransactionslinkedtransactionid-delete
      parameters:
      - in: path
        name: LinkedTransactionID
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
      - LinkedTransactionID
    get:
      summary: Get Linkedtransactions Linkedtransaction
      description: Get linkedtransactions linkedtransaction.
      operationId: getLinkedtransactionsLinkedtransaction
      x-api-path-slug: linkedtransactionslinkedtransactionid-get
      parameters:
      - in: path
        name: LinkedTransactionID
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
      - LinkedTransactionID
    post:
      summary: Post Linkedtransactions Linkedtransaction
      description: Post linkedtransactions linkedtransaction.
      operationId: postLinkedtransactionsLinkedtransaction
      x-api-path-slug: linkedtransactionslinkedtransactionid-post
      parameters:
      - in: path
        name: LinkedTransactionID
      - in: body
        name: LinkedTransactions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
      - LinkedTransactionID
    x-related-model:
      summary: X-related-model Linkedtransactions Linkedtransaction
      description: X-related-model linkedtransactions linkedtransaction.
      operationId: x-related-modelLinkedtransactionsLinkedtransaction
      x-api-path-slug: linkedtransactionslinkedtransactionid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - LinkedTransactions
      - LinkedTransactionID
  /ManualJournals:
    get:
      summary: Get Manualjournals
      description: Get manualjournals.
      operationId: getManualjournals
      x-api-path-slug: manualjournals-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
    post:
      summary: Post Manualjournals
      description: Post manualjournals.
      operationId: postManualjournals
      x-api-path-slug: manualjournals-post
      parameters:
      - in: body
        name: ManualJournals
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
    put:
      summary: Put Manualjournals
      description: Put manualjournals.
      operationId: putManualjournals
      x-api-path-slug: manualjournals-put
      parameters:
      - in: body
        name: ManualJournals
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
    x-related-model:
      summary: X-related-model Manualjournals
      description: X-related-model manualjournals.
      operationId: x-related-modelManualjournals
      x-api-path-slug: manualjournals-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
  /ManualJournals/{ManualJournalID}:
    get:
      summary: Get Manualjournals Manualjournal
      description: Get manualjournals manualjournal.
      operationId: getManualjournalsManualjournal
      x-api-path-slug: manualjournalsmanualjournalid-get
      parameters:
      - in: path
        name: ManualJournalID
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
    post:
      summary: Post Manualjournals Manualjournal
      description: Post manualjournals manualjournal.
      operationId: postManualjournalsManualjournal
      x-api-path-slug: manualjournalsmanualjournalid-post
      parameters:
      - in: path
        name: ManualJournalID
      - in: body
        name: ManualJournals
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
    x-related-model:
      summary: X-related-model Manualjournals Manualjournal
      description: X-related-model manualjournals manualjournal.
      operationId: x-related-modelManualjournalsManualjournal
      x-api-path-slug: manualjournalsmanualjournalid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
  /ManualJournals/{ManualJournalID}/Attachments:
    get:
      summary: Get Manualjournals Manualjournal Attachments
      description: Get manualjournals manualjournal attachments.
      operationId: getManualjournalsManualjournalAttachments
      x-api-path-slug: manualjournalsmanualjournalidattachments-get
      parameters:
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
  /ManualJournals/{ManualJournalID}/Attachments/{FileName}:
    get:
      summary: Get Manualjournals Manualjournal Attachments Filename
      description: Get manualjournals manualjournal attachments filename.
      operationId: getManualjournalsManualjournalAttachmentsFilename
      x-api-path-slug: manualjournalsmanualjournalidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
      - FileName
    post:
      summary: Post Manualjournals Manualjournal Attachments Filename
      description: Post manualjournals manualjournal attachments filename.
      operationId: postManualjournalsManualjournalAttachmentsFilename
      x-api-path-slug: manualjournalsmanualjournalidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
      - FileName
  /Organisation:
    get:
      summary: Get Organisation
      description: Get organisation.
      operationId: getOrganisation
      x-api-path-slug: organisation-get
      responses:
        200:
          description: OK
      tags:
      - Organisation
    x-related-model:
      summary: X-related-model Organisation
      description: X-related-model organisation.
      operationId: x-related-modelOrganisation
      x-api-path-slug: organisation-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Organisation
  /Organisation/{ShortCode}:
    get:
      summary: Get Organisation Shortcode
      description: Get organisation shortcode.
      operationId: getOrganisationShortcode
      x-api-path-slug: organisationshortcode-get
      parameters:
      - in: path
        name: ShortCode
      responses:
        200:
          description: OK
      tags:
      - Organisation
      - ShortCode
    x-related-model:
      summary: X-related-model Organisation Shortcode
      description: X-related-model organisation shortcode.
      operationId: x-related-modelOrganisationShortcode
      x-api-path-slug: organisationshortcode-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Organisation
      - ShortCode
  /Overpayments:
    get:
      summary: Get Overpayments
      description: Get overpayments.
      operationId: getOverpayments
      x-api-path-slug: overpayments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Overpayments
    x-related-model:
      summary: X-related-model Overpayments
      description: X-related-model overpayments.
      operationId: x-related-modelOverpayments
      x-api-path-slug: overpayments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
  /Overpayments/{OverpaymentID}:
    get:
      summary: Get Overpayments Overpayment
      description: Get overpayments overpayment.
      operationId: getOverpaymentsOverpayment
      x-api-path-slug: overpaymentsoverpaymentid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: OverpaymentID
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
    x-related-model:
      summary: X-related-model Overpayments Overpayment
      description: X-related-model overpayments overpayment.
      operationId: x-related-modelOverpaymentsOverpayment
      x-api-path-slug: overpaymentsoverpaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
  /Overpayments/{OverpaymentID}/Allocations:
    put:
      summary: Put Overpayments Overpayment Allocations
      description: Put overpayments overpayment allocations.
      operationId: putOverpaymentsOverpaymentAllocations
      x-api-path-slug: overpaymentsoverpaymentidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: OverpaymentID
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
      - Ocations
    x-related-model:
      summary: X-related-model Overpayments Overpayment Allocations
      description: X-related-model overpayments overpayment allocations.
      operationId: x-related-modelOverpaymentsOverpaymentAllocations
      x-api-path-slug: overpaymentsoverpaymentidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
      - Ocations
  /Payments:
    get:
      summary: Get Payments
      description: Get payments.
      operationId: getPayments
      x-api-path-slug: payments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payments
    post:
      summary: Post Payments
      description: Post payments.
      operationId: postPayments
      x-api-path-slug: payments-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
    put:
      summary: Put Payments
      description: Put payments.
      operationId: putPayments
      x-api-path-slug: payments-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
    x-related-model:
      summary: X-related-model Payments
      description: X-related-model payments.
      operationId: x-related-modelPayments
      x-api-path-slug: payments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Payments
  /Payments/{PaymentID}:
    get:
      summary: Get Payments Payment
      description: Get payments payment.
      operationId: getPaymentsPayment
      x-api-path-slug: paymentspaymentid-get
      parameters:
      - in: path
        name: PaymentID
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
    post:
      summary: Post Payments Payment
      description: Post payments payment.
      operationId: postPaymentsPayment
      x-api-path-slug: paymentspaymentid-post
      parameters:
      - in: path
        name: PaymentID
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
    x-related-model:
      summary: X-related-model Payments Payment
      description: X-related-model payments payment.
      operationId: x-related-modelPaymentsPayment
      x-api-path-slug: paymentspaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
  /Prepayments:
    get:
      summary: Get Prepayments
      description: Get prepayments.
      operationId: getPrepayments
      x-api-path-slug: prepayments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Prepayments
    x-related-model:
      summary: X-related-model Prepayments
      description: X-related-model prepayments.
      operationId: x-related-modelPrepayments
      x-api-path-slug: prepayments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
  /Prepayments/{PrepaymentID}:
    get:
      summary: Get Prepayments Prepayment
      description: Get prepayments prepayment.
      operationId: getPrepaymentsPrepayment
      x-api-path-slug: prepaymentsprepaymentid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: PrepaymentID
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
    x-related-model:
      summary: X-related-model Prepayments Prepayment
      description: X-related-model prepayments prepayment.
      operationId: x-related-modelPrepaymentsPrepayment
      x-api-path-slug: prepaymentsprepaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
  /Prepayments/{PrepaymentID}/Allocations:
    put:
      summary: Put Prepayments Prepayment Allocations
      description: Put prepayments prepayment allocations.
      operationId: putPrepaymentsPrepaymentAllocations
      x-api-path-slug: prepaymentsprepaymentidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PrepaymentID
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
      - Ocations
    x-related-model:
      summary: X-related-model Prepayments Prepayment Allocations
      description: X-related-model prepayments prepayment allocations.
      operationId: x-related-modelPrepaymentsPrepaymentAllocations
      x-api-path-slug: prepaymentsprepaymentidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
      - Ocations
  /PurchaseOrders:
    get:
      summary: Get Purchaseorders
      description: Get purchaseorders.
      operationId: getPurchaseorders
      x-api-path-slug: purchaseorders-get
      parameters:
      - in: query
        name: DateFrom
      - in: query
        name: DateTo
      - in: query
        name: No Name
      - in: query
        name: Status
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
    post:
      summary: Post Purchaseorders
      description: Post purchaseorders.
      operationId: postPurchaseorders
      x-api-path-slug: purchaseorders-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: PurchaseOrders
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
    put:
      summary: Put Purchaseorders
      description: Put purchaseorders.
      operationId: putPurchaseorders
      x-api-path-slug: purchaseorders-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: PurchaseOrders
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
    x-related-model:
      summary: X-related-model Purchaseorders
      description: X-related-model purchaseorders.
      operationId: x-related-modelPurchaseorders
      x-api-path-slug: purchaseorders-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
  /PurchaseOrders/{PurchaseOrderID}:
    get:
      summary: Get Purchaseorders Purchaseorder
      description: Get purchaseorders purchaseorder.
      operationId: getPurchaseordersPurchaseorder
      x-api-path-slug: purchaseorderspurchaseorderid-get
      parameters:
      - in: path
        name: PurchaseOrderID
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
    post:
      summary: Post Purchaseorders Purchaseorder
      description: Post purchaseorders purchaseorder.
      operationId: postPurchaseordersPurchaseorder
      x-api-path-slug: purchaseorderspurchaseorderid-post
      parameters:
      - in: path
        name: PurchaseOrderID
      - in: body
        name: PurchaseOrders
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
    x-related-model:
      summary: X-related-model Purchaseorders Purchaseorder
      description: X-related-model purchaseorders purchaseorder.
      operationId: x-related-modelPurchaseordersPurchaseorder
      x-api-path-slug: purchaseorderspurchaseorderid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
  /PurchaseOrders/{PurchaseOrderID}/Attachments:
    get:
      summary: Get Purchaseorders Purchaseorder Attachments
      description: Get purchaseorders purchaseorder attachments.
      operationId: getPurchaseordersPurchaseorderAttachments
      x-api-path-slug: purchaseorderspurchaseorderidattachments-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
  /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName}:
    get:
      summary: Get Purchaseorders Purchaseorder Attachments Filename
      description: Get purchaseorders purchaseorder attachments filename.
      operationId: getPurchaseordersPurchaseorderAttachmentsFilename
      x-api-path-slug: purchaseorderspurchaseorderidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
      - FileName
    post:
      summary: Post Purchaseorders Purchaseorder Attachments Filename
      description: Post purchaseorders purchaseorder attachments filename.
      operationId: postPurchaseordersPurchaseorderAttachmentsFilename
      x-api-path-slug: purchaseorderspurchaseorderidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
      - FileName
  /Receipts:
    get:
      summary: Get Receipts
      description: Get receipts.
      operationId: getReceipts
      x-api-path-slug: receipts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Receipts
    post:
      summary: Post Receipts
      description: Post receipts.
      operationId: postReceipts
      x-api-path-slug: receipts-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Receipts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Receipts
    put:
      summary: Put Receipts
      description: Put receipts.
      operationId: putReceipts
      x-api-path-slug: receipts-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Receipts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Receipts
    x-related-model:
      summary: X-related-model Receipts
      description: X-related-model receipts.
      operationId: x-related-modelReceipts
      x-api-path-slug: receipts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Receipts
  /Receipts/{ReceiptID}:
    get:
      summary: Get Receipts Receipt
      description: Get receipts receipt.
      operationId: getReceiptsReceipt
      x-api-path-slug: receiptsreceiptid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
    post:
      summary: Post Receipts Receipt
      description: Post receipts receipt.
      operationId: postReceiptsReceipt
      x-api-path-slug: receiptsreceiptid-post
      parameters:
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
      - in: body
        name: Receipts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
    x-related-model:
      summary: X-related-model Receipts Receipt
      description: X-related-model receipts receipt.
      operationId: x-related-modelReceiptsReceipt
      x-api-path-slug: receiptsreceiptid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
  /Receipts/{ReceiptID}/Attachments:
    get:
      summary: Get Receipts Receipt Attachments
      description: Get receipts receipt attachments.
      operationId: getReceiptsReceiptAttachments
      x-api-path-slug: receiptsreceiptidattachments-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
  /Receipts/{ReceiptID}/Attachments/{FileName}:
    get:
      summary: Get Receipts Receipt Attachments Filename
      description: Get receipts receipt attachments filename.
      operationId: getReceiptsReceiptAttachmentsFilename
      x-api-path-slug: receiptsreceiptidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
      - FileName
    post:
      summary: Post Receipts Receipt Attachments Filename
      description: Post receipts receipt attachments filename.
      operationId: postReceiptsReceiptAttachmentsFilename
      x-api-path-slug: receiptsreceiptidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
      - FileName
  /RepeatingInvoices:
    get:
      summary: Get Repeatinginvoices
      description: Get repeatinginvoices.
      operationId: getRepeatinginvoices
      x-api-path-slug: repeatinginvoices-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - RepeatingInvoices
    x-related-model:
      summary: X-related-model Repeatinginvoices
      description: X-related-model repeatinginvoices.
      operationId: x-related-modelRepeatinginvoices
      x-api-path-slug: repeatinginvoices-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - RepeatingInvoices
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