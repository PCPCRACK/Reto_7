# Reto_7
1. Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
```python
if __name__ == "__main__":
    n = int(1) #inicializa a n en 1
    while n <= 100:
        
        """Mientras el valor de n sea menor o igual a 100, se
        va a repertir el print y se le sumara 1 a n cada vez
        que se repita el ciclo"""
        
        print("El cuadrado del número ",n," es", n**2) #se eleva el numero dentro del print
        n +=1 #se le suma 1 a n cada ciclo
```
2.  Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
```python
if __name__ == "__main__":
    n = 1 #inicializa n en 1
    print ("un listado con los números impares desde 1 hasta 999") #se ejecuta antes de iniciar el ciclo
    while n < 1000: #mientras n sea menor que 1000
        if n%2 > 0: #compara si el valor del la divion por residuo de n es mayor a cero
            print (n) #imprime el valor de n en cada ciclo
        n += 1 #suma 1 al valor de n
        
    n = 2 #cambia el valor de n a 2
    print("listado con los números pares desde 2 hasta 1000.") #se ejecuta antes de iniciar el ciclo
    while n <= 1000: #mientras n sea menor o igual que 1000
        if n%2 == 0: #compara si el valor del la divion por residuo de n es igual a cero
            print (n) #imprime el valor de n en cada ciclo
        n += 1 #resta 1 al valor de n
```
3.  Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado
```python
if __name__ == "__main__" :
    n = 1000 #inicializa n en 1000
    print("números pares en forma descendente hasta 2") #se ejecuta antes de iniciar el ciclo
    while n>1: #mientras n sea mayor que 1
        print(n) #imprime el valor de n en cada ciclo
        n -= 1 #suma 1 al valor de n
```
4. En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18:9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a
la de A.
```python
if __name__ == "__main__" :
    PA = 25000000 #inicializa PA en 25000000
    PB = 18900000 #inicializa PB en 18900000
    año = 2022 #inicializa año en 2022
    while PA>=PB : #mientras PA sea mayor o igual que PB
        print("Poblacion del pais A ",PA," mientas que el pais B tiene ",PB," en el año ",año)
        PA *= 1.02  #se le aumenta el 2 % cada ciclo
        PB *= 1.03 #se le aumenta el 3 % cada cilco
        año += 1 #suma 1 al valor de año
    print("Poblacion del pais A ",PA," mientas que el pais B tiene ",PB," en el año ",año) 
    """ se ejecuta al terminar el ciclo 
    con los valores finales de PA,PB y año"""
```
5. Imprimir el factorial de un número natural n dado.
```python
if __name__ == "__main__" :
    n = int(input("Numero factorial ")) #se ingresa el valor de n
    f = n #inicializa f en n
    while n > 1 : #mientras n sea mayor a 1
        n -= 1 #se le resta 1 a n para que no se multiplique por si mismo la primera vez
        f *= n #se multiplica el valor inicial f por el mismo valor menos 1 osea n
    print("El valor factorial es ",f) #se ejecuta al terminar el ciclo 
```
6. Implementar un algoritmo que permita adivinar un número dado de 1 a 100, preguntando en cada caso si el número es mayor, menor o igual.
from random import randint
```python
from random import randint

if __name__ == "__main__" :
    f = randint(1,100) #se elije un valor aleatorio para f
    n = int(input("Adivina el numero del 1 al 100 ")) #se ingresa el valor de n
    while n != f : #se compara en caso de que n sea igual f
        if n < f : #si n es menor que f
            print("el numero es mayor ")
        else: #sino
            print("el numero es menor ")
            n = int(input("intenta otra vez ")) #se sobreescribe el valor de n y se compara
print("acertaste el numero era ",f) #se ejecuta al terminar el ciclo con el valor final de f
```
7. Implementar un programa que ingrese un número de 2 a 50 y muestre sus divisores.

from random import randint
```python
if __name__ == "__main__" :
    n = int(input("ingrese un número de 2 a 50 ")) #se ingresa el valor de n
    i = 1 #se establece un contador
    while i <= n : #mientras i sea menor o igual n
        if n%i == 0 : #si n es divisible por i por residuo igual a 0
            print(i) #se imprime i
        i +=1 #se le suma 1 en cada ciclo
```
8. Implementar el algoritmo que muestre los números primos del 1 al 100. **nota:** use funciones
```python
def Esne(n : int,):
        i = int(2) # se establece un contador en 2
        if n == 2 : #si es dos 
            print(n)
        while i < n : #mientras i sea menor a n
            if n%i == 0: #si n es divisible por i y de residuo igual 0
                break #se rompe el ciclo
            elif i == n-1: #si i es igual n-1
                print(n) 
            i += 1 #se le suma 1 en cada ciclo

if __name__ == "__main__" :
    n = int(2) #inicializa n en 3
    T = 100 #inicializa T en 100
    while n < T: #mientras n sea menor que T
        a = Esne(n) #se llama la funcion
        n += 1 #se le suma 1 en cada ciclo
```
