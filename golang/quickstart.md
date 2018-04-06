# Hello world

```go
/*
 helloworld.go
 经典演示程序
 在Go语言中，package 总是首先出现，然后是 import，然后是其他所有内容。当 Go 程序在执行的时候，首先调用的函数是 main.main()
*/
package main //所有的 Go 文件以 package开头，对于独立运行的执行文件必须是 package main
import "fmt" //将 实现格式化的I/O包 fmt 加入 main。不是 main 的其他包都被称为库
func main() { //定义了main函数
    fmt.Println("hello world")
}
```

# 编译和运行代码
```
$ go run helloworld.go
$ go build helloworld.go

```
go run直接运行
go build编译出可执行文件
