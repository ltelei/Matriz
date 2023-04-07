# Matriz
meu primeiro codigo de matriz
Algoritmo "Sala de Aula"

Var
   x, y:  inteiro
   notas: vetor [1..4,1..3] de real  {primeiro a linha}
                                      {depois a coluna}


Inicio
   // Seção de Comandos, procedimento, funções, operadores, etc...

   para x de 1 ate 4 faca
      para y de 1 ate 2 faca
         Escreval(" Digite a nota " ,y, " do aluno ", x )
         leia (notas[x,y])
      fimpara
      notas[x,3]<-(notas[x,1]+notas[x,2])/2

   fimpara
    para x de 1 até 4 faca
    escreval(" A media do aluno ",x,"  é ",notas[x,3])
    
    fimpara


Fimalgoritmo
