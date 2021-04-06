## Read 8

# Access Control (ACL)

### When is Basic Authorization used vs. Bearer Authorization?

The Basic authentication are dedicated to the authentication using a username and a secret. The Bearer authentication is 
dedicated to the authentication using a token

### What does the JSON Web Token package do?

JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely 
transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

### What considerations should we make when creating and storing a SECRET?

should be in the .env 

## Term

### encryption

 encryption is the process of encoding information. This process converts the original representation of the information, 
 known as plaintext, into an alternative form known as ciphertext. Ideally, only authorized parties can decipher a ciphertext back 
 to plaintext and access the original information.
 
 ### token
 server will validate the user details and generate a token which is sent as response to the users, and user store the token in client 
 side, so client do further HTTP call using this token which can be added to the header.
 
 ### bearer
 Bearer Tokens are the predominant type of access token used with OAuth 2.0. A Bearer Token is an opaque string, not intended to have 
 any meaning to clients using it. Some servers will issue tokens that are a short string of hexadecimal characters, while others 
 may use structured tokens such as JSON Web Tokens.
 
 ### secret
 secret is a symmetric key that is known by both the sender and the receiver. It is negotiated and distributed out of band.
 
 ### JSON Web Token
 JSON Web Token is an Internet proposed standard for creating data with optional signature and/or optional encryption whose payload holds 
 JSON that asserts some number of claims.
 
 
## Preparation Materials

### RBAC (wiki)

In computer systems security, role-based access control or role-based security is an approach to restricting system access to 
authorized users. It is used by the majority of enterprises with more than 500 employees, and can implement mandatory access control or 
discretionary access control.

### 5 steps to RBAC

- Inventory your systems
- Analyze your workforce and create roles
- Assign people to roles
- Never make one-off changes
- Audit


















