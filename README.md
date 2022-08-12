# # JWT Json Web Token

->token used for 
JSON Web Token or JWT, as it is more commonly called, is an open Internet standard (RFC 7519) for securely transmitting trusted information between parties in a compact way.
	1. Authentication - security 1st part. if user is a valid user
	2. Authorization - check what all access the valid user is having, what permissions present for accessing a resource
->The tokens contain claims that are encoded as a JSON object and are digitally signed using a private secret or a public key/private key pair. 

-> They offer a lot of advantages over session management using in-memory random tokens. 

-> A JWT token is divided into 3 parts namely – header, payload, and signature in the format of

[Header].[Payload].[Signature]

-> Header − The Header of a JWT token contains the list cryptographic operations that are applied to the JWT. This can be the signing technique, metadata information about the content-type and so on.

-> Payload − The payload part of JWT contains the actual data to be transferred using the token.

-> Signature− The signature part of the JWT is used for the verification that the message wasn’t changed along the way. If the tokens are signed with private key, it also verifies that the sender is who it says it is.


->spring security + spring web
-
->angular/postman first hit generate token to generate token rest call for authorization/authentication
->/welcome - api to be accessed if the user is having valid access

-> Header - in postman select Authorization and then type Bearer hhgasads448665
Authorization Bearer 23546789fhghgjgh
