```go
package main

import (
    "fmt"
    "time"
)

func tarefa() {
    fmt.Println("Executando goroutine")
}

func main() {
    go tarefa()

    time.Sleep(time.Second)
}
```