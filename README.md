# primeiro-codigo
Foi um treinamento que estou fazendo para aprender a programar em python

mensagem="Por favor insira operação matemática que deseja"
mensagem+="\n + para adição"
mensagem+="\n - para subtração"
mensagem+="\n * para multiplicação"
mensagem+="\n / para divisão:\n"

operacao= input(mensagem)

num_1 = int(input ("Entre o primeiro número: \n"))
num_2 = int(input ("Entre o segundo número: \n"))

if operacao =='+':
    print(f"adição:{num_1} {operacao} {num_2} = {num_1 + num_2}")
elif operacao =='-':
    print(f"subtração: {num_1} {operacao} {num_2} = {num_1 - num_2}")
elif operacao =='*':
    print(f"multiplicação: {num_1} {operacao} {num_2} = {num_1 * num_2}")
elif operacao =='/':
    print(f"divisão: {num_1} {operacao} {num_2} = {num_1 / num_2}")
else:
    print("Operação matemática invalida, tente novamente")
 
