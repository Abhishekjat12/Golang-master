This repository contains a collection of Go programs and libraries that demonstrate the language, standard libraries, and tools.

Clone the project
$ git clone https://go.googlesource.com/example
$ cd example
https://go.googlesource.com/example is the canonical Git repository. It is mirrored at https://github.com/golang/example.

hello and hello/reverse
$ cd hello
$ go build
$ ./hello -help
A trivial "Hello, world" program that uses a library package.

The hello command covers:

The basic form of an executable command
Importing packages (from the standard library and the local repository)
Printing strings (fmt)
Command-line flags (flag)
Logging (log)
The reverse reverse covers:

The basic form of a library
Conversion between string and []rune
Table-driven unit tests (testing)
helloserver
$ cd helloserver
$ go run .
A trivial "Hello, world" web server.

Topics covered:

Command-line flags (flag)
Logging (log)
Web servers (net/http)
outyet
$ cd outyet
$ go run .
A web server that answers the question: "Is Go 1.x out yet?"

Topics covered:

Command-line flags (flag)
Web servers (net/http)
HTML Templates (html/template)
Logging (log)
Long-running background processes
Synchronizing data access between goroutines (sync)
Exporting server state for monitoring (expvar)
Unit and integration tests (testing)
Dependency injection
Time (time)
appengine-hello
A trivial "Hello, world" App Engine application intended to be used as the starting point for your own code. Please see Google App Engine SDK for Go and Quickstart for Go in the App Engine Standard Environment.

gotypes
The go/types package is a type-checker for Go programs. It is one of the most complex packages in Go's standard library, so we have provided this tutorial to help you find your bearings. It comes with several example programs that you can obtain using go get and play with as you learn to build tools that analyze or manipulate Go programs.

template
A trivial web server that demonstrates the use of the template package's block feature.

slog-handler-guide
The log/slog package supports structured logging. It features a flexible backend in the form of a Handler interface. This guide can help you write your own handler.
