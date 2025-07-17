1. client-server architecture
  client (web browser, mobile app) ----> request (store retrieve, update) ---> server

2. IP address
    when client sends req it must send to the correct ip address

3. Domain Name Systems (DNS)
    translates human readable-websites (like google.com) into the numerical IP address that computes  actually use to connect
    you can find any IP address by using ping

4. Proxy server/ reverse proxy
    a proxy server acts as the middle man between device and the internet,
    when you request a web page the proxy forwards request to server, 
    proxy hides ip

    a reverse proxy intercepts the client request and forwars them to backend server based on predifined rules

5. Latency
    time it takes for data to cover distance, 
    can make using apps feel slow and unresponsive

    CAN REDUCE LATENCY BY DEPLOYING ACROSS MULTIPLE DATA CENTERS WORLDWIDE
    THIS WAY USERS CAN CONNECT TO CLOSEST SERVER

6. HTTP / HTTPS
    protocol for tranferig text
    requiest body includes form data etc
    server processes that data and sends back http response
    response either has data or error message

    sends data in plain text
    https enxrypts the text

7. API Application program interface
    Client sends request to API
    API Processes the request then interacts with databases or oother services
    Sends back a Resoibse in a structured format, typically json

    Two main types of APIS are REST and GraphQL

8