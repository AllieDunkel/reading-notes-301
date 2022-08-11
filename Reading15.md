### Reading: What is OAuth

1. What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single log on credential.

2. Give an example of what using OAuth would look like.
An example would be ypu go to a website and it lets you sign in with your google account

3. How does OAuth work? What are the steps that it takes to authenticate the user?
a. The first website connects to the second website on behalf of the user
b. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
c. The first site gives this token and secret to the initiating user’s client software.
d. The client’s software presents the request token and secret to their authorization provider
e. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
f. The user approves a particular transaction type at the first website.
g. The user is given an approved access token 
h. The user gives the approved access token to the first website.
i. The first website gives the access token to the second website as proof of authentication on behalf of the user.
j. The second website lets the first website access their site on behalf of the user.
k. The user sees a successfully completed transaction occurring.

4. What is OpenID?
allows you to use an existing account to sign in to multiple websites, without needing to create new passwords 

### Authorization and Authentication flows

1. What is the difference between authorization and authentication?
Authorization is the process of letting a subject access resources after a successful authentication, oftentimes somewhere else. 
Authentication is the process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor. 

2. What is Authorization Code Flow?
it exchanges an Authorization Code for a token. 

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security so they use PKCE

4. What is Implicit Flow with Form Post?
alternative to the Authorization Code Flow- 
It is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.

5. What is Client Credentials Flow?
It occurs when they pass along their Client ID and Client Secret to authenticate themselves and get a token.

6. What is Device Authorization Flow?
It occurs when the device asks the user to go to a link on their computer or smartphone and authorize the device

7. What is Resource Owner Password Flow?
Requests that users provide credentials like username and password- but it is not recommended 
