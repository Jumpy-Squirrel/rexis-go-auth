# rexis-go-auth

## Overview

A backend service that provides authentification and limited authorization functionality.

Implemented in go.

THIS IS A VERY EARLY WORK IN PROGRESS

## Installation

Any dependencies will be downloaded by go build / go test, because this project uses 
[go modules](https://blog.golang.org/using-go-modules).

## Examples

Try out pw flow:

```
curl -X POST -d "client_id=000000&client_secret=999999&grant_type=password&username=admin&password=123456" \
     http://localhost:9096/token
```

For the sample login form try in browser: http://localhost:9096/login

## Documentation 

Based on this oauth2 implementation

https://github.com/go-oauth2/oauth2
