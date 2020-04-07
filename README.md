# shop-API
Building a RESTFUL API With nodejs
This API was built with Node server 8.11
 
 The API is built using Nodejs, to model an  actuall shop, you can add product, search for product by price, by type,</br>  The API uses mangodb as database and also includes user authentication.
 To use clone repo and
 
# Prerequisites
What things you need to install the software and how to install them\
 ```
  bcrypt
  body-parser
  express
  jsonwebtoken
  mongoose
  mongoose-morgan
  multer
 ```

 
# To get started 
`git clone`

them run <br> 
`npm install` <br>

There after run <br>
`npm init`

# Running the tests
After starting your node server you can test using <br>To check orders, remove and add
`http://localhost:3000/orders/`
<br> To add and remove and view new products
`http://localhost:3000/products/`

Make sure to also add your Mongo Atlas Admin Username to  nodemon.json file.

```
{
    "env": {
        "MONGO_ATLAS_PW": "YOUR_MONGO_USER_PW"
    }
}
```




   
