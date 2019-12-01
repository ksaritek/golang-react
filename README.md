# Golang app with the Gin & React & Auth0 + JWT

## Setup
* [Sign up](https://auth0.com) for an account for free if you don't have one.
* create an API first
* create an application
* Run `mv .env.sample .env` and update with valid credentials
* Update the `.env` file with your Auth0 Credentials.
    * AUTH0_CLIENT_ID
    * AUTH0_DOMAIN
    * AUTH0_API_AUDIENCE
* Update the `views/app.jsx` file with your Auth0 Credentials.
    * AUTH0_CLIENT_ID
    * AUTH0_DOMAIN
    * AUTH0_API_AUDIENCE
* Add `http://localhost:3000` to your Allowed Callback, and Allowed Logout URL's in your [Auth0 Management Dashboard](https://manage.auth0.com).

* Source the environment variables - `source .env`
* Launch the application by running `go run main.go`
* Navigate to `localhost:3000` to view the application

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
