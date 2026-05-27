# Testes Automatizados

Go possui suporte nativo para testes.

## Exemplo

```go
package main

import "testing"

func Soma(a int, b int) int {
    return a + b
}

func TestSoma(t *testing.T) {

    resultado := Soma(2, 3)

    if resultado != 5 {
        t.Errorf("Resultado incorreto")
    }
}
```

## Executando testes

```go
go test
```

## Explicação

- funções de teste começam com `Test`
- `go test` executa os testes