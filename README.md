# calculador-de-peso
#calculadora de peso imc
#imc = peso x altura
# < 19 : delgadez
# 20 a 25 : normal
#  26 a 30 : sobrepeso
# 30 en adelante obesidad

peso = float(input("ingrese su peso en kilogramos"))
altura = int(input("ingrese su altura en metros"))
alturaenmetros = altura / 100
imc = peso / (altura * altura)

print ("su imc es de" + str(imc))

if imc <= 19:
    print("estas delgado")

if imc >= 20 and imc <= 25:
    print("estas normal")

if imc >= 26 and imc <=30 :
    print("estas sobrepesado")

if imc >=31:
   print("estas obeso")
