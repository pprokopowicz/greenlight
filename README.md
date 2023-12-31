[![Go 1.21](https://img.shields.io/badge/Go-1.21-blue?logo=go&color=4EA5CC)](https://golang.org/doc/go1.21)

# Greenlight

This project is a JSON API written in Go for retrieving and managing information about movies, created as part of [Let's Go Further by Alex Edwards](https://lets-go-further.alexedwards.net/).

You can also check out [Snippetbox](https://github.com/pprokopowicz/snippetbox), written as part of [Let's Go](https://lets-go.alexedwards.net/) book.

## Building

Before running this application add a `.envrc` file with keys:
- GREENLIGHT_DB_DSN
- SMTP_USERNAME
- SMTP_PASSWORD

You can use makefile to build and run this application. To get more information run `make help`.