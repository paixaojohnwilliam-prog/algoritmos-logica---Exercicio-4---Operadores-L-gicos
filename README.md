# algoritmos-logica---Exercicio-4---Operadores-L-gicos
Esse me deu uma "canseira", mas com prática peguei a lógica.

algoritmo "Triangulo"
var
     L1, L2, L3: Real
     EQ, ES : Logico
inicio
          Escreva("Digite o primeiro lado: ")
          Leia(L1)
          Escreva("Digite o segundo lado: ")
          Leia(L2)
          Escreva("Digite o terceiro lado: ")
          Leia(L3)
          EQ <- (L1 = L2) e (L2 = L3)
          ES <- (L1 <> L2) e ( L2 <> L3)
          Escreva("O triangulo e EQUILATERO? ", EQ)
          Escreval("O trigangulo e ESCALENO?", ES)
fimalgoritmo
