## Assignment
- Describe what the internet is.
Simply, it is a wire burried in the ground. Everything in the internet has an IP address, so that no information goes wrong place.
keywords to search: Server, client, ISP, DSL, DNS Server, Router, Ethernet, ICANN, Bluetooth, switch, modem
How celular data is transferred?
  First info goes to cell tower. Then from there it is sent through electromagnetic waves. (That's why it is slower.)
Why internet is not transferred using satellites?
  Because it is slower than fiber optic cables.

- Describe what packets are and how they are used to transfer data.
Basically, when data is sent acreoss the web, it is sent in thousands of small chunks called packets. There are multiple reasons why data is sent in small packets, but most significantly:
  - They are sometimes dropped or corrupted and, when this happens, it's quicker and easier to replace small chunks than entire files.
  - If each website was sent as a single big chunk, only one user could download it at a time. Small chunks allow many different users to download the same website at the same time.

- Understand the differences between a web page, web server, web browser, and search engine.
Web page: A document that can be displayed in a web browser.
Website: A collection of (web) pages. Often called a site.
Web server: A computer that hosts a website on the Internet.
Web service: A software that responds to requests over the Internet to perform a function or provide data. Many websites are also web services. E.g. a site resizez images, provides a weather report, or handles user login.
Search engine: A web service that helps you find other web pages.
Web browser: A piece of software that retrieves and displays web pages.

! Browsers can also display other documents like PDF files or videos, but the term `web page` specifically refers to HTML documents.

- Briefly explain what a client is.
Clients are the typical web user's internet-connected devices.

- Briefly explain what a server is.
Servers are computers that store webpages, sites, or apps.

! When a clients wants to access a webpage, a copy of the webpage code is downloaded from the server onto the client machine to be rendered by the browser and displayed to the user.

- Explain what IP addresses are.
An Internet Protocol address is a numerical label such as 192.0.2.1 that is assigned to a device connected to a computer network that uses the Internet Protocol for communication.

- Explain what DNS servers are.
When users type domain names into the URL bar in their browser, DNS servers are responsible for translating those domain names to numeric IP addresses, leading them to the correct website.

Additional notes:
TCP/IP: Transmision Control Protocol (TCP) and Internet Protocol (IP) are communication protocols that define how data should travel accross the internet.
DNS: The Domain Name System (DNS) is like and 'actual address' book for websites.
HTTP: Hypertext Transfer Protocol (HTTP) is an application protocol that defines a language for clients and servers to speak to each other.

URL: URLs define the locations of unique resources on the internet. Technically, web addresses that you type into the browser address bar form part of Uniform Resource Locators (URLs). URL = a web address + a protocol.
e.g.:
`https://developer.mozilla.org/en-US/`
The main parts of the URL are:
`https`: The protocol being used to send the request. In this case, we are using HTTPS, which is a secure version of HTTP that stops bad people from reading your data while it is being transported. On the modern web, pretty much every server uses HTTPS, so if you don't include it explicitly, the browser assumes that is what you are using and adds it for you.
`developer.mozilla.org`: The domain name of the URL.
`/en-US/`: The path to the resource on the server that you are accessing.MDN keeps all its US English content in a folder called 'en-US', which is what this URL is pointing to.

## Knowledge Check
- What is a web server?
A web server is computer software and underlying hardware that accepts requests via HTTP or its secure variant HTTPS.
- What is a network?
A computer network is a collection of communicating computers and other devices, such as printers and smart phones.
- What is the Internet?
It is a wire burried in the ground.
- What is an IP address?
An Internet Protocol address is a numerical label such as 192.0.2.1 that is assigned to a device connected to a computer network that uses the Internet Protocol for communication.
- What is a router?
A router is a computer and networking device that forwards data packets between computer networks, including internetworks such as the global Internet. Routers perform the "traffic directing" functions on the Internet.
- What is an ISP?
An Internet service provider is an organization that provides a myriad of services related to accessing, using, managing, or participating in the Internet.
- What are packets and how are they used to transfer data?
They are small chunks. Basically, when data is sent acreoss the web, it is sent in thousands of small chunks called packets.
- What is a client?
Clients are the typical web user's internet-connected devices.
- What is a server?
Servers are computers that store webpages, sites, or apps.
- What is a web page?
An HTML document.
- What is a web browser?
A piece of software that retrieves and displays web pages. It is an application on computer.
- What is a search engine?
A web service that helps you find other web pages. It is like another web page.
- What is a DNS request?
A DNS query (also known as a DNS request) is a device's request to a Domain Name System (DNS) server to provide an IP address for a given hostname. By default, your router will send these requests to your internet service provider's (ISP) public DNS servers.
- Which browser are you currently using?
Firefox.
- In your own words, describe the process that takes place when you initiate a search on google.com in terms of what we discussed.
If I am looking for a website, first my request goes to DNS server to find the actual address (IP adress of the website). If answered success 200 OK from the website, it downloads me a copy of that website.
