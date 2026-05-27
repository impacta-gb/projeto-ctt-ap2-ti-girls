# Structs e Métodos

Structs agrupam informações relacionadas.

## Exemplo

```go
package main

import "fmt"

type Pessoa struct {
    Nome string
    Idade int
}

func main() {

    pessoa := Pessoa{
        Nome: "Daiana",
        Idade: 20,
    }

    fmt.Println(pessoa.Nome)
}
```

## Explicação

- `struct` cria tipos personalizados
- structs organizam dados