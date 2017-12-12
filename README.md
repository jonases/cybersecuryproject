# cybersecuryproject

- How to build and run

Before building the code, you need to set the following environment variables:

`CLOUDANT_USER_NAME` is the Cloudant database user name

`CLOUDANT_PASSWORD` is the password for the Cloudant database

`export CLOUDANT_USER_NAME=myusername`

`export CLOUDANT_PASSWORD=mypassword`

Edit `main.go`, and set `Secure` flag session cookie to `false`

then ...

1. `go build`

2. `./cybersecuryproject`
