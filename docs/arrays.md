# Arrays, Slices e Maps

Go possui diferentes estruturas para armazenar dados.

## Array

```go
numeros := [3]int{1, 2, 3}
```

## Slice

```go
nomes := []string{"Ana", "Carlos"}
```

## Map

```go
idades := map[string]int{
    "Ana": 20,
    "Carlos": 25,
}
```

## Explicação

- arrays possuem tamanho fixo
- slices possuem tamanho dinâmico
- maps armazenam chave e valor

# Arrays, Slices e Maps

## O que são Arrays?

Arrays armazenam vários valores do mesmo tipo.

## Exemplo em Go

```go
package main

import "fmt"

func main() {
    numeros := [3]int{1, 2, 3}

    fmt.Println(numeros)
}