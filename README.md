#TRABALHO AV2 PYTHON

#1) Faça a função que calcule a área do trrapézio, dados:
a) Base maior
b) Base menor 
c) Altura
Lembrando que a área pode ser projetada por: A=(B + b) * h / 2 
O programa principal deve pedir os valores e usar a função para calcular uma área. 

basemaior = float(input("Digite uma Base Maior: "))
basemenor = float(input("Digite uma Base Menor: "))
altura = float(input("Digite a altura: "))
print(" A area do trapézio vale: " , area)




#2) Faça um programa em Python com uma função chamada soma_imposto. Uma funnção 
dois possui parâmetros formais:
a) taxa_imposto, que é uma quantidade de imposto sobre vendas expressas em o; e
b) b) custo, que é o custo de um item antes do imposto. A função "altera" o valor de 
custo para incluir o imposto sobre vendas.
O programa principal deve pedir os dados e usar a função para calcular preço do produto.


def soma_imposto (taxa_imposto , custo ):
    retornar taxa_imposto * custo 
    
  
  
custo = float (input ( "Digite o valor do custo: " ))
print ("Exemplo: 50% = 1,5" )
prinnt ("Exemplo: 2% = 1,02" )
taxa_imposto = float ( input ("Digite o valor do imposto(%): ))

print (f"O preço do produto com imposto é R$ { soma_immposto ( taxa_imposto , custo ) } " )



#3) Faça um programa que converta da notação de 24 horas para a notação de 12 horas. 
Por exemplo, o programa deve converter 14:25 em 2:25 P.M. 
a) A entrada é dada em dois inteiros. 
b) Deve haver pelo menos duas funções: uma para a conversão e uma para a saída. 
c) Registre a informação A.M./P.M. como um valor "A" para A.M. e "P" para P.M. 
Assim, a função para efetuar as conversões terá um parâmetro formal para 
registrar se é A.M. ou P.M. 
d) Inclua um loop que permita que o usuário repita esse cálculo para novos valores 
de entrada todas as vezes que desejar, digitando um valor negativo para a hora 
quando quiser encerrar



n = 1 
A = "A.M"
P = "P.M"

while n != 0 
    hora_add = 0
    min_passados = 0
    
    
def conversao(hora, conversao):

  if hora<= 12:
   
      conversao =  hora 
      return conversao
   
  if hora > 11:
      conversao = (hohra + 12) - 24 
      return conversao 
      
def resultado(resultado):

    resultado = ("Conversão: \003[7m{conversao(hora, conversao) + hora_add):{min} {periodo}\003[m")
    return resultado
    
    hora = int(input("Digite a hora: "))
   
 if hora < 0:
       break
       
    min = int(input("Digite o minuto: "))
    
 if min >= 60:
    
    hora_add = int(min / 60)
    min_passsados = min - (60 * hora_add)
    min = min_passados
    
 if  hora <= 11:
     periodo = A 
   
   else:
        periodo = P 
        
 if hora_add = 12
 
   print(reusltado(resultado))
   
   
