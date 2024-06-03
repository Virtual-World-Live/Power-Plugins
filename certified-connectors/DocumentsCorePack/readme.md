

## DocumentsCorePack Connector
DocumentsCorePack allows you to generate and automate your documents incorporating Dataverse and Dynamics 365 data. Based on Microsoft Word – templates, the DocumentsCorePack connector provides you with a variety of actions to create and process your documents.

The DocumentsCorePack Connector brings this functionality to Power Automate and Flows.
[Details](https://www.mscrm-addons.com/Products/DocumentsCorePack) 

Follow [this link](https://short.mscrm-addons.com/dcpconnector) to see step-by-step tutorials, ho tos and get detailed information.

## Publisher: PTM EDV Systeme GmbH - mscrm-addons.com Corp.


## Prerequisites


- Dynamics 365 or Dataverse environment. 
- DocumentsCorePack Service (You can start a trial using [this link](https://short.mscrm-addons.com/dcptrial))

### Generate API Key for your environment
An API key can be generated from the DocumentsCorePack Service configuration (Note if you don't have a service you can start a free trial using [this link](https://short.mscrm-addons.com/dcptrial)).

In the Service-Configuration, click on [Optain the API-Key](https://short.mscrm-addons.com/getapikeyimg).

If you have troubles please look into following [article](https://short.mscrm-addons.com/getapikey) or send your an email to support@mscrm-addons.com 


## API documentation
The API documentation can be found [here](https://short.mscrm-addons.com/apidocu)

## Supported Operations

### Create document (sync) (V3)
Creates a new document. For more information, [click here](https://short.mscrm-addons.com/createdocumentjob).

### Create DocumentJob (async) (V3)
Creates a new document. The action does NOT wait for a result. For more information, [click here](https://short.mscrm-addons.com/createdocumentjobasync).

### Create Multipart document (async) (V3)
Create a document consisting of multiple components. The action does NOT wait for a result. For more information, [click here](https://short.mscrm-addons.com/multipart).

### Sign DocumentJob (sync) (V3)
Send a document for e-signing.

### Run One-Click-Action (sync) (V3)
Runs a One-Click-Action and waits for the result. For more information, [click here](https://short.mscrm-addons.com/oca).

### Run One-Click-Action (async) (V3)
Runs a One-Click-Action. The action does NOT wait for a result. For more information, [click here](https://short.mscrm-addons.com/oca).

### Create Multipart document (sync) (V3)
Create a document consisting of multiple components. For more information, [click here](https://short.mscrm-addons.com/multipart).

### Get DocumentJob result (V3)
Retrieves status information of a DocumentJob. The result will include the generated document.

### Get DocumentJob status (V3)
Retrieves the status of a DocumentJob.

### Print DocumentJob (V3)
Print document generated by a DocumentJob.

### Print File (V3)
Prints a document content or base64 encoded file. Supported filetypes: pdf, docx.

### Attach DocumentJob as note (V3)
Attach document generated by a DocumentJob as a note to a Dynamics 365 record.

### Attach file as note (V3)
Attach a document content or base64 encoded file as a note to a Dynamics 365 record.

### Attach DocumentJob to email (V3)
Attach the document content generated by a DocumentJob as attachment to a Dynamics 365 email.

### Concatenate two DocumentJobs (V3)
Concatenate two documents generated by two DocumentJobs. Supported filetypes: pdf, docx.

### Concatenate two document contents or base64 encoded files (pdf,docx) (V3)
Concatenates two document contents or base64 encoded files. Supported filetypes: pdf,docx.

### Attach file to email (V3)
Attach a document content or base64 encoded file as attachment to a Dynamics 365 email.

### Send email (V3)
Send Dataverse email.

### Create SharePoint folder (V3)
Creates folders on SharePoint in the document location of a Dynamics 365 record.

### Gets the Default Environment for this ApiKey
Returns the environment id for the used ApiKey.

### Get Profiles for a User APIKey
Retrieves all Profile Ids for this ApiKey.

### Get document templates
Retrieves a list of available DocumentsCorePack Templates.

### Get a list of DocumentLocations
Retrieves a list of Dynamics DocumentLocations.

### Get Printers
Retrieve available printers.

### Get a list of dynamics users
Retrieves a list of Dynamics users.

### Get One-Click-Actions
Retrieves all One-Click-Actions configured in Dynamics 365.

### Retrieve table names with annotation capability
Retrieve a list of Dynamics tables supporting annotations.

### Get e-signing providers
Retrieve all e-Signature providers available in DocumentsCorePack.

### WhoAmI (V3)
Retrieve information about the used API Key and associated DocumentsCorePack Service.

## Obtaining Credentials

First of all, you need to [Create an Account](https://short.mscrm-addons.com/myaccount) 
and sign up for a DocumentsCorePack Service (14 days free trials available).

Get the API Key for your environment:
- [Create a DocumentsCorePack Service](https://short.mscrm-addons.com/serviceconfig)
- [Optain the API-Key](https://short.mscrm-addons.com/getapikeyimg)


If you have question send an email to support@mscrm-addons.com

## Known Issues and Limitations
N/A