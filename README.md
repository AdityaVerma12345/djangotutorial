Answers:-
<br> 1. Browser reads the url then go to dns which tells the browser the ip address of the website, and browser connects to website server and send it httprequest. Server recieves it, rusns some code and it sends back Httpresponse , and our browser takes it run some code and render it on our device.
<br> 2. client is a device or application that request services and server receives the request and provide services. they both communicate via http, sending and receiving these requests and responses.
<br> 3. HyperText Transfer Protocol is some set of rules through which server and client communicates. http response contains:- status like 200 or 404,headers and body. while http request contains:- request line with which it analyse what it needs, headers and body.
<br> 4. Get is used to take and read information whereas most is used to send data to the server for processing.
<br> 5. 200 - OK, 302 - found, 404 - Not found, 500 - internal server error.
<br> 6. HTML — structure and content, CSS — appearance and layout, JavaScript — behaviour and interaction.
<br> 7. It is due to cookies and sessions. server send some date to browser to store which it sends back to sever when you viv=sit that website again. session is a way of storing data of user in server which expires according to session settings.
<br> 8. first Django receives the request then check middleware, go to urls match the url then accordingly go to views then go to template if need then sends httpresponse. if needed it can go tp model.py to access database.
<br> 9. {% csrf_token %} is used to prevent Cross Site Request Forgeries, basically it authenticates if it was the user who voted not some other website as it can trick our browser and session cookie don't prevent that from happening.
<br> thanks that's it from my side. :)
