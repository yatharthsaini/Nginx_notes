// this repo covers the learning about the basics of Apache Nginx by Piyush Garg 

Engine-X
Definition: it is a powerful web server that used non threaded and event driven architecture
Uses : w.r.t to web architecture are : a. Load balancing, b. Http caching and c. reverse proxy 



![nginx-reverse-proxy](https://github.com/yatharthsaini/Nginx_notes/assets/88713642/539874fe-f0ad-4470-a890-2c6640b385a6)


Reverse proxy : there's no direct access given to the user to get the response from the servers but instead it interacts with the nginx server that acts a middleware between the request response mechanism and also acts as an API gateway.

For example we have 5 servers : we can allot every server some load and while continous allotement of requests on the servers via round robin algo we avoid giving the request to the server that is already loaded heavily and therefore we use the nginx which also acts a load balancer for requests 

Also http caching can be done that is response gets stored in the cache so in case of multiple same requests it can fetch the response from the cache and in turn make the request response cycle even faster.

More advantages of nginx :

1. Can handle 10k concurrent requests
2. Cache HTTP requests
3. Acts a reverse proxy
4. It can also act as a load balancer
5. Act as an API Gateway
6. Serve and cache static files like images and videos
7. Handle SSL Certificates that are required for getting that "This connection is secure" on the website 
