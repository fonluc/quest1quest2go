### Problemas Númericos com Go (Desafio 1)

Criada a pasta quest1 dentro da pasta src, aberto o VS Code e criado um arquivo quest1.go com o seguinte código:

```go
package main

import "fmt"

func main() {
	for i := 1; i <= 100; i++ {
		if i%3 == 0 {
			fmt.Println(i)
		}
	}
}
```

Depois foi aberto o Terminal e dados os comandos: “go build quest1.go” e “go run quest1.go”, exibindo a seguinte mensagem na tela:

“3
6
9
12
15
18
21
24
27
30
33
36
39
42
54
57
60
63
66
69
72
75
78
81
84
87
90
93
96
99”

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
