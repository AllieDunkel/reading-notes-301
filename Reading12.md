### Status Codes Based On REST Methods

1-5. In your own words, describe what each group of status code represents:

1. 100’s = they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

2. 200’s = They tell the client that its request was accepted

3. 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore

4. 400’s = They are all about invalid requests a client sent to a server.

5. 500’s = Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

6. What is a status code 202?
This code tells the client that the request was valid, but its processing will finish sometime in the future.

7. What is a status code 308?
 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. 

8. What code would you use if an update didn’t return data to a client?
code 204

9. What code would you use if a resource used to exist but no longer does?
code 204

10. What is the ‘Forbidden’ status code?
code 403

### Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
so other people cant see it

2. What is middleware?
functions that have access to the request object, the response object, and the next function in the application's request-response cycle.

3. What does app.use(express.json()) do?
parses incoming JSON requests and puts the parsed data in req

4. What does the /:id mean in a route?
is the path that gets you to this function

5. What is the difference between PUT and PATCH?
 PUT handles updates by replacing the entire entity, while PATCH only updates the fields that you give it. PATCH does not change any of the other values. If you use the PUT method, then everything will get updated


6. How do you make a default value in a schema?
If you create a new document without that path set, the default will kick in.

7. What does a 500 error status code mean?
the server encountered an unexpected condition that prevented it from fulfilling the request

8. What is the difference between a status 200 and a status 201?
200= received and understood(most common)
201= request was successful and as a result, a resource has been created 