# Library for Jenkins

[![Build Status](http://github.dronehippie.de/api/badges/webhippie/go-jenkins/status.svg)](http://github.dronehippie.de/webhippie/go-jenkins)
[![Stories in Ready](https://badge.waffle.io/webhippie/go-jenkins.svg?label=ready&title=Ready)](http://waffle.io/webhippie/go-jenkins)
[![Join the Matrix chat at https://matrix.to/#/#webhippie:matrix.org](https://img.shields.io/badge/matrix-%23webhippie%3Amatrix.org-7bc9a4.svg)](https://matrix.to/#/#webhippie:matrix.org)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1755ee7dc16f4073a99841a26a5cf9b6)](https://www.codacy.com/app/webhippie/go-jenkins?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=webhippie/go-jenkins&amp;utm_campaign=Badge_Grade)
[![Go Doc](https://godoc.org/github.com/webhippie/go-jenkins?status.svg)](http://godoc.org/github.com/webhippie/go-jenkins)
[![Go Report](http://goreportcard.com/badge/github.com/webhippie/go-jenkins)](http://goreportcard.com/report/github.com/webhippie/go-jenkins)

This repository will provides helpers related to Jenkins.

## Development

Make sure you have a working Go environment, for further reference or a guide take a look at the [install instructions](http://golang.org/doc/install.html). This project requires Go >= v1.8. It is also possible to just simply execute the `go get github.com/webhippie/go-jenkins/...` command, but we prefer to use our `Makefile`:

```bash
go get -d github.com/webhippie/go-jenkins/...
cd $GOPATH/src/github.com/webhippie/go-jenkins
make retool sync clean generate test
```

## Examples

### Dummy

[embedmd]:# (examples/dummy/main.go go)
```go
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Dummy")
}
```

## Security

If you find a security issue please contact thomas@webhippie.de first.

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

* [Thomas Boerger](https://github.com/tboerger)

## License

Apache-2.0

## Copyright

```console
Copyright (c) 2018 Thomas Boerger <thomas@webhippie.de>
```
