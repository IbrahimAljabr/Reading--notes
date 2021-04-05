
## Read 7

# Bearer Authorization

### the correct order:
- Register your application to get a client_id and client_secret.
- Ask the client if they want to sign in via a third party.
- Redirect to a third party authentication endpoint.
- Make a request to the third-party API endpoint.
- Receive authorization code.
- Make a request to the access token endpoint.
- Receive access token.

### What can you do with an authorization code?

you can do with the authorization code is to make a request to get an access token.

### What can you do with an access token?

Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a 
specific application to access specific parts of a user's data

### What’s a benefit of using OAuth instead of your own basic authentication?

More specifically, OAuth is a standard that apps can use to provide client applications with “secure delegated access”. OAuth works over HTTPS and authorizes 
devices, APIs, servers, and applications with access tokens rather than credentials.


## Term

### Client ID
The client_id is a public identifier for apps. Even though it's public, it's best that it isn't guessable by third parties, so many implementations use something like a 32-character hex string.

### Client Secret
Client Secret (OAuth 2.0 client_secret) is a secret used by the OAuth Client to Authenticate to the Authorization Server. The Client Secret is a secret known only to the OAuth Client and the Authorization Server

### Authentication Endpoint
The Authentication API enables you to manage all aspects of user identity when you use Auth0. It offers endpoints so your users can log in, sign up, log out, access APIs, and more.

### Access Token Endpoint

The /oauth2/token endpoint only supports HTTPS POST. The user pool client makes requests to this endpoint directly and not through the system browser. 

### API Endpoint
An API endpoint is a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program. APIs work by 
sending requests for information from a web application or web server and receiving a response.

### Authorization Code

The authorization code is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting

### Access Token
An access token is an object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity.



