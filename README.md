## **_Spring Boot 3.0 backend application running with Postgres 12.1 on Heroku cloud_**

### FOR DETAILS CHECK --> class_diagram.jpg and instance_diagram.jpg

![Class diagram](/class_diagram.jpg)

![CInstance diagram](/instance_diagram.jpg)

Link to application: https://rgiovann-springboot-app.herokuapp.com/

----- **USER TABLE** ---

ADD USER Postman

PUT https://rgiovann-springboot-app.herokuapp.com/users

JSON body

{

"name": "Bob Brown",

"email": "bob@gmail.com",

"phone": "977557755",

"password": "123456"

}

DELETE USER Postman

DELETE https://rgiovann-springboot-app.herokuapp.com/users/ID ID= user oid

UPDATE USER Postman

POST https://rgiovann-springboot-app.herokuapp.com/users/ID ID= user oid

JSON body

{

"name": "Bob Brown Jr",

"email": "bob@gmail.com",

"phone": "977557755",

"password": "123456"

}

GET ALL USERS Postman

GET https://rgiovann-springboot-app.herokuapp.com/users

GET USER BY ID

GET https://rgiovann-springboot-app.herokuapp.com/users/ID ID= user oid

----- **CATEGORY TABLE** ---

GET ALL CATEGORIES Postman

GET https://rgiovann-springboot-app.herokuapp.com/categories

GET CATEGORY BY ID

GET https://rgiovann-springboot-app.herokuapp.com/user/categories/ID ID= user oid

----- **ORDERS TABLE** ---

GET ALL ORDERS Postman

GET https://rgiovann-springboot-app.herokuapp.com/orders

GET ORDER BY ID

GET https://rgiovann-springboot-app.herokuapp.com/user/orders/ID ID= user oid

----- **PRODUCTS TABLE** ---

GET ALL PRODUCTS Postman

GET https://rgiovann-springboot-app.herokuapp.com/products

GET PRODUCT BY ID

GET https://rgiovann-springboot-app.herokuapp.com/user/products/ID ID= user oid
