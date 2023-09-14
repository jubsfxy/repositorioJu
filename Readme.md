Algoritmo "menu lanchonete_julia fernanda D silva"

Var
opcao, total, valor_item:real

Inicio
total<-0
escreval ("Seja Bem-Vindo a julia's lanchonete!")
escreval ("escolha seu pedido:")
escreval ("1 X-Salada R$7.00")
escreval ("2 X-Bacon R$11.00")
escreval ("3 X-Egg R$8.00")
escreval ("4 Refrigerante R$5.00")
escreval ("5 Finalizar Pedido")

repita
escreval("faça seu pedido: ")
leia(opcao)

 se opcao = 1 entao
   valor_item <- 7.0
 senao
 se opcao = 2 entao
   valor_item <- 11.0
 senao
 se opcao = 3 entao
   valor_item <- 8.0
 senao
 se opcao = 4 entao
   valor_item <- 5.0
 senao
 se opcao = 5 entao
   escreval("pedido finalizado. total a pagar: R$", total)
 senao
   escreval("opçãoinvalida. escolha uma opção valida.")
   
  fimse
  fimse
  fimse
  fimse
  fimse
  

   total <-(total + valor_item)
   
ate opcao = 5

Fimalgoritmo
