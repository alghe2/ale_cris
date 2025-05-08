nombre = input("Bienvenido, cual es tu nombre?: ")
print("Bienvenido ", nombre)

edad = int(input("Cuantos años tienes?: "))

if edad < 100:
    años_faltante = 100 - edad
    print(f"Te faltan {años_faltante} para llegar a 100 años :)")

elif edad == 100:
    print("Felicidades ya tienes 100 años! :)")

else:
    print("Felicidades pasaste los 100 años! :)")
