---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting Get Currencies
  description: Get currencies.
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