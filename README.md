# Ejercicios pseudocódigo/diagrama flujos 

### A continuación, se deben realizar el pseudocódigo y el diagrama de flujo de 
los siguientes enunciados. Se puede utilizar herramientas como PSeInt para 
realizar los ejercicios y verificar el correcto funcionamiento del algoritmo 
planteado. 

**1.** Hacer un pseudocódigo que imprima los números del 100 al 0, en 
orden decreciente. 
```
Algoritmo contador_inverso
	contador<-100
	Mientras contador>=0 Hacer
		Escribir contador
		contador=contador-1
	Fin Mientras
FinAlgoritmo

```
**2.** Hacer un pseudocódigo que imprima los números impares entre 0 y 100. 

```
Algoritmo contador_impares
	contador<-0
	Mientras contador<=100 Hacer
		Si contador%2<>0 Entonces
			Escribir contador
			contador=contador+1
		SiNo
			contador=contador+1
		Fin Si
	Fin Mientras
FinAlgoritmo

```

**3.** Hacer un programa que imprima la suma de los 100 primeros números. 

```
Algoritmo contador_suma
	contador<-0
	Mientras contador<=100 Hacer
		numSuma=numSuma+contador
		contador=contador+1
		Escribir numSuma
	Fin Mientras
FinAlgoritmo
```

**4.** Hacer un pseudocódigo que imprima todos los números naturales que hay desde el 0 hasta un número que introducimos por teclado. 
```
Algoritmo imprimir_naturales
	contador<-0
	Escribir "Escribe un numero natural"
	Leer numUsuario
	Mientras contador<=numUsuario Hacer
		Escribir contador
		contador=contador+1
	Fin Mientras
FinAlgoritmo
```

**5.** Introducir un numero por teclado. Que nos diga si es positivo o negativo. 
```
Algoritmo positivo_negativo
	Escribir "Escribe un numero"
	Leer numUsuario
	Si numUsuario<0 Entonces
		Escribir numUsuario, " es negativo"
	SiNo
		Escribir numUsuario, " es positivo"
	Fin Si
FinAlgoritmo

```

**6.** Programa donde introducimos tantas frases como queramos (el usuario) y contarlas. 

**7.** Imprimir y contar los múltiplos de 3 desde 0 hasta un número que introducimos por teclado.

```
Algoritmo multiplos_tres
	Escribir "Escribe un numero"
	Leer numUsuario
	contador<-0
	Mientras  contador<=numUsuario Hacer
		Escribir 3*contador
		contador=contador+1
	Fin Mientras
FinAlgoritmo

```

**8.** Hacer un pseudocódigo que imprima el mayor y el menor de una serie de cinco números que vamos introduciendo por teclado. 

**9.** Introducir dos números por teclado. Imprimir los números naturales que hay entre ambos números empezando por el más pequeño, 
contar cuantos hay y cuantos de ellos son pares. Calcular la suma de los impares. 

**10.** Imprimir diez veces la serie de números del 1 al 10.
