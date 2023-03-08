## - Variables -

1. Has hecho una compra y sabes el precio del producto y su iva. Haz un script que te calcule el precio total que vas a pagar por tu compra. 
	Te recuerdo que para calcular el total debes sumar al precio el resultado de multiplicasr precio por el iva y dividir por 100.

> Precio 100€
> 
> Iva: 21%
> 
> El total son 121 €.

2. En una variable tienes el lado de un cuadrado, debes escribir un programa que te calcule el área y el perímetro del cuadrado.
	El area la calculas como lado multiplicado por lado. El perímetro es la suma de los cuatro lados.
	
> Lado 40
> 
> El area es 1600 
> 
> El perímetro es 169

3. Un poco de interactividad. En este ejercicio debes escribir un programa que lea el nombre del usuario y salude con un "Hola" seguido del nombre del usuario.
	Para leer el nombre usa un prompt con un texto indicativo como _"Escribe tu nombre"_

> Aparecerá el prompt y el usuario escribirá su nombre:
> 
> Usuario escribe Juan. 
> 
> Hola Juan.

4. En este ejercicio vas a pedir al usuario que teclee tres números enteros y el script mostrará como resultado el valor medio de los tres.
	Recuerda que la media de tres números se calcula sumando los tres y dividiendo entre 3.
> Si el usuario teclea:
> 
> 3  
> 
> 2  
> 
> 4
> 
> La media de los números es 3.

5. Escribe un programa que solicite al usuario ingresar el número de litros consumidos por su coche, luego le pide el número de kilómetros recorridos. El script debe mostrar el consumo de combustible por kilómetro.
	Un problema matemático muy simple, numero de litros dividido por número de kilómetros.
	
>El usuario teclea
>
>Num de litros: 20
>
>Num de kilómetros: 80
>
>Has consumido 4 l/km


6. Cambio de unidades. en este ejercicio debes convertir a segundos una medida de tiempo dada en horas y minutos. 
	Recuerda una hora son 6o minutos y cada minuto son 60 segundos.
	
>horas : 2
>
>minutos 30
>
>Resultado 2*60*60 + 30*60 = 9000 segundos

7. En este script debes pedir al usuario un programa de dos dígitos y debes devolver el número de unidades y de decenas, o sea, cada dígito del número.
	Recuerda si divides un número entre 10 el cociente entero es el número de decenas y el resto es el número de unidades

> Si ese teclea el número 45
> 
> Unidades: 5
> 
> Decenas: 4

8. Una tortilla de patatas lleva 200 gramos de patatas por persona. Por cada kilo de patatas se necesitan 5 huevos y 300 gramos de cebolla. Escribe un script que dado el número de comensales calcule las cantidades de ingredientes necesarias

> 5 comensales 
> 
> Se necesitará:
> 
> 1 kg de papas
> 
> 5 huevos
> 
> 300 gr de cebolla

9. Este ejercicio es todo un clásico si lo haces a la primera y sin tardar mucho, puedes estar seguro: entiendes las variables.
	Tenéis que escribir un programa que intercambie el valor de dos variables. Al final la primera variable debe terner el valor de la segunda y la segunda el valor de la primera.
>Antes:
>
>**varUno** vale 10, **varDos** vale 30
>
>Al final
>
>**varUno** vale 30, **varDos** vale 10

10. No todo van ser números. Escribe un código que dado un número nos devuelva true si es un número par y false si es un número impar. No usar condiconales.

>numero: 50 
>
>¿Es par? : true  
  
---

## -Condicionales - 

1. Se trata de escribir un script que diga si un número es par o es impar.
	Recordemos que un número es par si al dividirlo por 2 da como resto 0.

> Si el número es 17, el programa debe decir que es impar.

2. Un programa que pida un número y diga si es positivo o negativo. El cero se considera positivo

> Si num1 es 2 debe decir que num1 es positivo

3. En este ejercicio debes pedir dos números enteros y devolver el cociente de dividir el primero entre el segundo, pero si este es cero no debe hacer la división, sino lanzar un mensaje de error

> Si se entran el número 8 y 2, debe resultar 4
> 
> Si se entran 4 y 0, dbe resultar en un mensaje de error.

4. Este script pide al usuario que teclee una letra entre A, B, C, D. Si pulsa la letra A en mayúsucla o en minúscula le dará el mensaje de que ha acertado, en caso contrario le dirá que se equivocó...

> Si pulsa C le dará mensaje de error.

5. En este ejemplo el usuario entrará dos números. Debe devvolver la diferencia entre el mayor y el menor.

> Si el usuario entre el 5 y el 8, el programa devolverá 3 (8 - 5)

6. Este ejercicio dirigirá a los clientes a la barra de bebidas o a la de comidas, para ello el cliente puede pedir vino, cerveza, refresco, agua. Si pide un cerveza o vino se le dirige a la barra y si no pues se le dirige a la tienda.

> Un cliente elige vino, aparecerá el mensaje vaya a la barra, en caso contrarío dirá que vaya a la tienda.

7. Este programa te ayuda a viajar. El programa pide al usuario si va a viajar con coche, tren, bicicleta o autobús. Si va en tren o autobus le recordará que lleve dinero para el billete.

> El cliente pide ir en tren, aparecerá el mensaje "lleva dinero para el ticket"

8. En un tramo de un rally los conductores no deben ir ni demasiado rápido ni demasiado lentos. Este ejercicio debe tomar la longitud del tramo en kilometros y el tiempo empleado, si la velocidad está entre 40 y 60 km/h el conductor pasa la prueba en caso contrario es descalificado.

> Ejemplo si recorre 100 km en 4 horas, ha ido a una velocidad de 100/4 que son 25km/h. Estaría descalificado.

9. Una tienda aplica un descuento del 15% para las compras que incluyan más de 10 artículos iguales cuyo precio sea superior a 40 euros. Tu programa debe comprobar y calcular la cantidad a pagar sabiendo el número de artículos y el precio de cada uno.

>Por ejemplo si compras 20 artículos de 10 euros se te descuenta un 15% del total pagarías 20*10 - 20*10*0.15 = 170 eruos.

10. Crea un programa que pida la nota de un estudiante en los tres trimestres del curso y calcule la nota promedio. El resultado que dará será suspenso si la media es menor de 5, aprobado si está entre 5 y 7 y  Notable por encima de 7.

> Para las notas 6, 8, 10 la media es 8 por tanto se califica como Notable

---

## - Condicionales 2ndo bloque -

1. El usuario debe introducir dos valores numéricos por teclado y la aplicación deberá indicar cual es el mayor, el primero o el segundo.  
La idea es usar las sentencias if reducidas (cond ? true:false)

> Si el usuario entra 2 y luego 4, debe decir que el mayor es el segundo número.

2. El usuario debe entrar un número y su cuadrado. Si es correcto el script enviará un mensja ede acierto en caso contrario dirá que se produjo un error.  
Se trata de usar el if resumido (cond?true:false)

> Por ejemplo si teclea 3 y 9 el resutlado es Correcto. Si tecleo 3 8, el resultado será Error

3. En ste caso, también suando el perador ternario o if reducido, un visitante a la página deberá teclear su edad, si es igual o mayor de 18 recibirá el mensaje de "Entra" en caso contario deberá decirle los años que tiene que estperar para entrar

> Si le digo que tengo 19 años me dirá "Puedes entrar", si le digo que tengo 14 años me dirá "Espera 4 años"

4. En un restaurante los clientes pueden pedir menú de carne, pescado o verdura. Si pide carne se le ofrecerá como bebida vino tinto, si pide pescado se le ofrecerá vino blanco y si pide verdura se le ofrecerá agua  
Si no elije el menú de la lista aparecerá la frase elija carne, pescado o verdura.

> Por ejemplo he pedido carne, el ejercicio mostrará "¿Desea beber vino tinto?"

5. En una sala de juegos existen tre salas: Consolas, Juegos 2D, Juegos 3D, Realidad Virtual. Si un usuario paga  4 créditos puede acceder a todas, si apga 3 solo podrá acceder a las tres primeras, si paga 2 a las dos primeras y si paga 1 solo a la primera sala.

> Tecleo que pago 2 créditos, el escript me dirá que puedo acceder a las salas de consola y juegos 2D.

6. A partir de un número de mes tecleado por un usuario el programa debe indicar la estación del año.  
Las estaciones serán 12,1,2: Invierno. 3,4,5 primavera, 6,7,8 verano y 9,10,11 otoño.

> i tecleo el 3 el script me responderá que estamos en Primavera

7. En este ejercicio el usuario entra la longitud de la base y el alto de un cuadrado. Si la base y el alto son idénticos la respuesta será "Es un cuadrado", si la base es mayor que el alto dira "Rectángulo horizontal" y en caso contrario dirá "Rectángulo vertical".

> Si entro base es 10, alto es 5. Resultado rectángulo

8. En una tienda coches se quiere redirigir a un cliente a una sección de acuerdo al tipo de coche que elija. Si elige tipo gasolina o 1 se le enviará a la oficina numero 100. Si elije el tipo diesel o 2 irá a la oficia 200 y si elige electrico o 3 se le enviará a la ofician 300.

> Por ejemplo tecleo el número 2, el mesnaje me dirá que vaya a la oficina 200

9. Un comerciante hace descuentos a sus clientes de la siguiente forma:  
Si ha comprado menos de 100 euros no hay descuento  
Si la compra está entre 100 y 300 euros le descuenta un 5%  
Si la compra está por encima de 300 hasta 500 euros le descuenta un 10%   
Si la compra supera los 400 euros le descuenta un 15%

> Es decir: hago una compra de 150 euros pago 150 - 5% de 150, o sea 142,5 euros.

10. En este ejercicio el script convertirá las notas numéricas de un examen en paabras: 0 - 4 suspenso, 5-6 aprobado, 7-8 notable, 9-10 sobresaliente.

> Si tecleo 8 me dirá "Tu calificación es  notable"

---

## - Bucles For - 

1. Usando un bucle for escribir un script que pida un valor entero y muestre en pantalla una lista de números desde el 0 al valor tecleado. Los números se separarán por comas.  

> Si el usuario entra por teclado el número 5 el script devolverá la secuencia  0, 1, 2, 3, 4, 5  

2. Se trata de que dado un número entero el script muesre una cuenta atrás, es decir, una lista de numeros separados por coma desde el número tecleado hasta el 0.

> Si tecle o número 5 deberá mostarar 5,4,3,2,1.

3. Se quiere un bucle que genere una lista con todos los números pares positivos por debajo del número tecleado por el usuario. Los números se aparecerán en una ventana alert con cambios de linea (carácter '\n').

> Si tecleo el número el número 9 deberá mostrar cinco lineas con los números 0 2 4 6 8

4. Este script debe escribir la tabla de multiplicar del número que el usuario teclee. La tabla mostrará en diferentes líneas cada producto y el resultado en la forma a x b = ab.  
Recuerda que el salto de linea es el carácter "\n"

> Si el usuario teclea el 4 la tabla mostrará diez líneas en la forma 
 4 x 1 = 4
 4 x 2 = 8...


5. En este ejercicio mezclamos bucles on condicionales: el usuario escribe un número y el script imprimirá (console.log) todos los números menores que al dividirlos por 3 den como resto 2.  
Recuerda: un número es múltiplo de N es cuando el dividirlo por N el resto es 0.

> Por ejemplo si tecleas el 14, obtendré la lista 2, 5, 8 y 11

6. Este script el usuario deberá teclear una letra y un número, y el programa mostrará una cadena formada por la letra repetida el número que haya tecleado.

> Si el usuario teclea x y 5 el script mostrará xxxxx. O sea una cadena de 5 letras x

7. Se quiere tener un contador de dos dígitos en base 5. El funcionamiento es simple: el dígito de la derecha irá aumentando y cuando pase de 4 su valor se pondrá a 0 y el dígito de la izquierda se incrementa en 1. El contador debe deternerse cuando alcancemos el valor 1:4

> Usamos el console log para ir imprimiendo los valores de los dígitos, deberá quedar algo así:  
0:0  
0:1  
0:2  
...  
...  
1:4 será el final del conteo

8. Se trata de dibujar un triángulo con asteriscos. El usuario tecleará un valor entero, el programa escribirá con asteriscos tantas lineas como diga ese número. Cada linea estará formada por una serie de astericos tan larga como diga el número de línea en el que está.  
	Para separar una linea de la siguiente en console o en alert debes usar "\n". En este ejercicio usa console.log.

> Le tecleamos el valor 5. El resultado será:   
```
*  
** 
***  
****  
*****
```

9. Se trata de crear una aplicación que calcule la suma de todos los números enteros positivos entre 0 y el número tecleado por el usuario. El resultado será de la fomra "Los números enteros de 0 a n  suman suma"

> Si tecleo el 5 obtendré "Los enteros enteros de 0 a n suman 15" (1+2+3+4+5 ).

10. Programa un script que pida al usuario que teclee 4 números (uno cada vez). Con esos números el programa deberá calcular la media aritmética. O sea la suma de los 4 números dividida entre 4

> El progrma pide 4 veces al usuario que telcee un número y este escribe 5,9,10,12. El programa dirá "La media es 9"

---

## - Bucles While -

1. Usando un bucle while escribir un script que pida un valor entero y cree una lista con los números desde el 0 al valor tecleado. Luego deberá sacar esa lista con un alert. Los números se separarán por comas.  

> Si le doy el número 5 pues deberá contar 0,1,2,3,4,5

2. Se trata de pedir al usuario que teclee un número entre 1 y 5, si escribe alguno que esté fuera de ese rango deberá volver a pedir el número

> Si tecleo 0 me dirá Por favor teclee un número entre 1 y 5.

3. Un script que preguntará al usuario si desea continuar con el programa. Si el usuario pulsa una letra n (mayúscla o minúscula), el programa finalizará. Cualquier otra entrada repetirá la pregunta

> El usuario teclea Si, como no es la letra s pues dirá Error, ¿Desa seguir con el programa?

4. Determinar si el número que teclea el usuario es primo o no. Recordar que un número primo es el que solo puede dividirse por si mismo y por la unidad.

> Si el usuario teclea el 3: dirá que 3 es primo. Si teclea el 4 dirá que 4 no es primo.

5. Escribir un script que pida al usuario una contraseña. Si coincide le devolverá el mensaje "Acceso concedido" y si no coincide le deolverá el mensaje "Acceso Denegado" . Solo falla tres veces se emitirá el mensaje "Alerta, intruso"

> La contraseña es por ejemplo pasar. Tecleo tres veces otra distinta: Acceso Intruso.

6. En este script se pedirá al usuario que teclee un número cada vez. El proceso acaba cuando teclee un 0 en cuyo caso además mostrará la suma de todos los números tecleados.

> El usuario teclea primero el 4 luego el 5 depsués 6 y finalmente , 0. El programa se para y muestra "La suma de todos los número es 15"

7. Este script le pide al usuario que vaya tecleando números enteros positivos hasta que el usuario ingrese el 0. En esete caso el programa acaba mostrando el valor máximo y mínimo de los números tecleados.

> El usuario teclea la sere 4,2,3,5,0, El máximo es 5 y el minimo es 2. Si telcea 2,2,2,0, máximo es 2 y minimo es 2.

8. Este script le pide al usuario que vaya tecleando números una y otra vez, pero solo números pares, en caso de que teclee un número impar el programa acabará y dirá la cantidad de números pares ingresados (el 0 cuenta como par).

> Muestra Si escribo 2,8,12,1 el script me dirá "Ha escrito 3 números pares")

9. Este script muestra un menu de opciones: 1- Leer datos. 2- Mostrar datos 3- Fin. El usuario deberá teclear uno de ellos y el programa mostrará la opción elegida. Si teclea un valor fuera del menus se mostrará un mensaje de error y se vuelve a pedir un número de opción. El programa finaliza al teclear el 3.

> Pulso 1, mensaje Opción leeer datos. Y vuelve a pader opción. Pulso 4 : Error y vuelve a pedir opción, Pulso 3: Fin del programa y acaba

10. Un script pedirá al usuario que vaya tecleando números hasta llegar al 0, entocnes el programa muestra "La suma es " seguido de la suma de los números. Si esta suma es par el programa se repite y si es impar el programa acaba.

> Si tecleo 2,6,2, 0 Me dirá suma "10" y volverá a pedir otra serie de números, si tecleo 2,6,3 Me dirá "suma 11" y acabará.

---

## - Bucles Do...While -

1. Realiza un script que le pida al usuario que telee la letra A (en mayúscula) y mientras no lo haga se lo vuelva a pedir. Usa un bulce do..while y la ventana alert para los mensajes

> El usuario teclea b, el programa vuelve a pedirme que teclee una letra

2. Este script usará un bucle do while para determinar si un número es primo o no. El numero tecleado deberá estar entre 0 y 100. Si es primo lo mostrará en una ventana alert

> Si escribo 0 o 100 el programa me seguirá pidiendo un número

3. En este script vas a crear un menu con tres opciones: escribir, leer, ssalir. El usuario elegirá una opción y en un alert se le indicará la opción elegida. El programa vuelve a mostrar el menu y se repite el proceso. El script acabará cuando se pulse la opción de salir.

> El menu tiene 3 opciones, elijo la opción 2, respuesta "has elegido leer".

4. En este script se le pide al usuario que teclee dos números, el script mostrará la suma y pedirá al usuario si queire repetir. Si teclea S repite y si teclea N el programa sale. No acepta otras teclas

> Por ejemplo si tecleo 3 despues 9 me dirá que la suma es 12, y luego me preguntará si quiero repetir.

5. Usar un bucle do..while para crear una cadena que contenga letras repetidas. Las letras se entran por teclado y solo podrán ser la X o la Z despues de elegir las letras se le ingresa el número de repeticiones que deberá estar entre 1 y 15.

> Si elijo X y luego telco 10 se mostrará XXXXXXXXXX. Si tecleo z me olverá a pedir letra, y sitecelo 20 me volverá a pedir el número

6. En este sript se trata de calcular el máximo común divisor de dos números. El algorimto es simple: dividimos el primoer por el segundo. si el resto es cero este segundo es el mcm. Si no se desecha el primero y se repite el proceso con el segundo y el resto. Así mientras el resto no sea 0

> Si tecleo 20 y luego 10, el mcd es 10. Si tecleo 4 y luego 20 el mcd será 4. Si tecleo 20 y 8 el mcd es 4.

7. Este ejemplo debe pedir al usuario un  número entero y, mediante sucesivas divisiones por 10 debe escribir los digitos que lo forman de menor a mayor orden (de unidades hacia arriba) en una cadena separados por un espacio

> Si escribo 126 deberá responder  "Dígitos del número: 6 2 1"

8. Diseñar un script que pida un número mayor que cero y devuelva la suma de todos los números pares desde cero al número introducido. Mostrará la suma y volverá a pedir otro núero hasta que el usuario teclee un 0.

> Si tecleo el 10 mostrará 30 la suma de 2+4+6+8+10

9. Escribir un script usando el bucle do while para pedir que el usuario escriba dos números. Si el primero es mayor que el segundo el programa volverá a pedir que se escriban los números. Si el primero es menor o igual que el segundo el programa acaba y dice "Numeros en orden creciente"

> Si tecleo pimero un 12 y luego un 9, volverá a pedirme que escriba los datos. Si escribo un 12 y luego un 20 me dirá "Numeros ordenados"

10. Escribir un script para determinar si el numero introducido por el usuario es un palíndromo, es decir, un número que se lee igual del derecho que del revés.  
Para invertir el número podéis hacer sucesivas divisiones entre 10: el resto lo añadis al inveso multiplicado por 10. Y repetis con el valor entero del numero dividido por 10.

> Si escribo el número 12421 me dirá que "12421 es un palíndromo".

---

## - Arrays -

1. En este script deberás crear un array para guardar los nombres de los días de la semana, empezando por 0 para el domingo. Para comprobar el funcionamiento pide al usuario un número entre 0 y 6 y devuelve el nombre del día. Se supone que el dato tecleado estará entre 0 y 6

> Si tecleo el número 4 me deberá decir que el día de la semana es jueves

2. Crea un array booleano con dos valores 'verdadero' y 'falso'. Este array te sirve para traduicr los valores true y false. Usalo para que el script muestre un alert con el nombre vedadero si un usuario teclea un valor entre 0 y 9 y falso en el caso contrario.

> Por ejemplo al teclear 10 deberá devolver falso

3. Sin usar métodos del objeto array, diseña una función llamada sumaLista() capaz de sumar todos los números que forman el array que se le pase como argumento.

> Si ejecuto sumaLista([2,4,5,1,2]) deberá devolver como resultado 14

4. Diseña un script que vaya leyendo números y guardándolos en un array. Una vez lleno mostrará el array y deberá decir cuantos números son pares y cuantos son impares. La entrada de datos termina cuando el usuario teclea 0 o un valor no numérico.  
Intenta resolverlo sin usar métodos del objeto array, solo indices y longitudes de arrays.  
No debe aceptar valores no numéricos (isNaN(valor) permite detectar valores no numéricos).

> Por ejemplo si tecleo: 3,5,4,6,7,8, 11el script me dirá que el array de entrada es [3,5,4,6,7,8, 11] y que hay 3 pares y 4 impares.

5. Escribe una función que pueda devolver el valor más pequeño de un array numérico o el índice de ese valor. El segundo parámetro de la función dirá si debe devolver el valor ("v") o el índice ("i"). No uses métodos del objeto array.  
Se supone que el primer parámetro siempre será una matriz llena con al menos 1 número y sin duplicados.  
Se suponer el segundo parámetro será una letra con uno de dos valores: 'v' 'i'

> min([4,5,7], 'v')  devolverá 4, mientras que min([4,5,7], 'i') devolverá 0.

6. Escribe una función que determina si la letra que se le pasa como argumento se encuentra contenida dentro de un array de letras que se le pasa como segundo argumento.  
Se trata de resolverlo sin usar métodos del objeto array, solo el dato tipo array.

> existeEn('a', ['w','e','r','i']) devolverá false porque la letra 'a' no existe en el array

7. En este ejempo debes crear una función que reciba una array y devuelva una cadena formada por los elementos del array separados por un guión - si una letra es una vocal. La función tiene como único parámetro la letra que se quiere comprobar. Debe funcionar igual con mayúsculas y con minúsculas y por supuesto usando arrays.  
Solo se aceptan letras internacionales (sin acentos)

> Por ejemplo esVocal('A') dirá true, mientras que esVocal("z") dirá false.

8. Escribe una función qeu reciba como argumento un array y que devuelva una cadena de caracteres formada por los elementos del array separados por un guión

> Si llamamos a la función como listar("rojo", "verde", "azul") deberá devolver "rojo-verde-azul"

9. Un servicio de atención al ciente tiene establecido turnos semanales para sus empleados de manera que cada día de la semana se encarga del servicio  una persona: lunes - María, Martes - Luis, Miércoles - Antonia, Jueves - Pedro, Viernes - Marisa.  
Usa un array para almacenar los datos del servicio. En este array cada elemento será un para día - nombre.  
Crea una función que responda con el nombre de la persona encargada del servicio sabiendo el día. Si el día no existe deberá decir que no hay servicio. Los nombres de los días deben ir en minúsculas.

> Si le pido servicio('Lunes') me debería decir "Este día se encarga María" y si le pido servico(Miércoles") me daría Antonia.

10. Un tienda vende monitores, teclados y ratones. Los precios se almacenan en una estructura array conde cada elemento es un par producto - precio.  
Diseña una función que reciba como argumento el nombre de un producto (minúscula) y devuelva su precio.

> Si la lsita de precios es monitor: 200€, teclado: 20€ ratón: 10€, al pedri precio('monitor') me devolcerá 200.

---

## - Funciones -

1. Crea una función que tenga dos argumentos: num1, num2, y que deuelva como resultado la suma de ambos números. Se supone que se usarán solo números válidos. 

> Llamo a la función como sumar(3,5) deberá devolver 8.

2. Esta función se va a llamar esPar(num) y deberá devolver verdadero si el argumento es par y falso si es impar. Se acepta que solo se usarán números válidos.

> Por ejemplo al llamarla como esPar(5) me dará false, mientras que con esPar(6) me dará true.

3. Función que calcule si un número es múltiplo de otro. La función recibirá dos argumentos, el primero será el supuesto mutiplo del segundo argumento.

> Si ejecuto o llamo a la función con esMultiplo(40,4) debe devolver true porque 40 es divisible por 4.

4. Definir una función que cree una cadena de letras repetidas tantas veces como le digamos. La función recibe dos argumentos: la letra y el número de repeticiones.

> Al ejecutar repetir('a', 5) deberá devover la caden  aaaaa.

5. Usa el algoritmo de Euclides para diseñar una función que determine el máximo común divisor de dos números. Bueno este algoritmo es bien simple. Para clacular el mcd de A y B:
```
Si A = 0 entonces MCD(A,B)=B, ya que el MCD(0,B)=B, y podemos detenernos.  
Si B = 0 entonces MCD(A,B)=A, ya que el MCD(A,0)=A, y podemos detenernos.  
Calcula el resto de A/B
Asigna a A el valor de B
Asigna a B el resto
Repite hasta que A o B sean 0.
```

> Si me piden el MCD(10, 5) tendré 5 como solución, y el MCD( 24, 9) será 1, y el MCD(12,20) será 4

6. Diseña una función que calcule el factorial de un número, usa una función recursiva (que se llama a si misma). Recuerda que el factorial de un número es el resultado de multiplicar cada número por el anterior hasta llegar a 1. Y el factorail de 0 es por definición 1

> Si escribo factorial(3) obtendré 3*2*1 = 6

7. Escribir una función que reciba un número como argumento y lo devuelva invertido, o sea, escrito del revés. Usar esta función para determinar si un número es capicúa (palíndromo)

> Si ejecuto invertir(123) me deberá devolver el número 321 y me diría que no es capicua. Sin embargo si hago invertir(242) el resultado sería 242, y la prueba me diría que es capicúa.

8. Escribe una función que recibe como argumento un precio y el porcentaje de impuestos. La función devolverá el valor total a pagar, teniendo en cuenta que al precio se le descuenta un porcentaje del 10% si es mayor de 100 euros.

> Si he comprado por valor de 200 euros con un impuesto del 5%, me descuentan un 10% por tanto pago 180 euros más los impuestos que son el 5% de 180. En total 189 euros.

9. En esta función se trata de convertir notas a calificaciones literales de manera que menos de 5 es suspenso, un 5 es aprobado, el 6 es bine, el 7 y el 8 son notable, el 9 es sobresaliente y el 10 es matrícula.

> Por ejemplo si pido miCalificacion(5) la función me dirá tu calificación es Aprobado

10. Escibe una función que devuelva el siglo al que correponde un año que se la pasa como argumento. El siglo 1 va del año 1 al 100, el siglo 2 va del 101 al 200....

> Por ejemplo si le pido siglo(1910) me dirá siglo 20
