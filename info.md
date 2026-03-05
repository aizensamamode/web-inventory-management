link : https://excalidraw.com/#json=d83N9awPCfn4dVZ1ovtxF,EgLOxUtmqI3byhGTsq3f9A




Explanation of Each Folder
1️⃣ controller

Handles requests from the browser.

Example:

AuthController.java

Handles:

/login
/signup
/logout

Example:

ProductController.java

Handles:

/addProduct
/deleteProduct
/viewProducts
2️⃣ service

Contains the logic of the system.

Example:

UserService.java

What it does:

Check login

Validate signup

Process user data

Controllers call the service.

3️⃣ repository

Talks to the database (MySQL).

Example:

UserRepository.java

It can do:

save user
find user
delete user
4️⃣ model

Represents database tables as Java objects.

Example:

User.java
id
username
password

Example:

Product.java
id
name
price
quantity
5️⃣ templates

This is where HTML files go.

Spring Boot loads pages from here.

Example:

login.html
signup.html
home.html
products.html
inventory.html
6️⃣ static

Contains frontend resources.

CSS
static/css/style.css
static/css/login.css
JavaScript
static/js/script.js
Images
static/images/logo.png
