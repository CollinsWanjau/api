# REST API

* An acroynm for Representational State Transfer.

## Constraints for RESTFUL web services

* Client-Server.
* Stateless -> the client request should contain all the information necessary
to respond. In other words, it should be possible to make two or more
HTTP requests in any order and the same responses will be received.
* Cacheable -> Caching improves perfomance bec, it's not necessary to
regenerate a response for the same URL.
* Layered -> The requesting client need not know whether it's communicating
with the actual server, a proxy, etc.

## Creating a RESTFUL Web Service

1. An Endpoint URL -> An application implementing a RESTFUL API will define
one or more URL endpoints with a domain, port, path and/or query string.

2. The HTTP method

3. HTTP headers.

4. Body Data -> Data is normally transmitted in the HTTP body in an identical
way to HTML submissions or by sending a single JSON encoded

# QUERY STRING

* A query string is a part of a URL that assigns values to specified parameters
A query string commonly includes fields added to a base URL by a web browser
or other client application.

## Structure

* A typical URL containing a query string is as follows:

```
https://example.com/over/there?name=ferret
```

* When a server receives a request for such a page, it may run a pragram,
passing the query string, which is in this case is `name=ferret`, unchanged
to the program.

* The `?` is used as  a separator, and it's not part of the query string.
