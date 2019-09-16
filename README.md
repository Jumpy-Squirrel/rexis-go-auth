# rexis-go-attendee

## Overview

A backend service that provides authentification and limited authorization functionality.

Implemented in go.

Command line arguments
```-config <path-to-config-file>```

## Installation

```
go get github.com/dgrijalva/jwt-go
go get github.com/go-session/session
go get gopkg.in/oauth2.v3
go get github.com/tidwall/buntdb
go get gopkg.in/yaml.v2
go get github.com/gorilla/mux
go get github.com/go-http-utils/headers
go get github.com/jinzhu/gorm
go get github.com/go-sql-driver/mysql
go get github.com/stretchr/testify
go get -d github.com/pact-foundation/pact-go
```

THIS IS A VERY EARLY WORK IN PROGRESS

## Examples

try out pw flow:

```
curl -X POST -d "client_id=000000&client_secret=999999&grant_type=password&username=admin&password=123456" \
     http://localhost:9096/token
```

for login form try in browser: http://localhost:9096/login

## Documentation 

Based on this oauth2 implementation

https://github.com/go-oauth2/oauth2
