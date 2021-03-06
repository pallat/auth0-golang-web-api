# Auth0 + Go Web API Sample

## Running the App

To run the sample, make sure you have **go** and **goget** installed.

Rename the `.env.example` file to `.env` and provide your Auth0 credentials.

```bash
# .env

AUTH0_CLIENT_ID={CLIENT_ID}
AUTH0_DOMAIN={DOMAIN}
AUTH0_CLIENT_SECRET={CLIENT_SECRET}
```

Once you've set your Auth0 credentials in the `.env` file, run `go get .` to install the Go dependencies.

Run `go run main.go` to start the app and send a `GET` request to [http://localhost:3001/ping](http://localhost:3001/ping) to access an **unsecured** endpoint, or [http://localhost:3001/secured/ping](http://localhost:3001/secured/ping) to access a **secured** endpoint.
