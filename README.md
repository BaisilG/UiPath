# UiPath
Ephesoft Transact offers machine learning-powered extraction of structured or unstructured documents
The Ephesoft package can do digitization of semi structured and unstructured data.

Package consists of 7 activities

Transact Scope - The activity opens a connection to your instance of Transact, allowing all contained activities to be authenticated. Also pulls Batch Classes to be used at design time. 

Upload Batch - The activity sends multiple files to your Batch Class for processing.

Get All Batch Instances - The activity retrieves all active Batches with a specified status.

Classify Document - The activity submits a (potentially multi-page document) for OCR and classification. As this file can contain multiple different types of documents (e.g. invoice, contract, transcript...), a list of all constituent document types is returned along with the fields they may comprise.

Single-Page Extraction - The activity submits a single-page file for fast OCR, classification, and extraction of fields.

Multi-Page Extraction - The activity will submit multi-page files covering several document types and tables for processing. 

Get Extraction Results - Retrieves extracted fields and tables using the reference code from the previous activity.



Ephesoft is on a mission to help organizations increase productivity, improve efficiency and receive a substantial ROI (Return of Investment) through the patented machine learning technology embedded in their document capture solutions. They play a pivotal role for our clients by improving the way they capture, manage and analyze unstructured data.

The Ephesoft Transact package can perform digitization of semi-structured and unstructured data. Some advantages of using this packages are that no templates are required, it supports table extraction, and all operations are powered by a machine learning model that learns as you digitize documents.









Ephesoft Transact Scope
SUGGEST EDITS
UiPath.Ephesoft.Activities.TransactScope

This scope opens a connection to your Transact portal, authenticating all contained activities.

This connection is also available at design-time, displaying all batch classes currently present in the portal. To demonstrate, start by filling in the Password, URL, Username, and (if applicable) Tenant properties of the Transact Scope.


When Password, URL, and Username are entered, the Connect button becomes available. Simply click it to open the connection. If any of the credentials are incorrect or the Transact portal is unavailable, an error will be displayed.


Now, whenever an activity is dropped into the scope, all batch classes from your Transact portal will be available, making it easy to design workflows without ever leaving Studio.


Properties
Common
DisplayName (String) - The display name of the activity.
Input
Password (String) - Your Transact password. Supports only strings and String variables.
ServerAddress (String) - The address of your Transact server. Supports only strings and String variables.
Username (String) - Your Transact username. Supports only strings and String variables.
