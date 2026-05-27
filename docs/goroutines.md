# Goroutines em Go

Goroutines permitem executar funções simultaneamente.

```go
package main

import (
    "fmt"
    "time"
)

func mensagem() {
    fmt.Println("Executando goroutine")
}

func main() {

    go mensagem()

    time.Sleep(time.Second)
}
```

## Explicação

- `go` cria uma goroutine
- `time.Sleep()` evita que o programa finalize antes