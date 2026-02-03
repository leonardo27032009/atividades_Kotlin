# 📘 Atividades Kotlin

---

## Questão 1 — Celsius para Fahrenheit

```kotlin
fun main() {
    var entrada_celsius = 30
    var F = entrada_celsius * 9 / 5 + 32

    print(F)
}
````

---

## Questão 2 — Fahrenheit para Celsius

```kotlin
fun main() {
    var entrada_Fahrenheit = 86
    var C = (entrada_Fahrenheit - 32) * 5 / 9

    print(C)
}
```

---

## Questão 3 — Volume do Cilindro

```kotlin
fun main() {
    val PI = 3.14
    var raio = 5
    var altura = 10

    var V = PI * raio * raio * altura

    print(V)
}
```

---

## Questão 4 — Consumo

```kotlin
fun main() {
    var distancia = 360
    var consumo = 12

    var L = distancia / consumo

    print(L)
}
```

---

## Questão 5 — Juros Simples

```kotlin
fun main() {
    var valor_ori = 1000
    var taxa_juros = 1
    var meses_atrasados = 3

    var V = valor_ori * (1 + (taxa_juros / 100.0) * meses_atrasados)

    print(V)
}
```

---

## Questão 6 — Troca de Valores

```kotlin
fun main() {
    var A = 10
    var B = 5
    var temp: Int

    temp = A
    A = B
    B = temp

    println("A = $A")
    println("B = $B")
}
```

---

## Questão 7 — Volume da Caixa

```kotlin
fun main() {
    var comprimento = 5
    var largura = 3
    var altura = 2

    var volume = comprimento * altura * largura
    print(volume)
}
```

---

## Questão 8 — Quadrado

```kotlin
fun main() {
    var num = 5
    var quadrado = num * num

    print(quadrado)
}
```

---

## Questão 9 — Diferença

```kotlin
fun main() {
    var num1 = 25
    var num2 = 5
    var diferenca = num1 - num2

    print(diferenca)
}
```

---

## Questão 10 — Dólar para Real

```kotlin
fun main() {
    var dollar = 25
    var real = dollar * 5.26

    print(real)
}
```

---

## Questão 11 — Real para Dólar

```kotlin
fun main() {
    var real = 130
    var dollar = real / 5.26

    print(dollar)
}
```

---

## Questão 12 — Soma dos Quadrados

```kotlin
fun main() {
    var num1 = 10
    var num2 = 5
    var num3 = 4

    var soma = (num1 * num1) + (num2 * num2) + (num3 * num3)

    print(soma)
}
```

---

## Questão 13 — Quadrado da Soma

```kotlin
fun main() {
    var num1 = 10
    var num2 = 5
    var num3 = 4

    var soma = num1 + num2 + num3
    var quadrado = soma * soma

    print(quadrado)
}
```

---

## Questão 14 — Produto e Soma

```kotlin
fun main() {
    var num1 = 10
    var num2 = 5
    var num3 = 4
    var num4 = 6

    var produto = num1 * num3
    var soma = num2 + num4

    print("Produto: $produto, Soma: $soma")
}
```

---

## Questão 15 — Aumento Salarial

```kotlin
fun main() {
    var salario = 1000
    var porcentagem = 50

    var aumento = salario * (porcentagem / 100.0)
    var novo_salario = salario + aumento

    print(novo_salario)
}
```

---

## Questão 16 — Área do Círculo

```kotlin
fun main() {
    var raio = 5
    var area = 3.14159 * raio * raio

    print(area)
}
```

---

## Questão 17 — Operações

```kotlin
fun main() {
    var num1 = 10
    var num2 = 5

    var soma = num1 + num2
    var subtracao = num1 - num2
    var multiplicacao = num1 * num2
    var divisao = num1 / num2

    print("Subtração: $subtracao, Soma: $soma, Multiplicação: $multiplicacao, Divisão: $divisao")
}
```

---

## Questão 18 — Velocidade

```kotlin
fun main() {
    var distancia = 50
    var tempo = 1

    var velocidade = distancia / tempo / 3.6

    print(velocidade)
}
```

---

## Questão 19 — Potência

```kotlin
import kotlin.math.pow

fun main() {
    val base = 2.0
    val expoente = 3.0

    val resultado = base.pow(expoente)

    print(resultado)
}
```

---

## Questão 20 — Volume da Esfera

```kotlin
import kotlin.math.pow

fun main() {
    val pi = 3.14
    val raio = 5.0

    val resultado = (4.0 / 3.0) * pi * raio.pow(3.0)

    print(resultado)
}
```

---

## Questão 21 — Pés para Metros

```kotlin
fun main() {
    val pes = 10
    val metros = pes * 0.3048

    print(metros)
}
```

---

## Questão 22 — Raiz Quadrada

```kotlin
import kotlin.math.pow

fun main() {
    val base = 16.0
    val indice = 2.0

    val raiz = base.pow(1.0 / indice)

    print(raiz)
}
```

---

## Questão 23 — Antecessor e Sucessor

```kotlin
fun main() {
    val num1 = 10

    val sucessor = num1 + 1
    val antecessor = num1 - 1

    print("Antecessor: $antecessor, Sucessor: $sucessor")
}
```

---

## Questão 24 — Quadrado da Divisão

```kotlin
fun main() {
    val num1 = 15
    val num2 = 3

    val resultado = num1 / num2
    val quadrado = resultado * resultado

    print(quadrado)
}
```

---

## Questão 25 — Diferença Absoluta

```kotlin
fun main() {
    val num1 = 20
    val num2 = 8

    if (num1 > num2) {
        print(num1 - num2)
    } else {
        print(num2 - num1)
    }
}
```

---

## Questão 26 — Positivo, Negativo ou Neutro

```kotlin
fun main() {
    val num = 5

    if (num > 0) {
        print("Positivo")
    } else if (num < 0) {
        print("Negativo")
    } else {
        print("Neutro")
    }
}
```

---

## Questão 27 — Média

```kotlin
fun main() {
    val n1 = 7
    val n2 = 6
    val n3 = 4
    val n4 = 5

    val media = (n1 + n2 + n3 + n4) / 4

    if (media > 5) {
        print("Aprovado")
    } else {
        print("Reprovado")
    }
}
```

---

## Questão 28 — Média com Exame

```kotlin
fun main() {
    val n1 = 7
    val n2 = 6
    val n3 = 4
    val n4 = 5

    val media = (n1 + n2 + n3 + n4) / 4

    if (media > 7) {
        print("Você passou! Média: $media")
    } else if (media >= 5) {
        print("Exame. Média: $media")
    } else {
        print("Reprovado. Média: $media")
    }
}
```

---

## Questão 29 — Maior e Menor

```kotlin
fun main() {
    val num1 = 10
    val num2 = 20
    val num3 = 3

    var menor = num1
    var maior = num1

    if (num2 > maior) maior = num2
    if (num2 < menor) menor = num2

    if (num3 > maior) maior = num3
    if (num3 < menor) menor = num3

    print("Maior: $maior, Menor: $menor")
}
```

---

## Questão 30 — Validação

```kotlin
fun main() {
    val valor = 1

    if (valor <= 3) {
        print(valor)
    } else {
        print("Não segue os parâmetros")
    }
}
```

---

