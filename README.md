Algoritmo "SistemaMétrico"

var
   n1, n2, temp, chuva:real
   
inicio
   //Entrada de dados
   escreva("Digite a temperatura em Fahrenheit que deseja converter: ")
   leia(n1)
   
   escreva("Digite a quantidade de chuva em polegadas que deseja converter: ")
   leia(n2)
   
   //Operações
   temp <- (5 * ( n1 - 32) ) / 9
   chuva <- n2 * 25.4
   
   //Saída de dados
   escreval("O VALOR EM CELSIUS = " , temp)
   escreva("A QUANTIDADE DE CHUVA E =" , chuva , "mm")

fimalgoritmo
