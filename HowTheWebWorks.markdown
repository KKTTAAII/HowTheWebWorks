Part One
1. What is HTTP? : It is one of the protocol. It's a set of rules or the standards how we communicate between server and browser.
2. What is a URL? : It is the address of a site that consists of protocal, hostnames, port, resource and query(optional). The address can be accessible by the Internet.
3. What is DNS?: This is like a universal phone book that can translate the hostnames into IP Addresses.
4. What is a query string?: It is like an inquiry that the user puts in. It comes in form of a key:value pair.
5. What are two HTTP verbs and how are they different?
  5.1 GET: requests with no side effects like clicking links, search something etc
  5.2 POST: requests with side effects like posting a post on Facebook
6. What is an HTTP request?: a request we perform on a resource URL we want
7. What is an HTTP response?: a response we get from a server when we make a request
8. What is an HTTP header? Give a couple examples of request and response headers you have seen. : HTTP header includes the meta data of the URL we make a request. For example, content types, date, time, 
9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser? : The browser sends a request to the server and the server sends back the resource to the browser, the browser gather all the requests in that one request and renders the page to the user.

Part Two
1. ktai@DESKTOP-KODCRHE:~$ curl http://icanhazdadjoke.com/search?term=pirate
<a href="https://icanhazdadjoke.com/search?term=pirate">Moved Permanently</a>.
2.  dig icanhazdadjoke.com

; <<>> DiG 9.16.1-Ubuntu <<>> icanhazdadjoke.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 29778
;; flags: qr rd ad; QUERY: 1, ANSWER: 2, AUTHORITY: 0, ADDITIONAL: 0
;; WARNING: recursion requested but not available

;; QUESTION SECTION:
;icanhazdadjoke.com.            IN      A

;; ANSWER SECTION:
icanhazdadjoke.com.     0       IN      A       104.21.37.176
icanhazdadjoke.com.     0       IN      A       172.67.211.64

;; Query time: 0 msec
;; SERVER: 172.17.144.1#53(172.17.144.1)
;; WHEN: Sun Aug 08 13:27:29 MDT 2021
;; MSG SIZE  rcvd: 86

3. ktai@DESKTOP-KODCRHE:/mnt/c/Users/krata/OneDrive/เอกสาร/Spring Board/Career Track/All Projects/ConnectFour Project/conne
ct-four/connect-four$ python3 -m http.server
Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
127.0.0.1 - - [08/Aug/2021 13:38:16] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [08/Aug/2021 13:38:17] "GET /connect4.css HTTP/1.1" 200 -
127.0.0.1 - - [08/Aug/2021 13:38:17] "GET /connect4.js HTTP/1.1" 200 -
127.0.0.1 - - [08/Aug/2021 13:38:17] code 404, message File not found
127.0.0.1 - - [08/Aug/2021 13:38:17] "GET /favicon.ico HTTP/1.1" 404 -

http://127.0.0.1:8000/

Part Three