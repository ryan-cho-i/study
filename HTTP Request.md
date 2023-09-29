







1. How to get Client IP Address on Server?
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

