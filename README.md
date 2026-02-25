# go-module-template
[![go.dev reference](https://pkg.go.dev/badge/github.com/tinygo-org/tinygodoc)](https://pkg.go.dev/github.com/tinygo-org/tinygodoc)
[![Go Report Card](https://goreportcard.com/badge/github.com/tinygo-org/tinygodoc)](https://goreportcard.com/report/github.com/tinygo-org/tinygodoc)
[![codecov](https://codecov.io/gh/tinygo-org/tinygodoc/branch/main/graph/badge.svg)](https://codecov.io/gh/tinygo-org/tinygodoc)
[![Go](https://github.com/tinygo-org/tinygodoc/actions/workflows/go.yml/badge.svg)](https://github.com/tinygo-org/tinygodoc/actions/workflows/go.yml)
[![sourcegraph](https://sourcegraph.com/github.com/tinygo-org/tinygodoc/-/badge.svg)](https://sourcegraph.com/github.com/tinygo-org/tinygodoc?badge)
[![License: BSD-3](https://img.shields.io/badge/License-BSD3-green.svg)](https://opensource.org/license/bsd-3-clause-open-mpi)

To run with tinygo in the same folder as tinygodoc:
```
go run ./cmd/tgdoc -http=:18080 ../tinygo/targets ../tinygo/src/machine 
```