# What Happens When You Visit a Website

When you enter a URL into a browser there are several steps that occur very quickly.

## 1. DNS Lookup
The browser will first find the IP address of the website using the Domain Name System.

## 2. Establishing a Connection
Then the browser creates a TCP connection with the server.

## 3. Sending an HTTP Request
Example:
GET / HTTP/1.1  
Host: example.com

## 4. Server Processes the Request
After sending the request, the server finds the files needed to load the page.

## 5. Server Sends an HTTP Response
Example:
HTTP/1.1 200 OK  
Content-Type: text/html

## 6. Browser Renders the Page
The browser will then read the HTML, load the CSS and JavaScript, and display the webpage.

## Navigation
Back: [HTTP Requests and Responses](requests-responses.md)  
Back to README: [README](README.md)
