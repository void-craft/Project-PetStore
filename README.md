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
### Pets Module
* Testing features to create, update, search and delete pet.
* Executed and viewed using xml.
* https://api.postman.com/collections/27171422-d389a4bd-96b5-4adc-b6b6-075b50f7d888?access_key=PMAT-01H06XTQB95Y53DC4XT4GQG79F

### Store Module
* Testing features to create, search and delete orders
* Executed and viewed in JSON
* https://api.postman.com/collections/27171422-50075461-2263-43da-a2bd-ebc14a81035c?access_key=PMAT-01H06XX5WA0KX8RD7T91Q3V7X8

### User Module
* Testing features to add, searching, updating, deleting users, and login.
* Executed and viewed in JSON
* https://api.postman.com/collections/27171422-417a7421-c92b-4e8f-9bd6-1ef67891e1d5?access_key=PMAT-01H06XYDHN63A92CYGT5RZNGMG
