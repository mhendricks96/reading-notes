# Bearer Authoriztaion

- With an authorization code, the client can exchange that code for an access token.

- with an access token is how a user makes request from an api server. this way the server can easily confirm their identity every time.

- OAth allows users to not have to ever remember different passwords for different places. Also the server never actually controlls their information

## Terms

- Client ID: a unique ID used to confirm identity.

- Client Secret: a secret known only to the application and the authorization server.

- Authentication Endpoint: is designed to ensure that only authorized devices can connect

- Access Token Endpoint: where app can make a request to get an access token for a user.

- API endpoint: The communication/exchange of information point between the client and the server.

- Authorization Code: the code that the authorization endpoint uses to determine what permissions a given client has

- Acces Token: Used by client to make api requests once permission has been granted
