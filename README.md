# template-go

## Synopsis

The template-go repository serves as a starting point for new repositories hosting Go code.
It also shows best practices that can be retro-fitted into existing repositories hosting Go code.

[![Go Reference](https://pkg.go.dev/badge/github.com/senzing/template-go.svg)](https://pkg.go.dev/github.com/senzing/template-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/senzing/template-go)](https://goreportcard.com/report/github.com/senzing/template-go)
[![go-test.yaml](https://github.com/Senzing/template-go/actions/workflows/go-test.yaml/badge.svg)](https://github.com/Senzing/template-go/actions/workflows/go-test.yaml)
[![License][license-image]][license-url]

[license-url]: https://github.com/Senzing/template-go/blob/main/LICENSE
[license-image]: https://img.shields.io/badge/License-Apache2-brightgreen.svg

## Overview

Aspects of the template-go repository:

1. **Badges:** Example badges can be seen above.
1. **Makefile:** Simplifies development lifecycle commands.
1. **Sample code:** `main.go` and `examplepackage` code examples.
1. **Sample test cases:** `*_test.go` files showing how to write and document test cases.
1. **Sample documentation:** Documentation style conducive to the [Go Package library](https://pkg.go.dev).
1. **Dockerfile:** Containerizing the Go program.
1. **RPM/DEB builds:** Using `package.Dockerfile` to build `RPM` and `DEB` files for installation.
1. **.github/workflows:** GitActions tailored to Go programming.
1. **.github/dependabot.yml** Specifications for keeping Go dependencies up-to-date.

## Use

(TODO:)

## References

1. [API documentation](https://pkg.go.dev/github.com/senzing/template-go)
1. [Development](docs/development.md)
1. [Errors](docs/errors.md)
1. [Examples](docs/examples.md)
1. Related artifacts:
    1. [DockerHub](https://hub.docker.com/r/senzing/template-go)
    1. [Helm Chart](https://github.com/Senzing/charts/tree/main/charts/template-go)
