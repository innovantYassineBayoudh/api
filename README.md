# api

To start the project type in command line
 npm install
 npm start
 
End points : 
POST : http://localhost:8080/api/auth/signin: Login
Example body :
{"username" : "yass123" , "password" : "azerty"}

POST : http://localhost:8080/api/auth/signup : Register 
example body :
 {
    "firstName" : "Yassine",
    "lastName" : "Bayoudh",
    "username" : "yass123",
    "password" : "azerty",
    "roles" : ["user"]
    }
