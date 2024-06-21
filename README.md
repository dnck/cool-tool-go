# cool-tool-go 

A simple Golang module to test some ideas about how the checksumdb works, and the security features of Go modules in general. 

Currently usage of this module should result in a security error because the checksum will not match what is in sum.golang.org:

- https://sum.golang.org/lookup/github.com/dnck/cool-tool-go/v2@v2.0.1

This is because I force pushed a commit over the v2.0.1 tag.


