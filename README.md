btcutil
=======

[![Build Status](http://img.shields.io/travis/litecoinfinance/btcutil.svg)](https://travis-ci.org/litecoinfinance/btcutil)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/litecoinfinance/btcutil)

Package btcutil provides bitcoin-specific convenience functions and types.
A comprehensive suite of tests is provided to ensure proper functionality.  See
`test_coverage.txt` for the gocov coverage report.  Alternatively, if you are
running a POSIX OS, you can run the `cov_report.sh` script for a real-time
report.

This package was developed for btcd, an alternative full-node implementation of
bitcoin which is under active development by Conformal.  Although it was
primarily written for btcd, this package has intentionally been designed so it
can be used as a standalone package for any projects needing the functionality
provided.

## Installation and Updating

```bash
$ go get -u github.com/litecoinfinance/btcutil
```
## License

Package btcutil is licensed under the [copyfree](http://copyfree.org) ISC
License.
