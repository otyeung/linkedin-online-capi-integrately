# linkedin-online-capi-integrately

## Start Server indpendently

Server runs on port 4000 locally. Open terminal in your apps directory, run

```
cd server
npm i
npm start
```

## Start Client indpendently

Modify REACT_APP_SERVER_URL in "server/.env", default is "http://localhost:4000"
Client runs on port 3000.
Open terminal in your apps directory, run

```
cd client
npm i
npm start
```

## Start Server & Client at the same time

```
cd client
npm i
npm run start:dev
```
