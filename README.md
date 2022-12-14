 Point of sale API

A very basic Django project that uses Django Rest Framework to provide a RESTful API for a point of sale that let's you track the inventory of products and the orders done.



The API  use **JSON** format and should provide the following endpoints and functionalities:

### `/api/products/`

* List all existing products
* Create a new product
* Retrieve an existing product
* Update an existing product

Note that **deleting a product is not allowed**.

A product must allow you to save:

* The description of the product
* The unit price of the product in cents
* The available stock of the product

### `/api/orders/`

* List all existing orders
* Create a new order
* Retrieve an existing order

Note that **updating or deleting a product is not allowed**.

A order must allow you to save/calculate:

* The list of items that were purchased
* The quantity of each item
* The total amount earned by the order in cents
