# api

## Installation

```bash
 npm install
 npm start
```

 
## End points : 
POST : http://localhost:8080/api/auth/signin: Login 

```bash
{"username" : "yass123" , "password" : "azerty"}
```


POST : http://localhost:8080/api/auth/signup : Register
```bash
 {
    "firstName" : "Yassine",
    "lastName" : "Bayoudh",
    "username" : "yass123",
    "password" : "azerty",
    "roles" : ["user"]
    }
```

