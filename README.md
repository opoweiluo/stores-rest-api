# stores-rest-api
##Introduction  
This is a small project to practice RESTful APIs by using Flask, Python.  

## Resources

### UserRegister

- `POST: /register`
  - Description: send user name and password information in body to register.

### UserLogin

- `POST: /auth`
    - Description: authenticate a user and ,if authenticated, respond with a jwt token.

### Item

- `GET: /item/<name>`
    - Description: get an item by name.
    - Request header: `Authorization JWT {{jwt_token}}`
- `POST: /item/<name>`
    - Description: create a new item.
- `DELETE: /item/<name>`
    - Description: delete an item by name.
    
### ItemList

- `GET: /items`
    - Description: get all items
    
### Store

- `GET: /store/<name>`
    - Description: get a store by name.
- `POST: /store/<name>`
    - Description: create a new store.
- `DELETE: /store/<name>`
    - Description: delete an store by name.
    
### StoreList

- `GET: /stores`
    - Description: get all stores
