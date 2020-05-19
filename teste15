from random import randint
from time import sleep
#Demostração
print("Seja Bem-vindo, ao Simulador de Dados.")
c = 1
face_Min = int(input("Informe os valores Minímos do Dado: "))
face_Max = int(input("Informe os valores Máximos: "))
aleatorio = randint(face_Min, face_Max)
print("Os Dados foram lançados...")
sleep(2)
print("O resultado foi...")
sleep(1)
print(aleatorio)
vez = str(input("Deseja Lançar novamente[S/N]:  ")).upper()
if vez == "S":
    while c == 1:
        face_Min = int(input("Informe os valores Minímos do Dado: "))
        face_Max = int(input("Informe os valores Máximos: "))
        aleatorio = randint(face_Min, face_Max)
        print("Os Dados foram lançados...")
        sleep(2)
        print("O resultado foi...")
        sleep(1)
        print(aleatorio)
        sugestao = str(input("Deseja Continuar[S/N]: ")).upper()
        if sugestao == "S":
            c = c + 0
        elif sugestao == "N":
            print("Finalizando Programa, Aguarde...")
            print("Fim.")
            sleep(2)
            c = c - 1
       
else: print("Fim do Programa")
    
