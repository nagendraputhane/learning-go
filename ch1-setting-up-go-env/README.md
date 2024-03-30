go mod init hello_world 
    to mark this directory as a Go module.
    Go project is called a module
Code is organized into one or more packages. maain package contains the code that starts a Go program.
package main

import "fmt"

func main() {
fmt.Println("Hello, world!")
}
go build
./hello_world -> binary name = module name
go fmt ./...
