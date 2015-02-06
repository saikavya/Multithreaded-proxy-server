
     Development Environment : Eclipse
Instructions on how to run the code:
  Step 1: Copy the ProxyServer  project folder to the Eclipse workspace
  Step 2:Import this folder in Eclipse using the Import option. Then open the workspace.
  Step 3:There is a  .java file – ProxyServer.java.
             Run the ProxyServer.java ,It displays on the console that proxy server is listening to the requests from the browser.
            Open up the browser and give the URL 127.0.0.1:8080/www.amazon.com. The get method gives access to the 
             website by checking the cache. If the url is in the cache it will retrieve it from the cache or else the request is sent to 
             the original web server and the web page is read from the server. 
  Step 4: The post method retrieves the website  by giving the url of the uploading website with the local port number
            in the webbrowser. After retrieving the page If we click  the upload file button on the webpage it will give a message
          after sometime that it has been uploaded.This shows that the post method is working properly
  Step 5: Open another tab in the web browser and give address in the web browser such as 127.0.0.1:8080/www.yahoo.com
          the page is retrived from the server. This shows multithreading is also working

  Step 6: Stop the server after retriving the webpages
  


ExtraCredit: Cache is also working on this ProxyServer.java file

REFERENCES:
1.http://www.jtmelton.com/2007/11/27/a-simple-multi-threaded-java-http-proxy-server/
2.http://www.w3.org/Protocols/rfc2616/rfc2616.html: HTTP/1.1 specification
3.J. Kurose and K. Ross, “Computer Networking: A Top-Down Approach,” 6th edition,
chapter 2, section 2.2, 2.7: HTTP message format, Web caching, and Socket
programming.
