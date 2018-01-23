# Test Database

Implement **your own working storage system (own database engine)** with an API. 
Describe implemented solution and why you've chosen a particular approach.

## Description
The database is an organized collection of information potentially needed in the future. 
The point is to avoid using existing DBs (like PostgreSQL, MySQL, 
MongoDB, Redis ) while creating own storage system (own database engine)
 using NodeJS. The recommended subject area is simple contacts list, where one record contains Name and Phone Number. You are able to choose your own subject area - it will be a plus.

The database server may consist of several independent blocks:

* Storage engine (database engine). Where and how to store data?
* API (console, http, socket). How to communicate with a storage system?

The database server supports the following operations:

* Add record to the storage
* Get record from the storage
* Update existing record
* Delete existing record
* Get list of records

## Requirements
* Application should be written using NodeJS
* Support of all [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) operations
* Access to the database by any implemented [API](https://en.wikipedia.org/wiki/Application_programming_interface) (for example, console, http, sockets).
* The ability to save to a file so that you can restart your storage system and restore the state (for example, flush, commit or snapshot approach)
* Application should log all actions

## It’s allowed to use for implementation
* NodeJS
* Any frameworks for the API
* Any approaches and libraries for logging

## Advanced futures (optional)
* Sharding mechanism
* Scaling mechanism

## Possible subject areas
* Contacts list
* Movie catalogue
* Songs catalogue
* Restaurant menu
* Orders list
* etc.

#### In case of any questions don’t hesitate to contact me directly.
