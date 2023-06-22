## PROYECTO FINAL EQUIPO 3

* Chávez Soto Leslie Vanessa
* Maldonado Bedolla Daniela Del Carmen
* Monroy Cerón Lizeth
* Ramírez Ramírez Arlette Guadalupe
* Sandoval Rodríguez Laura Aide

Este programa está desarrollado para hacer la conversión de un número decimal a un número en sistema binario y viceversa (de sistema binario a sistema numérico decimal) 

# Decimal a Binario y de Binario a Decimal


El sistema binario es una técnica de numeración donde solo se utilizan dos dígitos, el 0 y el 1.
Para pasar un número del sistema decimal al binario debemos dividirlo entre 2 hasta que el dividendo sea menor que 2, considerando los residuos, como vemos a continuación:

37/2=18 residuo 1

18/2=9 residuo 0

9/2=4 residuo 1

4/2 =2 residuo 0

2/2=1 residuo 0

último cociente: 1

Tomamos entonces los residuos y el último cociente en orden inverso y obtenemos que 37 equivale a 100101 en el sistema binario.

Lo anterior se puede expresar de la siguiente forma:

![image](https://github.com/NessaChavez/Decimal-a-Binario/assets/137378640/3253319b-a54a-433b-885c-c5e185becf68)

Asimismo, para cambiar del sistema binario al decimal se tendría que multiplicar cada dígito por 2 elevado por la respectiva potencial. Es decir, volviendo al ejemplo de arriba sería:

(1*(2^5))+(0*(2^4))+(0*(2^3))+(1*(2^2))+(0*(2^1))+(1*(2^0))= 32+0+0+4+0+1= 37

## INSTRUCCIONES DE EJECUCIÓN 
* Para que el programa funcione sin problema es necesario utilizar un compilador de lenguaje C o C++

## CARACTERÍSTICAS DEL PROGRAMA

* El usuario va a ingresar algún número decimal que quiera convertir a sistema binario
* Se arrojará el resultado con números binarios
* El usuario ingresara un número en sistema binario
* El programa arrojara el número en sistema numérico decimal
