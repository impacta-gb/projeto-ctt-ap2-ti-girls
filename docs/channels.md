# Channels

Channels permitem comunicação entre goroutines.

## Exemplo

```go
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

## Explicação

- channels enviam dados entre goroutines
- `<-` envia e recebe valores