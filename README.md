import random

numero_secreto = random.randint(1, 100)
adivina = 0

print("Adivina el número del 1 al 100")

while adivina != numero_secreto:
    adivina = int(input("Tu número: "))

    if adivina < numero_secreto:
        print("Muy bajo ⬇️")
    elif adivina > numero_secreto:
        print("Muy alto ⬆️")
    else:
        print("¡GANASTE! 🎉 Era el", numero_secreto)

print("Fin del juego")