# rama 2 para cambios con pull request
#Realiza la las prácticas de los siguientes casos:

#Listas
#Tuplas.
#Diccionarios.
#Conjuntos.
#Estructuras mixtas.
#Recursividad.

#Listas
lenguajes = ["Sedan", "SUV", "compacto", "troca","camioneta"] #0, 1, 2, 3, 4, 5.

print (lenguajes )


# Tuplas

lenguajes = ["Sedan", "SUV", "compacto", "troca","camioneta"]
 
print(lenguajes [1:4])

#Diccionarios

Marcas= {}

Marcas["Honda"] = "Hondero"
Marcas["Italika"] = "Mortalika"
Marcas["Nissan"] = "Marcheratti"
Marcas["Ram"] = "Mamalona"
Marcas["Chrysler"] = "Bebe a bordo"

print(Marcas)

print (Marcas ["Italika"])

#Conjuntos

tipos4cil_o_menos= set(["Moto", "compacto", "Cuatrimoto"])

print("4 cil o menos: ", tipos4cil_o_menos)

tipos4cil_o_mas =set(["Sedan", "troca","camioneta"])

print("4 cil o mas : ", tipos4cil_o_mas)

#Estructuras Mixtas

#lista
tiposdecarros= ["Sedan", "SUV", "compacto", "troca","camioneta"]  
print(tiposdecarros)

print("tipo seleccionado :")

print(tiposdecarros[2])
#diccionario
diccionariodecarros = {"tipos": tiposdecarros}


#estructuramixta
diccionariodecarros["informacion del tipo de carro seleccionado"] = {
    "year": 2000,
    "fabricante": "HondaCivic",
    "precio_promedio": 50000.0,
    "existencia": True
}

print(diccionariodecarros)

#Recursividad

#def == crear una funcion
 
def factorial(i):
    if i == 0 or i == 1:
        return 1
    else:
        return i * factorial(i - 1)

numero = 5
resultado = factorial(numero)
print(f"El factorial de {numero} es {resultado}")

#f es para que sea de formato string y puedas meter valores de letras y numeros.

