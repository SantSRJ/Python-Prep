## Variables

# 1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla

mi_variable = 369
print(mi_variable)

# 2) Imprimir el tipo de dato de la constante 8.5

type(8.5)

# 3) Imprimir el tipo de dato de la variable creada en el punto 1

type(mi_variable)

# 4) Crear una variable que contenga tu nombre

mi_nombre = 'Santiago'

# 5) Crear una variable que contenga un número complejo

num_com = 36 + 9j

# 6) Mostrar el tipo de dato de la variable crada en el punto 5

type(num_com)

# 7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales

pi = 3.1416

# 8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?

var_1 = True
var_2 = True
# No son lo mismo, se trata de dos variables distintas que poseen el mismo valor Booleano.

# 9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 9

print('La variable var_1 es del tipo ', type(var_1), 'y la varoable var_2 es del tipo ', type(var_2))

# 10) Asignar a una variable, la suma de un número entero y otro decimal

a = 6 + 9.3
# 11) Realizar una operación de suma de números complejos

a = 3 + 6j
b = 9 + 3j
print(a + b)

# 12) Realizar una operación de suma de un número real y otro complejo

c = 9.6 + b

# 13) Realizar una operación de multiplicación

print(3 * 6)

# 14) Mostrar el resultado de elevar 2 a la octava potencia

print(2 ** 8)

# 15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla

a = 27 / 4
print(a)

# 16) De la división anterior solamente mostrar la parte entera

print(27 // 4)

# 17) De la división de 27 entre 4 mostrar solamente el resto

print(27 % 4)

# 18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado

x = 6 * 4 + 3
print(x)

# 19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas

var_3 = 'Hello'
var_4 = 'World'
print(var_3 + var_4)

# 20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?

2 == '2' 
# Respuesta False, porque uno es una variable tipo int y el otro un String.

# 21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera

2 == int('2')

# 22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')

# El error es por el uso de la "," en vez de "." para separar la parte entera de la decimal.

# 3) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido

g = 3
g -= 2
print(g)

# 24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?

a = 1 << 2
# Un sistema de numeración es un conjunto de símbolos y reglas que permi­ten representar datos numéricos. Los sistemas de numeración actuales son sistemas posicionales, que se caracterizan porque un símbo­lo tiene distinto valor según la posición que ocupa en la cifra.

# 25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?

n = 2
m = '2'
o = n + m
# No se trata de variables del mismo tipo

n = str(2)
m = '2'
o = n + m

n = int('2')
m = 2
o = n + m
# Si bien en ambos casos imprime 22, una variables es de tipo String y la otra Integer. No son lo mismo.

# 26) Realizar una operación válida entre valores de tipo entero y string

x = 'Santiago Mendoza'
z = 3
print(x * 3)