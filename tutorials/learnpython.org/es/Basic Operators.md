Tutorial
--------

esta sección explica un poco sobre como usar los operadores básicos en Python. 

### Operadores Aritméticos  


Tal como cualquier otro lenguaje de programación, los operadores de sumas, restas, multiplicaciones y divisiones pueden ser usadas con números.<br> 

    numeros = 1 + 2 * 3 / 4.0

Intenta predecir la respuesta. ¿Python sigue el orden de los operadores?

Otro operador disponible es el de modulo (%), este regresa el integral remanente de una división. dividendo % divisor = remanente.

    remanente = 11 % 3

Usando dos simbolos de multiplicación crea una relación de potencia.

    cuadrado = 7 ** 2
    cubico = 2 ** 3

### Usando operadores con texto

Python soporta unir texto usando el operador de adición:

    holamundo = "hola" + " " + "mundo"

Python también soporta multiplicar texto o cadenas para formar una cadena con una secuencia repetitiva:

    muchosholas = "hola" * 10

### Usar Operadores con listas

Las listas pueden ser unidas con los operadores de adición:

    even_numbers = [2,4,6,8]
    odd_numbers = [1,3,5,7]
    all_numbers = odd_numbers + even_numbers

Al igual que en las cadenas, Python admite la formación de nuevas listas con una secuencia repetitiva utilizando el operador de multiplicación:

    print [1,2,3] * 3

### Ejercicios

El objetivo de este ejercicio es crear dos listas llamadas lista_x y lista_y, las cuales contienen 10 instancias de las variables "x" y "y", respectivamente. También es necesario crear una lista llamada "lista_grande", que contiene "x" y "y", 10 veces cada una, concatenando las dos listas creadas.

Tutorial Code
-------------

x = object()
y = object()

# cambia este código
lista_x = [x]
lista_y = [y]
lista_grande = []

print "lista_x contiene %d objetos" % len(lista_x)
print "lista_y contiene %d objetos" % len(lista_y)
print "lista_grande contiene %d objetos" % len(lista grande)

# probando el código
if lista_x.count(x) == 10 and lista_y.count(y) == 10:
    print "Cerca..."
if lista_grande.count(x) == 10 and lista_grande.count(y) == 10:
    print "¡Buen trabajo!"

Expected Output
---------------

lista_x contiene 10 objetos
lista_y contiene 10 objetos
lista_grande contiene 20 objetos
Cerca...
¡Buen trabajo!

Solution
--------
