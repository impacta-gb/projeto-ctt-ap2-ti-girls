# Tratamento de Erros

Em Go, erros são tratados explicitamente.

## Exemplo

```go
package main

import (
    "fmt"
    "os"
)

func main() {

    _, err := os.Open("arquivo.txt")

    if err != nil {
        fmt.Println("Erro ao abrir arquivo")
    }
}
```

## Explicação

- `err` armazena possíveis erros
- `if err != nil` verifica falhas