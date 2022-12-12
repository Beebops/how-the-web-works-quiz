# How the Web Works

## What is HTTP?

HTTP (hypertext transfer protocol) is the standard by which clients send and receive data from a server.

## What is a URL?

Uniform Resource Locator is the address of a site on the internet

## What is DNS?

The Domain Name System will take a URL address and converts it into an IP address

## What is a query string?

A query string is a way of passing key:value pairs to a URL address: ?key1=value1&key2=value2

## List two HTTP Verbs and their use cases

GET - a client requests data from a server
POST - data sent to a server that updates/changes the data on that server

## What is an HTTP request?

A client uses the HTTP protocol to request data from a server

## What is an HTTP response?

The data that gets sent back to a client from a server using the HTTP protocol

## What is an HTTP header?

A header is additional information about the type of request or response. Examples of request header - the host, accept. Examples of response header - content-type, cache-control

## What happens when you type a URL in a browser?

1. the browser uses DNS to resolve the URL name into an IP address
2. the browser makes a request to that address and includes headers
3. the server sends a response back, usually HTML, and also a status code that gives info about the success of the response
4. the browser uses the HTML to make a DOM and locates any additional resources like CSS files, scripts, images, etc in a separate HTTP request from the server
