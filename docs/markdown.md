```
package main

import "fmt"

func main() {

    mensagem := make(chan string)

    go func() {
        mensagem <- "Olá"
    }()

    fmt.Println(<-mensagem)
}
```