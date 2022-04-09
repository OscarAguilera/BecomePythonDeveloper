# BecomePythonDeveloper

## Sintaxis 
Se refiere al conjunto de reglas que definen como se debe escribir el codigo en determinado lenguage.

## Lenguajes
En la mayoria de los lenguages existe una sintaxis comun, como el uso del signo = para asignar un dato a una variable, asi como el uso de {} para designar bloques, pero en Python contamos con ciertas particularidades.
Python no soporta el uso del signo $ y tampoco hace falta terminas las lineas con ; como en algunos lenguajes, asi como no es necesario el uso de {} dentro de un bloque IF

La sintaxis en programacion tiene el mismo sentido que la gramatica en los idiomas, es decir por ejemplo la frase "Yo programar aprender estoy" no es correcta, ya que no respeta las normas del lenguaje, de igual manera el siguiente bloque en Python no es correcto.

if($variable){
  x=9;
}

## Ejemplos:
La sintaxis de Python es muy parecida al pseudocódigo, por lo cual es relativamente mas fácil de leer y no necesita nada mas para ejecutar el codigo, como en java o c en los cuales se ocupa crear la funcion main(). Algunos ejemplos

### Asignar o definir una variable tipo string, es decir asignar un valor de cadena a una variable:
x= "El valor de (x+z)*y es"

### Podemos asignar multiples asignaciones:
x,y,z = 6, 8, 9

### Podemos hacer operaciones aritmeticas en asignaciones:
w= (x+z)*y

### Asignar variables booleanas:
hola = true

### IF
if imprimir:
    print(x, w)

### Comentarios
En python el comentario inicia con un signo de # y todo lo que vaya despues del signo hasta el final de la linea se considera un comentario, o de igual manera podemos usar las doble comillas triple *"""* o las comillas simple *'''*, pero tenemos que abrir con las mismas y cerrar con las que inicias, es decir por ejemplo:
*"""*
Esto seria un comentario de la linea
y seguiria siendo
un comentario hasta
que ponga las otras comillas como abajo
*"""*

### Identacion y bloques de codigo:
En python los bloques de codigo llevan identacion, es decir por norma general se debe usar cuatro espacios por ejemplo:

if True:
    print("True")

En el segmento de arriba el bloque if tiene un print identado a 4 espacios, que indica que el print pertenece al bloque if, y si no tuviera identacion, es decir si fuera como:

if True:
print("True")

Lo anterior daria error ya que el if no tiene ningun bloque de codigo y en python no se puede hacer eso.
Para terminar una linea de codigo solo basta con poner un salto de linea (enter), y aunque no usamos el ; para terminar una linea de codigo, lo podemos usar para tener 2 sentencias en la misma linea, es decir *x=1; z=2*

### Creando Variables

Como ya mencionamos la forma de crear una variable y asignarle el valor usando el signo de *=* pero tambien existen otras formas de hacerlo de una manera un poco mas versatil, por ejemplo:

x = y = z = 10

De igual manera podemos asignar varios valores separados por coma:

 x,y = 4, 2 
 z, x, y = 1, 2, 3 

### Nombrando Variables

Ya vimos como crear y asignar pero no hemos mencionado como debemos de crear los nombres para las variables ya que existen unas cuantas normas para hacerlo:


