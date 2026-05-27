# Goroutines

Goroutines permitem executar tarefas simultaneamente.

## Exemplo

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
- o programa executa funções em paralelo