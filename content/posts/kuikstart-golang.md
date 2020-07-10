+++
date = "2020-07-10T21:01:27+01:00"
draft = false
title = "kuikstart golang"
tags = [
    "linux",
    "golang",
]
+++
# Golang

according [the official golang website](https://golang.org/)  
The Go programming language is an **open source** project to make programmers more productive.
it makes it easy to build **simple**, **reliable**, and **efficient** software :blue_heart: .

## Install Golang on linux machine  

1 - go to the [official download page of Golang](https://golang.org/dl) and download it
2 - 
```bash
cd Downloads && tar -C /usr/local/ -xzf go*.tar.gz
```
3 - 
```bash
mkdir -p ~/go/{src,pkg,bin}
```
4 - apend this lines to your `~/.bashrc` file 
> export GOROOT=/usr/lib/go
> export GOPATH=$HOME/go
> export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

5 - 
```bash
source ~/.bashrc
```

6 - verify your installation 
```bash
go version
```

7 - write your first golang code and save it to main.go
```go
import "fmt"
func main(){
    fmt.Println("go kuikstart ! ")
}
```

8 - 
```bash
go run main.go
```
