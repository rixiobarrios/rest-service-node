## REST Service Node

**REST Client, REST Service, and API Calls**
- REST Client: code or an app that can access these REST services.
- REST Service: the server. 
- REST API: this defines the endpoint and methods allowed to access/submit data to the server. 

**Anatomy of REST**
- Endpoint: is the URL where the REST Server is listening.
- Method: request data or modify it with multiple methods for the different types of requests.
- Types of Requests: 
    1. GET: Get resource from the server.
    2. POST: Create resource to the server.
    3. PATCH or PUT: Update existing resource on the server.
    4. DELETE: Delete existing resource from the server.
- Headers: The additional details provided for communication between client and server (remember, REST is stateless). Some of the common headers are:
1. Request: 
    - host: the IP of client (or from where request originated)
    - accept-language: language understandable by the client.
    - user-agent: data about client, operating system and vendor.
2. Response:
    - status: the status of request or HTTP code.
    - content-type: type of resource sent by server.
    - set-cookie: sets cookies by server.
3. Data: (also called body or message) contains info you want to send to the server. 

**Aplications**
- NodeJS
- ExpressJS

**Packages installed**
- body parser

**Files**
- Server: ```./server.js```
- Client: ```./client.js```

**Run the server**
```node server.js```

- If everything is successful, you should see a message on console saying: ```Server is running on port 5000.```  
- Open up your browser and navigate to http://localhost:5000/.
- If you see the word ```Hi!```, your first GET request was successful.
