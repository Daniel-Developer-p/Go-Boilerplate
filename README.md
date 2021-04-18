# http-boilerplate

An example of a reasonably complex web server in Go.

## What's Included

This is a boilerplate application designed to show how to build web applications in Go. The following features are already set up:

* HTTPS through Let's Encrypt
* An API subrouter
* A demo of authentication middleware
* Static file serving
* Graceful shutdown

This application largely uses the standard library. Routing is provided by the `go-chi/chi` package, and Let's Encrypt functionality is provided by the `autocert` package.

## Usage

To start using this library, it's recommend to fork this repository. Then, you can update the import paths to point to your local copy.

##

More information in documentat