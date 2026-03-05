# web-inventory-management
web-based multi-branch inventory management system

System flow

inventory-system
│
├── src
│   └── main
│       ├── java
│       │   └── com.example.inventory
│       │       │
│       │       ├── controller
│       │       │     AuthController.java
│       │       │     ProductController.java
│       │       │     InventoryController.java
│       │       │
│       │       ├── service
│       │       │     UserService.java
│       │       │     ProductService.java
│       │       │     InventoryService.java
│       │       │
│       │       ├── repository
│       │       │     UserRepository.java
│       │       │     ProductRepository.java
│       │       │
│       │       ├── model
│       │       │     User.java
│       │       │     Product.java
│       │       │
│       │       └── InventoryApplication.java
│       │
│       └── resources
│           │
│           ├── templates
│           │     login.html
│           │     signup.html
│           │     home.html
│           │     products.html
│           │     inventory.html
│           │
│           ├── static
│           │     ├── css
│           │     │     style.css
│           │     │     login.css
│           │     │
│           │     ├── js
│           │     │     script.js
│           │     │
│           │     └── images
│           │           logo.png
│           │
│           └── application.properties
│
└── pom.xml
