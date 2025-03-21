
LEER COMO CODIGO PARA QUE SE MAS ENTENDIBLE
CLASE 1
EJERCICIOS DE DESCOMPOSICION 
PROBLEMA:hacer una hamburgesa 
1.alistar los ingredientes que ban a ser,tomates,cebollas,carne y pan 
2.lavar los tomates y cebollas 
3.cortar la cebolla y los tomates en rebanadas 
4.colocar las rebanadas en un plato
5.preparar las bolas de carne 
4.encender el sarte y agregarle aceite 
6.poner los panes en el sarten para que se doren 
7.sacarlos y ponerlos en un lugar seguro 
8.despues poner la carne y esperar a que este en el punto deseado
9.sacar la carne 
10.alistar los panes para empezar a armar la hamburguesa 
11.colocar el primer pan de abajo
12.colocar los tomates 
13.colocar la carne 
14.colocar la cebolla 
15.por ultimo colocar el pan de arriba y cerrar la hamburguesa

EJERCICIO DE ABSTRACCION 
El funcionamientop de un semaforo sin mencionar detalles internos del circuito electrónico
1.el semaforo cambia su color a rojo en este estado los peatones no pueden pasar 
2.el semaforo cambia su color a amarillo en este estado falta poco para para que los peatones puedan pasar
3.el semafore cambia su color a verde en este estado los peatones pueden pasar 

EJERCICIO DE MODELADO  

![WhatsApp Image 2025-03-19 at 10 11 30 PM (1)](https://github.com/user-attachments/assets/dce59f84-770e-45d8-8653-23abefaafaab)

EJERCICIO DE PATRONES
3, 5, 4, 6, 5, 7, 6, 8,_
del 3 al 5 se suman dos, luego del 5 al 4 se resta 1 y haci consecutivamente
RTA: 7




CLASE 2
EJECICIO 1:pseudocodigo determinar par y impar 
INICIO
DECLARAR numero COMO ENTERO
numero  <- 0
ESCRIBIR "ingrese un numero"
LEER numero
SI numero % 2  <- 0 ENTONCES 
ESCRIBIR "el numero es par"
SINO
ESCRIBIR"el numero es impar"
FIN SI 
FIN

EJERCICIO 2:Inscripcion en una plataforma en linea
![WhatsApp Image 2025-03-19 at 10 53 03 PM](https://github.com/user-attachments/assets/6337cbcb-0a9a-4c67-941e-e2dc4c412833)


EJERCICIO 3
1.ANANLISIS:
si se tiene que revisar cada dato de la lista esto podria requerir de demasiado tiempo, por esta razon es fundamental que el tiempo se proporcinal a la lista por eso la notacion big O que se nesesita es:O(n) en este caso el nivel de eficiencia es alto por que cumple con los factores clave 

2.ANALISIS:
En este 
3.ANALISIS:



EJERCICIO 4:algoritmo que calcule el factorial de un numero 
INICIO
factorial=1
DECLARAR factorial,numero COMO ENTERO
ESCRIBIR "ingrese un numero"
LEER numero 
PARA i DESDE 1 HASTA numero HACER 
factorial <- factorial * i
FIN PARA 
ESCRIBIR"el factorial de",numero,"es:",factorial 
FIN 




CLASE 3
EJECICIO 1
INICIO
DECLARAR edad COMO ENTERO
edad <- 37

EJERCICIO 2 
INICIO
(4+3*2)>(3+3)
(10>6) verdadero o true

EJERCICO 3
Para convertir 13 a numero binario tenemos que dividirlo entre 2 y tenemos que guardar el resultado del residuo y cociente, luego dividimos el cociente por 2 nuevamente y seguimos dividiendo hasta que el cociente sea cero.Por ultimo ubicamos los resultados de abajo hacia arriba 

CONVERSION: 
(13/2 <- 6)residuo (1)
(6/2 <- 3)residuo (0)
(3/2 <- 1)residuo (1)
(1/2 <- 0)residuo (1)
RESULTADO:1101

EJERCICIO 4
10 Y 20
SI numero >=10 && numero<=20 ENTONCES esta entre 10 y 20 
numero <- "15" esta entre 10 y 20 
numero:verdadero 
El AND conprueba que si ambas condiciones se cumplen la expresion es verdadera  


EJERCICIO 5

ENTRADA
par
impar 

PROCESO
si dividimos un numero entre dos y su residuo es cero entonces en numero es par de lo contrario este es impar 
13/2<- 1 
13<-impar 
6/2<-0
par
SALIDA
mostrar los numeros impares y pares 

CLASE 4

EJECICIO 1
ALGORITMO 

ENTRADA
escribir
leer 
nombre
mensaje 

PROCESO
ESCRIBIR"por favor, escriba su nombre:"
LEER nombre 
ESCRIBIR"hola, ",nombre

SALIDA 
mostrar el mesaje al usuario

EJERCICIO 2
PROGRAMA
INICIO
DECLARAR numero,positivo COMO ENTERO
REPETIR
ESCRIBIR"ingrese un numero positivo(> 0):"
LEER numero 
HASTA QUE numero sea > 0
FIN
EJERCICIO 3

ENTRADA
escribir 
leer
suma
num1, num2, num3, 

PROCESO 
escribir "ingrese tres numeros2
leer num1, num2, num3
suma<- num1+num2+num3

SALIDA
mostrar el resultado de la suma 

EJERCICIO 4

DECLARAR edad COMO ENTERO 
REPETIR 
ESCRIBIR"ingrese su edad:"
LEER edad
SI edad es <= 0 entoces 
ESCRIBIR"edad debe ser mayor a 0"
FIN SI 
HASTA QUE edad sea > 0
ESCRIBIR"la edad fue registrada satisfactoriamente:",edad
FIN

EJERCICIO 5
DECLARAR a, b producto COMO ENTEROS
ESCRIBIR"ingrese dos numeros
LEER a, b
producto <- a * b
ESCRIBIR"el producto de la multiplicacion es:",producto
FIN
PASO        INCOGNITA      Y       RESULTADO      SALIDA EN PANTALLA
1                                                "ingrese dos numeros" 
2                5         5
3                5         5           8 
4                                                   "el producto es:"



EJERCICIO 6

INICIO
DECLARAR par,impar,numero COMO ENTERO
numero <- 0
REPETIR 
ESCRIBIR"ingrese un numero (no pueden ser carateres especiales o cualquier otro simbolo)"
LEER numero 
HASTA QUE el usuario ingrese solo numeros 
ESCRIBIR"el numero ingresado es:",numero 
SI numero MOD 2 <- 0 ENTOCES HACER
par <- par + 1
SINO
impar <- impar + 1
FIN SI 
ESCRIBIR"el numero par es:",par,"el numero impar es:",impar 

FIN 

