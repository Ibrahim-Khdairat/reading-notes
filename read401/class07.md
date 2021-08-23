# READ 06 : Bearer Authorization

#### 1- Write the following steps in the correct order

1.Register your application to get a client_id and client_secret

2.Ask the client if they want to sign in via a third party

3.Make a request to a third-party API endpoint

4.Redirect to a third party authentication endpoint

5.Make a request to the access token endpoint

6.Receive access token

7.Receive authorization code

#### 2- What can you do with an authorization code?
An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

#### 3- What can you do with an access token?
Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.

#### 4- What’s a benefit of using OAuth instead of your own basic authentication?
It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities.

### Document the following Vocabulary Terms.
* **Client ID** :  The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles.

* **Client Secret** : The client_secret is a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable, which means you should avoid using common UUID libraries which often take into account the timestamp or MAC address of the server generating it.

* **Authentication Endpoint** : Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service. The approach is also known as device authentication.

* **Access Token Endpoint** : The /oauth/token endpoint is used by the application in order to get an access token or a refresh token. It is used by all flows except for the Implicit Flow because in that case an access token is issued directly.

* **API Endpoint** : an endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service.

* **Authorization Code** : The EPP code, which other registrars may refer to as the Authorization or Auth code, is essentially a unique password for the domain, made up of letters, numbers, and special characters. It’s used to prove your ownership of the domain and authorize a domain transfer.

* **Access Token** : An access token is an object that describes the security context of a process or thread. The information in a token includes the identity and privileges of the user account associated with the process or thread. When a user logs on, the system verifies the user’s password by comparing it with information stored in a security database.

