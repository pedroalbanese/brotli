# brotli
[![ISC License](http://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/pedroalbanese/brotli/blob/master/LICENSE) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/brotli?status.png)](http://godoc.org/github.com/pedroalbanese/brotli)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/brotli)](https://goreportcard.com/report/github.com/pedroalbanese/brotli)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/brotli)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/brotli)](https://github.com/pedroalbanese/brotli/releases)
### Brotli compression format library in Go:
This package is a brotli compressor and decompressor implemented in Go.
It was translated from the reference implementation (https://github.com/google/brotli)

### Command:
<pre>Usage: brotli [OPTION]... [FILE]
Compress or uncompress FILE (by default, compress FILE in-place).

  -c    write on standard output, keep original files unchanged
  -cores int
        number of cores to use for parallelization (default 1)
  -d    decompress; see also -c and -k
  -f    force overwrite of output file
  -h    print this help message
  -k    keep original files unchanged
  -s string
        use provided suffix on compressed files (default "brotli")

With no FILE, or when FILE is -, read standard input.</pre>

## License

This project is licensed under the MIT License.

##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Research Lab.
