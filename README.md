# atividades_Kotlin

##Questão 1:
fun main() {
	
    var entrada_celsius = 30
    var F = entrada_celsius * 9 / 5 + 32
    
    print(F)
      
}
// F = C * 9/5 + 32

##Questão 2:
fun main() {
	
    var entrada_Fahrenheit = 86
    var C = (entrada_Fahrenheit - 32) * 5/9 
    
    print(C)
      
}
//  C = (F - 32) * 5/9

##Questão 3:
fun main() {
	
    val PI = 3.14
    var raio = 5
    var altura = 10
    
    var V = PI * raio*raio *altura 
    
    print(V)
      
}
//   V = π * raio^2 * altura

##Questão 4:
fun main() {
	
    var distancia = 360
    var consumo = 12
    
    var L = distancia / consumo 
    
    print(L)
      
}
//    litros = distância / consumo

##Questão 5:
fun main() {
	
    var valor_ori = 1000
    var taxa_juros = 1
    var meses_atrasados = 3
    
    var V = valor_ori * (1 + (taxa_juros / 100) * meses_atrasados)
    
    print(V)
      
}
// valor = valor_original * (1 + (taxa_juros / 100) * meses_atraso)

##Questão 6:
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

##Questão 7:
fun main() {
   var comprimento = 5
   var largura = 3
   var altura = 2
   
   var volume = comprimento * altura * largura
   print(volume)
}

##Questão 8:
fun main() {
   var num = 5
   var quadrado = num * num
   print(quadrado)
}

##Questão 9:
fun main() {
   var num1 = 25
   var num2 = 5
   var diferença = num1 - num2
   print(diferença)
}

##Questão 10:
fun main() {
   var dollar = 25
   var real = dollar * 5.26
   print(real)
}

##Questão 11:

fun main() {
   var real = 130
   var dollar = real / 5.26
   print(dollar)
}

##Questão 12:
fun main() {
   var num1 = 10
   var num2 = 5
   var num3 = 4
   var soma = (num1 * num1) + (num2 * num2) + (num3 + num3)
   print(soma)
   
 
}
##Questão 13:
fun main() {
   var num1 = 10
   var num2 = 5
   var num3 = 4
   var soma = num1 + num2 + num3
   var quadrado = soma * soma
   print(quadrado)
}
##Questão 14:
fun main() {
   var num1 = 10
   var num2 = 5
   var num3 = 4
   var num4 = 6
   var produto = num1 * num3
   var soma = num2 + num4
   print("produto: " + produto + ", Soma: " +soma)
   
 
}
##Questão 15:
fun main() {
   var salario = 1000
   var porcentagem = 50
   var aumento = salario * (porcentagem / 100.0)
   var novo_salario = salario + aumento
   print(novo_salario)
 
   
 
}

##Questão 16:
fun main() {
   var raio = 5
   var area = 3.14159 * raio * raio
   print(area)
 
   
 
}
##Questão 17:
fun main() {
   var num1 = 10
   var num2 = 5
   var soma = num1 + num2
   var subtracao = num1 - num2
   var multiplicacao = num1 * num2
   var divisao = num1 / num2
   print("subtracao: " + subtracao + ", Soma: " + soma + ", multiplicacao: " + multiplicacao + ",divsao: " + divisao)
 
   
 
}
##Questão 18:
fun main() {
   var distancia = 50
   var tempo = 1
   var velocidade = distancia / tempo / 3.6
   print(velocidade)
 
   
 
}
##Questão 19:
import kotlin.math.pow

fun main() {
    val base = 2.0
    val expoente = 3.0
    val resultado = base.pow(expoente)
    
    print(resultado) 
}

##Questão 20:
import kotlin.math.pow

fun main() {
    val pi = 3.14
    val raio = 5.0
    val expoente = 3.0
    val raioo = raio.pow(expoente)
    val resultado = (4.0/3.0) * pi * raioo
    
    print(resultado) 
}
##Questão 21:
import kotlin.math.pow

fun main() {
    val pes = 10
    val metros = pes * 0.3048
    print(metros)
}
##Questão 22:
import kotlin.math.pow

fun main() {
    val base = 16.0
    val indice = 2.0
    var raiz = base.pow(1.0/indice)
    print(raiz)
}
##Questão 23:
import kotlin.math.pow

fun main() {
    val num1 = 10
    val sucessor = num1 + 1
    val antecessor = num1 - 1
    print("O antecessor é" + antecessor + ", O sucessor é" + sucessor)
}
##Questão 24:
import kotlin.math.pow

fun main() {
    val num1 = 15
    val num2 = 3
    var resultado_divisao = num1 / num2
    var quadrado = resultado_divisao * resultado_divisao
    print(quadrado)
}
##Questão 25:
import kotlin.math.pow

fun main() {
    val num1 = 20
    val num2 = 8
    if (num1 > num2) {
        print(num1 - num2)
    }else{
        print(num2 - num1)
    }
    	
    
}
##Questão 26:
import kotlin.math.pow

fun main() {
    val num = 5

    if (num > 0){
        print("positivo")
        
    }else if {num < 0}{
        print("negativo")
        
    }else {
        print("neutro")
    }


}
##Questão 27:
fun main() {
    val nota1 = 7
    val nota2 = 6
    val nota3 = 4
    val nota4 = 5
    var media = (nota1 + nota2 + nota3 + nota4) / 4
    if (media > 5){
        print("Aprovado")
    }else{
        print("Reprovado")
    }


}
##Questão 28:
import kotlin.math.pow

fun main() {
    val nota1 = 7
    val nota2 = 6
    val nota3 = 4
    val nota4 = 5
    var media = (nota1 + nota2 + nota3 + nota4) / 4
    if (media > 7){
        print("Voce passou!!, sua media é: " + media)
    }else if (media >= 5){
        print("sua media é: " + media + "- Exame")
    }else{
        print("Sua media é: " + media + " - reprovado")
    }


}
##Questão 29:
import kotlin.math.pow
fun main() {
    val num1 = 10
    val num2 = 20
    val num3 = 3

    var menor_valor = num1
    var maior_valor = num1

    if (num2 > maior_valor) {
        maior_valor = num2
    }
    if (num2 < menor_valor) {
        menor_valor = num2
    }

    if (num3 > maior_valor) {
        maior_valor = num3
    }
    if (num3 < menor_valor) {
        menor_valor = num3
    }

    print("Maior valor é:" + maior_valor +", e menor valor é:" + menor_valor)
}
##Questão 30:
import kotlin.math.pow

fun main() {
	val valor = 1
	if (valor <= 3) {
		print(valor)
	}else{
		print("não segue os parametros")
	}





}	






























