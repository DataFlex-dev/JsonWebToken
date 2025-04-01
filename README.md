# Json Web Token Library
This is a simple library for creating and verifying JSON Web Tokens (JWTs) in DataFlex. It has built-in support for different cryptographic backends and algorithms, making it easy to use in a variety of applications. The library is designed to be easy to use and understand.

The cool thing is that the cJsonWebToken class is a subclass of cJsonObject, which means you can use it as a regular JSON object. This allows you to easily manipulate the payload and headers of the JWT using the built-in methods of cJsonObject.

## Features
- Create and verify JWTs using different algorithms (HS256, RS256, etc.)
- Support for different cryptographic backends.
- Easy to use and understand API
- Built-in support for manipulating JWT payloads and headers using cJsonObject methods.
- Support for custom claims and headers
- Support for expiration and not before claims
- Support for audience and issuer claims
- Support for custom signing and verification methods

This library is based on l8w8jwt2 https://github.com/GlitchedPolygons/l8w8jwt