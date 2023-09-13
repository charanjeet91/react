# Auth0 React SDK Sample Application

Install Node.js 

## Project setup

Use `yarn` to install the project dependencies:

```bash
yarn install
```
### In case you want to user your own Configure credentials, if you choose your own credentials, you will  need to create your own APP in auth0 and define Callback URL,Logout Url and weborigin to http://localhost:3000. This is for testing only.  

modify `src/auth_config.json`, 

{
  "domain": "{YOUR AUTH0 DOMAIN}",
  "clientId": "{YOUR AUTH0 CLIENT ID}",
  "audience": "{YOUR AUTH0 API_IDENTIFIER}",
}
```


## Run the sample


This compiles and serves the React app and starts the backend API server on port 3001.

```bash
yarn run dev
```


### Compiles and minifies for production

bash
yarn run build
