# dosa [![GoDoc][doc-img]][doc] [![Build Status][ci-img]][ci] [![Coverage Status][cov-img]][cov]

[dosa][dosa-spec] is a library that provides a distributed
object storage abstraction for applications in golang and
java. It's designed to help with storage discovery and
abstract the underlying database system.

If you'd like to start by writing a small DOSA-enabled
program, check out [the guide][guide/DOSA.md].

## Overview

DOSA is a storage library that supports:

 * methods to store and retrieve go structs
 * struct annotations to describe queries against data
 * tools to create and/or migrate database schemas
 * implementations that serialize requests to remote stateless servers

## Annotations

<hr>
This project is released under the [MIT License](LICENSE.md).

[doc-img]: https://godoc.org/github.com/uber/dosa-go?status.svg
[doc]: https://godoc.org/github.com/uber/dosa-go
[ci-img]: https://travis-ci.org/uber/dosa-go.svg?branch=master
[ci]: https://travis-ci.org/uber/dosa-go
[cov-img]: https://coveralls.io/repos/uber/dosa-go/badge.svg?branch=master&service=github
[cov]: https://coveralls.io/github/uber/dosa-go?branch=master