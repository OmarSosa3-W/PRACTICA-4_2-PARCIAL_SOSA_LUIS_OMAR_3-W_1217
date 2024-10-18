# PRACTICA-4_2-PARCIAL_SOSA_LUIS_OMAR_3-W_1217
PRACTICA 4 DEL SEGUNDO PARCIAL

PROGRAMA 1: DICCIONARIO VACIO

print() #para una linea en blanco al ejecutar
print("SOSA LUIS OMAR 3-W 1217: MI PRACTICA DE DICCIONARIO VACIO") #Nombre del creador
print() #para una linea en blanco al ejecutar
#la funcion que imprimira los datos
datos = {}
def agregar_datos(clave, valor):
    datos[clave] = valor
    print("Datos actuales:", datos)
print() #para una linea en blanco al ejecutar

#para que muestre el nombre
nombre = input("Coloca tu nombre: ")
agregar_datos("Nombre", nombre)
print() #para una linea en blanco al ejecutar

#para que muestre la edad
edad = input("Coloca tu edad: ")
agregar_datos("Edad", edad)
print() #para una linea en blanco al ejecutar

#para que muestre el sexo
sexo = input("Coloca tu sexo: ")
agregar_datos("Sexo", sexo)
print() #para una linea en blanco al ejecutar

#para que muestre el mes de nacimiento
mes_nacimiento = input("Ingresa tu mes de nacimiento: ")
agregar_datos("Mes de nacimiento", mes_nacimiento)
print() #para una linea en blanco al ejecutar

#para que muestre el numero telefonico
telefono = input("Coloca tu número de teléfono: ")
agregar_datos("Número de teléfono", telefono)
print() #para una linea en blanco al ejecutar

#para que muestre el correo
correo = input("Ingresa tu correo electronico:")
agregar_datos("Correo electronico", correo)
print() #para una linea en blanco al ejecutar

![image](https://github.com/user-attachments/assets/6bec76ee-5538-4c23-bec3-2db8e6feb3f0)
![image](https://github.com/user-attachments/assets/baa99d75-d463-4204-9423-ef376e814fae)

PROGRAMA 2: TRADUCCIÓN DE ESPAÑOL A INGLES

print() #es para dejar una linea en blanco
print("SOSA LUIS OMAR 3-W 1217: MI PRACTICA DE TRADUCTOR") #nombre del creador
print() #es para dejar una linea en blanco
traducciones = {
    "hola": "hello",
    "mundo": "world",
    "cómo": "how",
    "estás": "are you",                      #se definen todas las variables que se usaran para la frase traducida 
    "gracias": "thank you",
    "no quiero" : "I don't want to",
    "hacer" : "do",
    "tarea" : "homework"
}
print(traducciones) #muestra o lee el diccionario a mostrar
print() #es para dejar una linea en blanco

print(traducciones)  #muestra o lee el diccionario a mostrar
print() #es para dejar una linea en blanco
frase_espanol = input("Ingresa una frase en español: ") #pide ingresar una frase o palabra en español
print() #es para dejar una linea en blanco
traduccion = ""
for palabra in frase_espanol.split(): #slipt para dividir una cadena de texto en una lista
    traduccion += traducciones.get(palabra, palabra) + " " #para traducir palabras en una oración utilizando

print("Traducción al inglés:", traduccion.strip()) #imprime el resultado final de la traducción
print() #es para dejar una linea en blanco

![image](https://github.com/user-attachments/assets/9ef812f2-ae27-4df1-b6a5-7f137b7c1bc7)
![image](https://github.com/user-attachments/assets/d3d46455-2ad8-45b0-8a80-8b055e8051fe)


