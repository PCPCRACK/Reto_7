# Reto_7
1. Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
```python
if __name__ == "__main__":
    n = int(1) #inicializa a n en 1
    while n <= 100:
        
        """Mientras el valor de n sea menor o igual a 100, se
        va a repertir el print y se le sumara 1 a n cada vez
        que se repita el ciclo"""
        
        print("El cuadrado del número ",n," es", n**2)
        n +=1
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
        n += 1 #suma 1 al valor de n
```
3.  Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado
4. En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18:9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a
la de A.
5. Imprimir el factorial de un número natural n dado.
6. Implementar un algoritmo que permita adivinar un número dado de 1 a 100, preguntando en cada caso si el número es mayor, menor o igual.
7. Implementar un programa que ingrese un número de 2 a 50 y muestre sus divisores.
8. Implementar el algoritmo que muestre los números primos del 1 al 100. **nota:** use funciones
