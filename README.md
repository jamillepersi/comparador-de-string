# comparador de string
#programa que compara as strings e informa se são iguais em tamanho e coteúdo

print("Compara duas strings")

s1 = input("Digite a frase")
s2 = input("digite a frase dois")
print(f'Tamanho de"{s1}": {len(s1)} caracteres')
print(f'Tamanho de"{s2}": {len(s2)} caracteres')

if len(s1) == len(s2):
    print("As duas strings são de tamanhos iguais.")
else:
    print("As duas strings são de tamanhos diferentes.")

if s1 == s2:
    print("As duas strings são iguais.")

else:        
    print("As duas strings possuem conteúdo diferente.")



