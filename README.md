# Api-Request-and-Response
API REQUEST AND RESPONSE METHODS 

API METHODS in Amazon 

GET - Amazon
-> in Amazon Website get method is working in Fetching details about a product
    or order.
-> Searching for items in the search bar.
-> Getting users details after a login.

Example 
get /products/123


POST - Amazon
-> in Amazon Website post methon is working in creating or placing an order.
-> Creating a new User Account.
-> Adding product to cart.

Example 
post /orders
Content-type: application/json

{
    "userId"     : "22",
    "product_id" : "1234",
    "quantity"   : 2
}


PUT - Amazon

->In Amazon website put method is working in updating user information e.g
shipping address of the user.
->Completely replacing the details of the product.

Example

PUT /users/9876
Content-Type: application/json

{
  "name": "Ali Raza",
  "email": "infoaliraza22@gmail.com",
  "address": "123 Main St"
}


PATCH - Amazon

->In Amazon website patch method is working in updating the shiping address while other data remains the same.
->Modifying the quantity of an item in the shopping cart.

Example

PATCH /users/9876
Content-Type: application/json

{
  "address": "Ghouisa Colony Khurrianwala"
}


DELETE - Amazon
->In Amazon website delete method is working in deleting a product from 
    the shopping cart.
->Remove a user account.

Example

DELETE /cart/items/12345.




