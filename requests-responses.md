# HTTP Requests and Responses

Web communication works through a request and response cycle. A browser will send an HTTP request, and a server will then send back an HTTP response.

## HTTP Requests
A request includes:
- Method (GET, POST, etc.)
- Path (which is the file or resource being requested)
- Headers (can include any extra information)
- Body (can include any optional data)

Common HTTP Methods:
- GET: Request data.
- POST: Send new data.
- PUT: Update data.
- DELETE: Remove data.

## HTTP Responses
A response includes:
- Status code
- Headers
- Body (HTML, images, or other content)

Common Status Codes:
- 200 OK: Success.
- 301 Moved Permanently: Redirect.
- 404 Not Found: Resource not found.
- 500 Internal Server Error: Server problem.

## Example
Request:
GET /index.html HTTP/1.1  
Host: example.com

Response:
HTTP/1.1 200 OK  
Content-Type: text/html

## Navigation
Back: [What Is HTTP?](what-is-http.md)  
Next: [What Happens When You Visit a Website](web-process.md)
