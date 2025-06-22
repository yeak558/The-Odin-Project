A request for the MDN home page might look like this:
```
GET /en-US/ HTTP/2

Host: developer.mozilla.org
```
The response sent by the server might looks something like this:
```
HTTP/2 200

date: Tue, 11 Feb 2025 11:13:30 GMT
expires: Tue, 11 Feb 2025 11:40:01 GMT
server: Google frontend
last-modified: Tue, 11 Feb 2025 00:49:32 GMT
etag: "65f26b7f6463e2347f4e5a7a2adcee54"
content-length: 45227
content-type: text/html

<!doctype html> ... (the 45227 bytes of the requested web page HTML)
```
The full response is more complex than this.
The main parts are as follows:
`HTTP/2 200`: The version of HTTP that the server is using to send the response, in this case HTTP/2 followed by a 'status code' indicating whether the request was successful. 200 indicates success.

`date, expires,...`: HTTP headers containing additional information about the response (requests also can have headers).

`<!doctype html>...`: The response body, which in this case contains the MDN homepage's HTML document.


- Other Status Codes
`301`: The requested resource has been permanently moved to a new location, which is provided in the response. This is used for redirecting content when it's moved.
`400`: The server can't process the request. This usually happens when the request isn't in a format the server understands, or has errors in it.
`403`: The server will not give the client access to the requested resource. This usually happens when the server knows who the client is, but they don't have permission to access the requested page.
`404`: The server cannot find the requested resource. This status is commonly returned if the URL is wrong or if content is deleted without putting a redirect in place.
`503`: The request cannot be handled due to a problem with the server. This is common when servers are offline for maintenance, and it's expected to be temporary.

Mynote: Advance this topic later
