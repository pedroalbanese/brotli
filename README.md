# brotli
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/brotli/blob/master/LICENSE) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/brotli?status.png)](http://godoc.org/github.com/pedroalbanese/brotli)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/brotli)](https://goreportcard.com/report/github.com/pedroalbanese/brotli)
### Brotli compression format library in Go:
This package is a brotli compressor and decompressor implemented in Go.
It was translated from the reference implementation (https://github.com/google/brotli)

### Command:
<pre>Usage: brotli [OPTION]... [FILE]
Compress or uncompress FILE (by default, compress FILE in-place).

  -c    write on standard output, keep original files unchanged
  -d    decompress; see also -c and -k
  -f    force overwrite of output file
  -h    print this help message
  -k    keep original files unchaned
  -s string
        use provided suffix on compressed files (default "brotli")

With no FILE, or when FILE is -, read standard input.</pre>

## License

This project is licensed under the MIT License.

##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Research Lab.
