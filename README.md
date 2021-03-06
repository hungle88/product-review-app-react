# product-review-app
# React Web Application  
## Requirements  
1. Users can add, delete, update and fetch all the products in the application.  
a. For delete and update: Only the creator of the product can do these operations.
2. Users can add, delete, update and fetch reviews of a product.  
a. For delete and update: Only the creator of the review can do these operations.
3. Products have reputation points:  
a. An excellent rating adds 2 points to the product’s reputation score.  
b. A bad rating deducts 1 point from the product’s reputation score.  
c. A good rating does not change a product’s reputation score.  
4. Users will sign in / sign up before they can use the application.
5. Products can be sorted by reputation.
6. All backend API requests are logged.


## SuperUser Account  
1. The user collection in the database must have a superuser account. (Role is superuser).
2. Superuser may log in to the Application and see a dashboard with the following functionalities:  
a. List all users’ accounts, activates/deactivates, and reset their password.  
b. List all the requests from the log.    

## Technical Details  
1. Use Redux to manage the state.
2. Use JWT for authentication and authorization.
3. Follow the REST convention to build the server application.