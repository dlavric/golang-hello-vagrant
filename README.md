# Go language script that prints hello

## Prerequisites
- [X] [Vagrant](https://www.vagrantup.com/downloads)

## How to use this Repository

- Clone this repo:
```shell
$ git clone
```

- Go to the directory of the repo:
```shell
$ cd golang-hello-vagrant
```

- Start Vagrant:
```shell
$ vagrant up
```

- Access the VM:
```shell
$ vagrant ssh
```

- Create the Go script that prints hello:
```shell
$ touch main.go
```

```shell
$ nano main.go
```

```golang
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

- Compile the Go code: 
```golang
$ go tool compile main.go
```

- Run the script:
```golang
$ go run main.go
```

- Logout of the VM:
```shell
$ logout
```

- When finished, destroy the Vagrant machine
```shell
$ vagrant destroy
```
