# Web-Development-Notes

## Clients and Servers:
- Client: are the web user's devices (eg. phone)
- Server: are computers that store webpages, sites, or apps
When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.


## Key Components of the Web
- **Internet connection**: 
  - Allows you to send and receive data on the web. 
  - Analogy: It's like the street between your house and the shop.
- **TCP/IP**: 
  - Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the web.
  - Analogy: This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. In our example, this is like a car or a bike (or however else you might get around).
- **DNS**: 
  - Doman Name Servers - translate IP addresses like `63.245.215.20` to human readable text like "www.google.com" 
  - Find the real IP of a website through [IP Checker](https://ipinfo.info/html/ip_checker.php)
  - Analogy: This is like looking up the address of the shop so you can access it.
- **HTTP**: 
  - Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other.
  - Analogy: This is like the language you use to order your goods.
- **Component files**: 
  - A website is made up of many different files and they come in two main types:
    - **Code files**: Websites are built primarily from HTML, CSS, and JavaScript.
    - **Assets**: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.
- **Packets**:
  - Data is sent from the server to the client in small chunks
  - This is to allow many different users to download the website at the same time

## Overall Process 
1. Browser goes to DNS server and find the real IP address that website lives on
2. Browser sends an HTTP request message to the server, asking it to send a copy of the website to the client
3. The message and all data is sent between the client and server across your internet connection using TCP/IP
4. If the server approves client request - server sends a "200 OK" message and then starts sending the website's files to the browser via packets
5. Browser asembels the packets into a complete website and displays it
