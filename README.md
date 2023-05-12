# Project-PetStore

* Testing of PetStore API using Postman/Newman
* Used chaining and collection variables to integrate the collection requests

## Links

### Swagger document:
https://petstore.swagger.io/

## Tools
Postman/Newman, newman-reporter-html
* npm install -g newman
* npm install -g newman-reporter-html

## Execution Commands
* newman run pets_module_xml.postman_collection.json -r html
* newman run user_module_json.postman_collection.json -r html
* newman run store_module_json.postman_collection.json -r html

## Collections
### 1. Pets Module
* Testing features to create, update, search and delete pet.
* Executed and viewed using xml.

### 2. Store Module
* Testing features to create, search and delete orders
* Executed and viewed in JSON

### 3. User Module
* Testing features to add, searching, updating, deleting users, and login.
* Executed and viewed in JSON
