# Somador_de_Numeros
Codigo criado para somar numeros até que o usuario digite "N", interrompendo a soma e dando o resultado final.
Algoritmo "SomarNumero"
//Codigo criado para somar número até que a resposta do usuário seja "N"

Var

  N: Inteiro
  S: Inteiro
  Resp: Caractere
  

Inicio

      S <- 0
      Repita
        Escreva ("Digite um valor: ")
        Leia (N)
        S <- S + N
        Escreva("Quer continuar? (S/N) ")
        Leia (Resp)
        Ate (Resp = "N")
        Escreva ("A soma dos valores e ", S)

Fimalgoritmo
