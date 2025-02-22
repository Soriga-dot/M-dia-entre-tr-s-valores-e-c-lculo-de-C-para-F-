celsius = float(input("Digite qual a temperatura em Celsius: "))
resultado = celsius * 1.8 + 32 #Este é o calculo utilizado para transformar celsius para fahrenheit
print("A temperatura de celsius para fahrenheit equivale a: ", resultado)
if (resultado < 68):
    print("Está uma temperatura fria, ponha um casaco ao sair de casa!")
if (resultado > 78.8):
    print("Está uma temperatura quente, saia de uma forma agradável!")
if resultado in [69.8, 71.6, 73.4, 75.2, 77]: #Utilizar "in" para facilitar ao usar o código, ao invés de or em todas as temperaturas em Fº
    print("Está uma temperatura normal para sair de casa!")
print("Até mais!")
