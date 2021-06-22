# simple_json_api for easy CRUD operations
-mkdir API_SERVER
-cd API_SERVER
- npm init -y
-npm i -g json-server
-add your json file
// {
  "users": [
    {
      "id": 1,
      "first_name": "John",
      "last_name": "Doe",
      "email": "john23@gmail.com"
    },
    {
      "id": 2,
      "first_name": "Anna",
      "last_name": "Bauer",
      "email": "annab56@gmail.com"
      }
      //
    },-json-server --watch users.json 
    
    
    
