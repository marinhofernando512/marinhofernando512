nome = "Fernando"
print(f"Oi, meu nome é {Fernando}")



#-------------------------------------

opcao1 = "a) Cadastrar funcionários"
opcao2 = "b) Listar funcionários"
opcao3 = "c) Editar funcionários"
opcao4 = "d) Remover funcionários"
opcao5 = "e) Sair"

# print(f"Cadastro de funcionários\n\n{opcao1}\n{opcao2}\n{opcao3}\n{opcao4}\n")
print('''
Cadastro de funcionários
a) Cadastrar funcionários
b) Listar funcionários
c) Editar funcionários
d) Remover funcionários
''')
input("Digite a opção desejada:")


-----------------------------------------

admin: str = None
nome: str = None
nome = "Fernando" # nome = Fernando; admin = None
admin = "João" # nome = Fernando; admin = João
nome = admin # nome = João; admin = João 
print(nome)

---------------------

nome: str = input("Digite o seu nome: ")
idade: int = int(input("Digite a sua idade: "))
peso: float = float(input("Digite o seu peso: "))
altura: float = float(input("Digite sua altura: "))
telefone: str = input("Digite o seu telefone: ")

print(f'''
Nome: {nome}
Idade: {idade}
Peso: {peso}
Altura: {altura}
Telefone: {telefone}
''')


-------------------------------

titulo: str = " Menino no Espelho"
edicao: int = "61"
autor: str = "Fernando Sabino"
data_publicacao: str = "10/10/1982"

print(f'''
Titulo: {titulo}
Edição: {edicao}
Autor: {autor}
Data de publicação: {data_publicacao}
''')

-------------------------


data_nascimento: str = "26/03/2000"
quantidade_filhos: int = 2
usuario_logado: str = "97aa1cbd-d266-4395-8270-dca278587024"

----------------------------

nome: str = "João"
print(f"Olá {1}") # Olá 1
print(f"Olá {'nome'}") # Olá nome
print("Olá {nome}") # Olá nome 

----------------------


a = 2
x = 1 + (a *= 2)
print(a, x)

a /= 2
a = a / 2 

----------------

# INPUT
altura: float = float(input("Digite a altura do retângulo: "))
largura: float = float(input("Digite a largura do retângulo: "))

# PROCESSAMENTO
area: float = altura * largura
perimetro: float = altura * 2 + largura * 2

# OUTPUT
print(f"""
A área do retângulo é: {area:.2f}
O perímetro do retângulo é: {perimetro:.2f}
""")

----------------------


# Crie um algoritmo que receba dois números e mostre na tela o resultado da 
# soma entre esses dois números.

# INPUT
# receba dois números

# PROCESSAMENTO
# soma entre esses dois números

# SAÍDA
# mostre na tela o resultado da 
# soma
numero1: int = int(input("Digite o número 1: "))
numero2: int = int(input("Digite o número 2: "))

soma: int = numero1 + numero2

print(f"A soma entre {numero1} e {numero2} é: {soma}") 


----------------


# 14)Faça um programa que receba duas notas do usuário, "  
# calcule a média e mostre o resultado na tela.
# INPUT
# N1, N2

# PROCESSAMENTO
# Calcular a média = (N1 + N2) / 2

# OUTPUT
# Média
nota1: float = float(input("Digite a nota 1: "))
nota2: float = float(input("Digite a nota 2: "))

media: float = (nota1 + nota2) / 2

print(f"A média é: {media:.2f}")


----------------------------------------


# Faça um programa que receba 3 números, calcule o quadrado de cada um deles e 
# mostre o resultado na tela.
# INPUT
# N1, N2, N3

# PROCESSAMENTO
# quadrado de cada um deles (N1, N2, N3)

# OUTPUT
# Mostrar o resultado

# INPUT
numero1: int = int(input("Digite o número 1: "))
numero2: int = int(input("Digite o número 2: "))
numero3: int = int(input("Digite o número 3: "))

# PROCESSAMENTO
quadrado1: int = numero1 ** 2
quadrado2: int = numero2 ** 2
quadrado3: int = numero3 ** 2

# OUTPUT
print(f"""
O quadrado número {numero1} é: {quadrado1}
O quadrado número {numero2} é: {quadrado2}
O quadrado número {numero3} é: {quadrado3}
""")

-------------------------

# Escreva um algoritmo que armazene o valor 10 em uma variável A 
# e o valor 20 em uma variável B. A seguir 
# (utilizando apenas atribuições entre variáveis) troque os seus conteúdos 
# fazendo com que o valor que está em A passe para B e vice-versa. Ao final, 
# mostrar na tela os valores que ficaram armazenados nas variáveis.
a: int = 10
b: int = 20
aux: int = a

a = b
b = aux

# a, b = b, a
print(a, b)

----------------------

# Considerando que cada mês possui 30 dias, faça um algoritmo que:

# Receba uma quantidade n de meses do usuário.
# Calcule o total de dias com base nessa quantidade n de meses.
# Mostre o resultado na tela.

# INPUT
# Quantidade de meses (n)

# PROCESSAMENTO
# Calcule o total de dias -> 30 * n

# OUTPUT
# Mostrar a quantidade de dias

# CONSTANTE -> Uma "variável" que não pode ser alterada
DIAS_NO_MES: int = 30

# INPUT
n: int = int(input("Digite a quantidade de meses: "))

# PROCESSAMENTO
total_dias = n * DIAS_NO_MES

#  OUTPUT
print(f"A quantidade de dias em {n} meses é: {total_dias}")


-------------------------------------------

# Elabore um script que leia um número e 
# apresente o antecessor, o número e o sucessor.
numero: int = int(input("Digite um número inteiro: "))

antecessor = numero - 1
sucessor = numero + 1

print(antecessor, numero, sucessor) 

-----------------------------

# Faça um programa que calcule e mostre o volume de uma esfera sendo 
# fornecido o valor de seu raio R. A fórmula para calcular o 
# volume é: (4/3) * pi * R^3. Considere (atribua) para pi o valor 3.14159.
import math


PI = 3.14159
R: float = float(input("Digite o valor do raio: "))

volume: float = 4 / 3 * math.pi * R ** 3

print(f"O volume da esfera é: {volume:.2f}")


-----------------------------------------

# Escreva um script que receba a base e altura de triângulo e calcule a sua área.
# INPUT
# receba a base e altura de triângulo

# PROCESSAMENTO
# calcular a área do triângulo -> base * altura / 2

# OUTPUT
# Mostrar a área do triângulo
base: float = float(input("Digite a base do triângulo: "))
altura: float = float(input("Digite a altura do triângulo: "))

area: float = base * altura / 2

print(f"A área do triângulo é: {area:.2f}")


------------------------------------

# Construa um script que leia o preço de um produto, o percentual 
# de desconto e calcule o valor a pagar e o valor do desconto
preco: float = float(input("Digite o preço do produto: "))
percentual_desconto: float = float(input("Digite o percentual de desconto do produto: "))

desconto: float = percentual_desconto / 100 * preco
valor_total: float = preco - desconto

print(f"Preço: {preco}")
print(f"% de desconto: {percentual_desconto}")
print(f"Valor total: {valor_total}")
print(f"Desconto: {desconto}")


-------------------------------

# Faça um programa que leia o nome de um vendedor, o seu salário fixo 
# e o total de vendas efetuadas por ele no mês (em dinheiro). Sabendo que 
# este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o 
# total a receber no final do mês, com duas casas decimais.
nome: str = input("Digite o nome do vendedor: ")
salario_fixo: float = float(input("Digite o salário do vendedor: "))
total_vendas: float = float(input("Digite o total de vendas do vendedor: "))

salario_total: float = salario_fixo + total_vendas * .15

print(f"O salário total do funcionário é: {salario_total:.2f}")

-------------
