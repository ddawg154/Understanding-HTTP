# HTTP Requests & Responses

Every action you take on the web—loading a page, clicking a link, submitting a form—creates an **HTTP request**. The server then returns an **HTTP response**.

Understanding this exchange is key to understanding how the web works.

---

## HTTP Requests

A request includes:
- **Method:** What action the client wants to perform  
- **Path:** What resource it wants (like `/index.html`)  
- **Headers:** Small pieces of additional information  
- **Body:** Optional data sent with the request (ex: form submissions)

### Common HTTP Methods
- **GET** — Retrieve information  
- **POST** — Send new data to the server  
- **PUT** — Update existing data  
- **DELETE** — Remove data  
---

## HTTP Responses

A response includes:
- **Status code:** Indicates success or failure  
- **Headers:** Information about the returned data  
- **Body:** The content (HTML, JSON, images, etc.)

### Common HTTP Status Codes
- **200 OK** — The request succeeded  
- **301 Moved Permanently** — The resource was redirected  
- **404 Not Found** — The resource doesn't exist  
- **500 Internal Server Error** — Something broke on the server  
---

## Example Request & Response

### Request (from browser)
