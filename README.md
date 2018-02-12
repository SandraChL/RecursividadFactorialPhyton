# RecursividadFactorialPhyton
El factorial de un número es la multiplicación de los número que van del 1 a dicho número. Para expresar el factorial se suele utilizar la notación n!.


Codigo Phyton Factorial 

1)
print(6 * 5 * 4 * 3 * 2 * 1)

2)
from math import factorial
factorial(5)

3)
def factorial(x,n):
 if(n>0):
  x=factorial(x,n-1)
  x=x*n
 else:
  x=1
 return x
n=int(input("ingresa un numero  \n"))
x=1
x=factorial(x,n)
print (x)




## los resultados de cada uno vienen en la imagenes integradas (captura de pantalla)
