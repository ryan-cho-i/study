
1. HTTP Method
2. URI
3. HTTP Version
4. Headers
	1. `req.headers`
	2. Host
		1. Description: Specifies the host (domain or IP address) of the web server receiving the request.
		2. Example: `Host: www.example.com`
	3. User-Agent
		1. Description: Provides information about the client software or user agent making the request.
		2. Example: `User-Agent: Mozilla/5.0`
	4. Authorization
		1. Description: Contains user authentication information, often used with usernames, passwords, or tokens.
		2. Example: `Authorization: Bearer <token>`
	5. Cookie
		1. `req.cookie`
		2. Description: Contains one or more cookies associated with the current request.
		3. Example: `Cookie: sessionid=abc123; username=johndoe`
	7. Content-Type
		1. Description: Indicates the media type of the data in the request body (e.g., JSON, XML).
		2. Example: `Content-Type: application/json`
6. Request Body

```
POST /submit-data HTTP/1.1
Host: www.example.com
User-Agent: Mozilla/5.0
Content-Type: application/json
Content-Length: 45

{
  "name": "John Doe",
  "email": "johndoe@example.com"
}
```


7. How to get Client IP Address on Server?
```js
const express = require('express');
const app = express();

app.get("/", (req, res) => {
	const clientIp = req.ip
	res.send("Client IP Address is : ${clientIp}")
})

const PORT = 8080;
app.listen(PORT, ()=>{
	console.log("Server on ${PORT}")
})
```



