# UTN-TUPaDProgramacion1
Trabajo Práctico: uso de Git mediante GitHub y GitHub Desktop

## 1) Crear un programa que imprima por pantalla el mensaje: “Hola Mundo!”.

print("Hola Mundo!")

## 2) Crear un programa que pida al usuario su nombre e imprima por pantalla un saludo usando el nombre ingresado.

nombre = input("Ingrese su nombre: ")
print(f"Hola {nombre}!")

## 3) Crear un programa que pida al usuario su nombre, apellido, edad y lugar de residencia e imprima por pantalla una oracion conw los datos ingresados.

nombre = input("Ingrese su nombre: ")
apellido = input("Ingrese su apellido: ")
edad = input("Ingrese su edad: ")
lugar_residencia = input("Ingrese su lugar de residencia: ")

print(f"Soy {nombre} {apellido}, tengo {edad} años y vivo en {lugar_residencia}.") 


## 4) Crear un programa que pida al usuario el radio de un círculo e imprima por pantalla su área y su perimetro

radio = float(input("Ingrese el radio del círculo: "))
area = 3.1416 * radio ** 2
perimetro = 2 * 3.1416 * radio

print(f"El área del círculo es: {area}")
print(f"El perímetro del círculo es: {perimetro}")

## 5) Crear un programa que pida al usuario una cantidad de segundos e imprima por pantalla a cuántas horas equivale.

segundos = int(input("Ingrese una cantidad de segundos: "))
horas = segundos / 3600 

print(f"{segundos} segundos equivalen a {horas} horas.")

## 6) Crear un programa que pida al usuario un número e imprima por pantalla la tabla de multiplicar de dicho numero.

numero = int(input("Ingrese un número: "))

for i in range(1, 11):
    resultado = numero * i
    print(f"{numero} x {i} = {resultado}")

## 7) Crear un programa que pida al usuario dos números enteros distintos del 0 y muestre por pantalla el resultado de sumarlos, dividirlos, multiplicarlos y restarlos.

num1 = int(input("Ingrese el primer número entero distinto de 0: "))
num2 = int(input("Ingrese el segundo número entero distinto de 0: "))
suma = num1 + num2
resta = num1 - num2
multiplicacion = num1 * num2
division = num1 / num2

print(f"La suma de {num1} y {num2} es: {suma}")
print(f"La resta de {num1} y {num2} es: {resta}")
print(f"La multiplicación de {num1} y {num2} es: {multiplicacion}")
print(f"La división de {num1} y {num2} es: {division}")

## 8) Crear un programa que pida al usuario su altura y su peso e imprima por pantalla su índice de masa corporal. 
## Tener en cuenta que el índice de masa corporal se calcula del siguiente modo: IMC = peso / altura^2

peso = float(input("Ingrese su peso en kilogramos: "))
altura = float(input("Ingrese su altura en metros: "))
imc = peso / altura ** 2
print(f"Su índice de masa corporal (IMC) es: {imc}")

## 9) Crear un programa que pida al usuario una temperatura en grados Celsius e imprima por
## pantalla su equivalente en grados Fahrenheit. Tener en cuenta la siguiente equivalencia: temperatura en °F = (temperatura en °C * 9/5) + 32

celsius = float(input("Ingrese una temperatura en grados Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print(f"{celsius} grados Celsius equivalen a {fahrenheit} grados Fahrenheit.")

## 10) Crear un programa que pida al usuario 3 números e imprima por pantalla el promedio de dichos números.

num1 = float(input("Ingrese el primer número: "))
num2 = float(input("Ingrese el segundo número: "))
num3 = float(input("Ingrese el tercer número: "))
promedio = (num1 + num2 + num3) / 3
print(f"El promedio de {num1}, {num2} y {num3} es: {promedio}")
