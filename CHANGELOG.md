## 0.3.0 - 2018-02-05

* Added authentication metadata providers, optimized for use with Google Cloud.
* Added service URI to metadata provider API, needed for Json Web Token generation.
* Added authenticated cloud-to-prod interoperability tests.
* Refactored connection logic to throw initial connection errors early.

## 0.2.1 - 2018-01-18

* Updated generated code in examples using latest protoc compiler plugin.
* Dart 2.0 fixes.
* Changed license to Apache 2.0.

## 0.2.0 - 2017-12-15

* Implemented support for per-RPC metadata providers. This can be used for
  authentication providers which may need to obtain or refresh a token before
  the RPC is sent.

## 0.1.0 - 2017-10-12

* Core gRPC functionality is implemented and passes
[gRPC compliance tests](https://github.com/grpc/grpc/blob/master/doc/interop-test-descriptions.md).

The API is shaping up, but may still change as more advanced features are implemented.

## 0.0.1 - 2017-07-05

* Initial version.

This package is in a very early and experimental state. We do not recommend
using it for anything but experiments.
