# Symbolizer

[![Build Status](https://travis-ci.org/Didstopia/symbolizer.svg?branch=master)](https://travis-ci.org/Didstopia/symbolizer)
[![codecov](https://codecov.io/gh/Didstopia/symbolizer/branch/master/graph/badge.svg)](https://codecov.io/gh/Didstopia/symbolizer)

A modern crash log symbolication utility for iOS, watchOS, tvOS and macOS.

**NOTE: _Work in progress._**

## Usage

_To be implemented._

## Development

Install dependencies:

```sh
go get -t -v ./...
go get github.com/golang/lint/golint
go get github.com/goreleaser/goreleaser
```

---

Build binaries:

```sh
touch CHANGELOG.md
goreleaser --snapshot --rm-dist
```

## License

See [LICENSE.txt](LICENSE.txt).

## Stargazers

[![Stargazers](https://starcharts.herokuapp.com/Didstopia/symbolizer.svg)](https://starcharts.herokuapp.com/Didstopia/symbolizer)
