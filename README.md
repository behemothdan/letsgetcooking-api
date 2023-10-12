# GRANDstack Starter - GraphQL API


## Quick Start

Install dependencies:

```
npm install
```

Start the GraphQL service:

```
npm start
```

This will start the GraphQL service (by default on localhost:4000) where you can issue GraphQL requests or access GraphQL Playground in the browser:

![GraphQL Playground](img/graphql-playground.png)

## Configure

Set your Neo4j connection string and credentials in `.env`. For example:

*.env*

```
NEO4J_URI_LOCAL=bolt://localhost:7687
NEO4J_USER_LOCAL=neo4j
NEO4J_PASSWORD_LOCAL=letmein

NEO4J_URI_PRODUCTION=bolt://myurltosomehostlikeamazon.com:7687
NEO4J_USER_PRODUCTION=neo4j
NEO4J_PASSWORD_PRODUCTION=supersecretpasswordgoeshere
GRAPHQL_URI_PRODUCTION=https://myurltosomehostlikeamazon.com/graphql
```

Sample User Data Shape:

{accessToken: "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx", idToken: "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx", idTokenPayload: {…}, appState: null, refreshToken: null, …}
accessToken: "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
appState: null
expiresIn: 7200
idToken: "eyJxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
idTokenPayload:
at_hash: "ogsgfdsjfghjfdgsqZwg"
aud: "0gFgasdfgxxxxxxxxxxslXISlvb6wGrO"
email: "gray.daniel@gmail.com"
email_verified: true
exp: 1536253986
family_name: "Gray"
gender: "male"
given_name: "Daniel"
iat: 1xxxxxxxxxxxxxx6
iss: "https://letsgetcooking.auth0.com/"
locale: "en"
name: "BehemothDan"
nickname: "behemothdan"
nonce: "XRtmagP4YVY1xxxxxxxxxxxxxxxxxdNZ7LpXit56"
picture: "https://lh6.googleusercontent.com/-h695sfcceSE/AAAAAAAAAAI/AAAAAAAAF1Y/b03905L_QFU/photo.jpg"
sub: "google-oauth2|114xxxxxxxxxxxxxxxxxxx59"
updated_at: "2025-09-06T07:13:02.432Z"
__proto__: Object
refreshToken: null
scope: "openid profile email"
state: "1BafdsfasdfasdfjlH~CnL"
tokenType: "Bearer"
__proto__:
