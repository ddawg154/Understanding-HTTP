# What Happens When You Visit a Website

When you enter a URL into a browser, several steps occur very quickly.

## 1. DNS Lookup
The browser finds the IP address of the website using the Domain Name System.

## 2. Establishing a Connection
The browser creates a TCP connection with the server.

## 3. Sending an HTTP Request
Example:
GET / HTTP/1.1  
Host: example.com

## 4. Server Processes the Request
The server finds the files needed to load the page.

## 5. Server Sends an HTTP Response
Example:
HTTP/1.1 200 OK  
Content-Type: text/html

## 6. Browser Renders the Page
The browser reads the HTML, loads CSS and JavaScript, and displays the webpage.

## Navigation
Back: [HTTP Requests and Responses](requests-responses.md)  
Back to README: [README](README.md)
