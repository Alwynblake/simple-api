# Simple json-server API

## Author

Alistair Blake

## Description

This is a simple api built with json-server that has the following `/categories` and `/products` endpoints:

```
/categories GET, POST
/categories/:id/ PUT, DELETE
/products GET, POST
/products/:id/ PUT, DELETE

```

## Data Models Include the Following Fields:

### /categories

* id
* name
* display_name
* description
  
### /products

* id 
* category
* name
* display_name
* description

### To run the server

* Type the command `npm run watch`

### Links and Resources
* GitHub Repo: https://github.com/Alwynblake/simple-api
