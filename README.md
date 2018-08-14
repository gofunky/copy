# copy

[![Build Status](https://travis-ci.com/gofunky/copy.svg?branch=master)](https://travis-ci.com/gofunky/copy)
[![GoDoc](https://godoc.org/github.com/gofunky/copy?status.svg)](https://godoc.org/github.com/gofunky/copy)
[![Go Report Card](https://goreportcard.com/badge/github.com/gofunky/copy)](https://goreportcard.com/report/github.com/gofunky/copy)
[![codecov](https://codecov.io/gh/gofunky/copy/branch/master/graph/badge.svg)](https://codecov.io/gh/gofunky/copy)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c098f83f1d524464adee9f8b6968bab6)](https://app.codacy.com/app/gofunky/copy?utm_source=github.com&utm_medium=referral&utm_content=gofunky/copy&utm_campaign=badger)

`copy` copies directories recursively.

Example:

```go
err := copy.Copy("your/directory", "your/directory.copy")
```
