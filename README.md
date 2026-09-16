# CALCULADORA DE ÁREAS VERSION 2
# STUDENT: RAYNER CORY CHAGUA

print("CALCULADORA DE ÁREAS")
print("1. Cuadrado")
print("2. Rectángulo")

opcion = input("Seleccione una opción: ")

if opcion == "1":
    lado = float(input("Ingrese el lado del cuadrado: "))
    area = lado * lado
    print("El área del cuadrado es: ", area)

elif opcion == "2":
    base = float(input("Ingrese la base del rectángulo: "))
    altura = float(input("Ingrese la altura del rectángulo: "))
    area = base * altura
    print("El área del rectángulo es: ", area)

else:
    print("Opción no válida")
    
