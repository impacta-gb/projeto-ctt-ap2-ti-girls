# Estruturas de Controle

Go possui estruturas de decisão e repetição.

## If

```go
idade := 18

if idade >= 18 {
    fmt.Println("Maior de idade")
}
```

## For

```go
for i := 0; i < 5; i++ {
    fmt.Println(i)
}
```

## Switch

```go
dia := "segunda"

switch dia {
case "segunda":
    fmt.Println("Início da semana")
}
```

## Explicação

- `if` cria condições
- `for` faz repetições
- `switch` compara valores