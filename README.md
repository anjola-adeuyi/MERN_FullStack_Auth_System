# MERN FullStack Auth & Login System

**Creating a Login System in a MERN Stack Application**
In this project, I will be building a login, registration, profile, and reset password functionality in a MERN stack application. I will also be sending emails from the Node.js backend.


## Working with the Project

For the Client Folder create .env file and put this code inside it.

.env
```
REACT_APP_SERVER_DOMAIN='<server_domain>' # example 'http://localhost:8080'
```


After that create a file in the Server Folder with the name config.js and put the below code inside it.

config.js
```
export default {
    JWT_SECRET : "<secret>",
    EMAIL: "jola@test.email", // testing email & password
    PASSWORD : "sMf46xCzrvdrxvuagc",
    ATLAS_URI: "<MONGODB_ATLAS_URI>"
}
```

> **Note:** The **ATLAS_URI** is important to work this project.

Now, create all these variables in the project and make sure you set ATLAS_URI variable.
Otherwise, the project will not work.

