[![Build Status](https://app.travis-ci.com/xenking/bytebufferpool.svg?branch=master)](https://app.travis-ci.com/xenking/bytebufferpool)
[![Go Reference](https://pkg.go.dev/badge/github.com/xenking/bytebufferpool.svg)](https://pkg.go.dev/github.com/xenking/bytebufferpool)
[![Go Report Card](https://goreportcard.com/badge/github.com/xenking/bytebufferpool)](https://goreportcard.com/report/github.com/xenking/bytebufferpool)
[![codecov](https://codecov.io/gh/xenking/bytebufferpool/branch/master/graph/badge.svg?token=WH2SGawBHl)](https://codecov.io/gh/xenking/bytebufferpool)

# bytebufferpool

An implementation of a pool of byte buffers with anti-memory-waste protection.

The pool may waste limited amount of memory due to fragmentation.
This amount equals to the maximum total size of the byte buffers
in concurrent use.

# Benchmark results
Currently bytebufferpool is fastest and most effective buffer pool written in Go.

You can find results [here](https://omgnull.github.io/go-benchmark/buffer/).

# bytebufferpool users

* [fasthttp](https://github.com/valyala/fasthttp)
* [quicktemplate](https://github.com/valyala/quicktemplate)
