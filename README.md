# Store-CRUD-RESTful-app
Project description: A market simulation with CRUD operation on stores, items, and users. After registration, an
email is sent to the user for verification before the account is eligible. Each user is assigned a JWT on login and
certain routes request a Fresh JWT in order to be accessed. Each user can also upload images and have one
avatar image. Special error message handling implementation for better scaling.
The application has been tested using the Postman Tool.
Technologies: Flask, Marshmallow, SQAlchemy, Flask-RESTful, Flask-JWT-Extended, Flask-Uploads
