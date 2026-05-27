```go
package main

import (
    "fmt"
    "errors"
)

func validarIdade(idade int) error {
    if idade < 18 {
        return errors.New("idade inválida")
    }

    return nil
}

func main() {
    errors := validarIdade(15)

    if error != nil {
        fmt.Println(errors)
    }
}
```