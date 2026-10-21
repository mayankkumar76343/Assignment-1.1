Assignment 1.1 — How a Website Works

A website opens on the screen through the interaction of a browser, client, server, and database. When a user types a URL (Uniform Resource Locator) into a browser such as Google Chrome, the browser finds the server’s IP address using DNS and sends an HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure) request to the web server. HTTP is used to transfer data between a browser and a server, while HTTPS provides a secure, encrypted connection. The server processes the request, communicates with a database if necessary, and sends an HTTP response containing HTML, CSS, JavaScript, images, and other resources. The browser then interprets these resources and displays the website on the screen. This process is called the request-response cycle. A client is the device or application that requests information, a server provides the requested resources, and a database stores and manages data. A static website displays fixed content that usually remains the same for every visitor, while a dynamic website can generate or update content based on user actions, database information, or other conditions. To inspect this process, open Google Chrome, visit any website, right-click the page, select Inspect, and open the Network tab. Reload the page to see the requests and responses, including resource types, status codes, and loading times.

Network Tab Screenshot
Open Google Chrome and visit https://example.com.
Right-click anywhere on the page and select Inspect.
Click the Network tab in DevTools.
Reload the page using Ctrl + R.
Observe the requests, status codes (such as 200), resource types, and loading times.
Take a screenshot showing the Network tab and its requests.
Save the screenshot as network-tab.png and include it with your assignment.

Conclusion: A website works through communication between a browser and a server using HTTP or HTTPS, and the browser displays the resources received in response to the request.