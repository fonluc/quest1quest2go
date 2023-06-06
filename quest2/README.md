### Problemas Númericos com Go (Desafio 2)

Criada a pasta quest2 dentro da pasta src, aberto o VS Code e criado um arquivo quest2.go com o seguinte código:

```go
package main

import "fmt"

func main() {
	for i := 1; i <= 100; i++ {
		if i%3 == 0 {
			fmt.Print("Pin")
		}
		if i%5 == 0 {
			fmt.Print("Pan")
		}
		fmt.Println()
	}
}
```

Depois foi aberto o Terminal e dados os comandos: “go build quest2.go” e “go run quest2.go”, exibindo a seguinte mensagem na tela:

“

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan

Pin

PinPan

Pin

Pan
Pin

Pin
Pan”
