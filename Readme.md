**PROYECTO TINKERCAD**

En este proyecto lo que he relizado es compresión y práctica de los circuitos con una Placa de Arduino , Placa Protoboard y Leds, en un programa - TINKERCAD. Anotando las cosas que consideraba importantes de cada actividad.



04/04/25

---
 ## SALIDA DIGITAL


Programación y simulación  de una salida digital controlada por arduino; encender un led. 

Componentes:


---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (1)

> · Led (1)


---

Una vez tengamos los componentes, prodecemos a su correspondiente colocación, es importante este procedimiento, y a preferencia u estetica, además de evitar confusiones,  cambiamos el color de los cables, el positivo de un color (rojo) y el negativo de otro (negro).
Hecho esto, empezamos con el código/ programación para hacer que funcione. 

1- Edición en texto.

 La sintaxis de esta debe ser correcta, debido a que si ésta esta mal nos dará "Error" por más mínimo que sea.


2- Edición en texto +  bloques.

Esta edición es más sencilla, mediante vamos armando los bloques, la sintaxis automaticamente se refleja en el texto.

· Ejemplo:

https://www.tinkercad.com/things/2u8hz6QVhkR-ingenious-krunk?sharecode=1X-yb5-TFVczVR31QVibNydGjlm5pLFO2AnF35js3X8

---

___
## USO DE VARIABLES

 Uso de nombres o varables, esto permitirá poder idetificar los elementos/ componentes y evitar intervenir todo el código en caso de correciones. Secuencia de encendido/apagado con leds.

Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (3)

> · Led (3)

---

En este circuito prodecemos a colocar los leds en su correspondiente colocación a la vez que nombramos cada componente, es importante este procedimiento, y a preferencia u estetica, además de evitar confusiones,  cambiamos el color de los cables, el positivo de un color (rojo) y el negativo de otro (negro). Los leds se colocaran seguidos, conectando las resistencias con los cables en sus respectivas filas y conectando la Protoboard al Arduino.
Hecho esto, empezamos con el código/ programación para hacer que funcione. 

1- Edición en texto.

 La sintaxis de esta debe ser correcta, debido a que si ésta esta mal nos dará "Error" por más mínimo que sea.


· Ejemplo:

https://www.tinkercad.com/things/6obMrxFMuH7-funky-bruticus-elzing?sharecode=fRjTm8LgR8F-dnJQsK8PYQmm2ZvMoTHMOzHcJX_h3OI

---
___


## BLUCLE FOR

 Esta programación en bucle realiza procesos repetitivos de forma automática, ahorrando líneas de código y simplificar tus programas. Encendido/apagado luces leds simultaneamente.



Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (5)

> · Led (5)

---
---

Realizamos lo mismo que en la anterior circuito; los leds en su correspondiente colocación uno seguido de otro con sus respectivos nombres, en la misma fila, cambiamos el color de los cables, el positivo de un color (rojo) y el negativo de otro (negro). Conectamos las resistencias con los cables en sus respectivas filas y conectando la Protoboard al Arduino, cable ngro (negatico) a GND y los rojos (positivos) a los numeros, siempre en un orden, parea evitar confusiones.

Hecho esto, empezamos con el código/ programación para hacer que funcione. 

1- Edición en texto.

 La sintaxis de esta debe ser correcta, debido a que si ésta esta mal nos dará "Error" por más mínimo que sea.


· Ejemplo:

https://www.tinkercad.com/things/izrNv4arzag-powerful-jaban-gaaris?sharecode=qD6O039aYxq2Y4jL9G96dzJkmTaiNj10gesGym9y79Q


## SUBRUNITAS

El uso de funciones o subrutinas en la programación de Aurdio, esta forma nos permite a ordenar nuestro código en tareas más pequeñas, y además ayuda a las tareas posteriores de depuración.

Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (6)

> · Led (6)

---

Secuencia de derecha a izquierda y de izq. a dch. Aplicar el programa principal.

--> void loop()

    secuencia_unos() ; ->  Llamado a Subrutina 1

    secuencia_dos() ; ->   Llamado a Subrutina2

    / /Código de Programa


    Ejemplo:
    https://www.tinkercad.com/things/cfFZiUm45qD-exquisite-maimu-krunk?sharecode=1AUR2P331udoOjlT2opiNOPG9F_9014CfQ2ecFXlyv4

---
---

## SALIDAS ANALÓGICAS

Uso de las dsalida analógicas, que emulan voltajes analógicos de 0 a 5 volt, por los puertos de ARDUINO habilitados para esta función.
PWM; salidas utilizadas para porder controlar el nivel de intensidad lumínica de los led o poder contralar las revoluciones o velocidad de ciertos motores que soporten control por señal PWM.


Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (3)

> · Led (3)

---

Las reistencias deberan ir conectadas a los puertos con marcas, y así porder simular las salidas PWM.

Ejemplo:

https://www.tinkercad.com/things/dW18cLyNagt-brilliant-hango?sharecode=c8JjLn4MNBTQbAcdhHrhZg7f3IOh9AubUQJhYOx0s-Y

---
---


08/04/25

---

## ESTRICTURA DE PROGRAMACIÓN

Explica como se estructura la programación de ARDUINO, reconociendo las instruciones básicas, pinMode, digitalWrite y delay para controlar el comportamiento de tres leds conectados a la placa en los pines 8,9 y 10.

* -> OUTPUT     |                                        -> INPUT  
Como una entrada de salida. información         |            Entrada

Tener en cuenta ñlas pautas básicas. 
Como "Delay"

Ejemplo:

https://www.tinkercad.com/things/20JQ4BA1BE7

---


---
## PROTOBOARD

La Protoboard nos permitirá realizar montaje de circuitos muy fácil, lo impportante es tener claro como funcinan para no cometer más errores. Existen varios tipos de este, por lo tanto entender la estructura es importante, en todas las columnas existe una referencia.

Ejemplo:

https://www.tinkercad.com/things/lY7RaYN1AmJ-protoboard?sharecode=7Dhzp1tpGBoKaBy8YqDqxysEzlhlluL7YIybEpsORAc

---
---

## VARIABLES Y FUNCIONES

Las variables son espacios en la memoria que tienen un nombre y un valor en programación hay distintos tipos de variables, depende del uso para indicar cual.

Ejemplo:

https://www.tinkercad.com/things/0IdXzcJfYp9-fantastic-jaban?sharecode=dK3kfdwVq3ngXq8pmCVg3f4vaPpGnEFvB5SF8kZVd-M

---
---

## ARGUMENTOS

Datos que se utilizan en las funciones, el uso adecuado de estos permite un proceso de programación más agil. Se le llama argumento en el momento que se llama a la función, pero cuando se esta declarando la función se le lama parámetro. 

Ejemplo:

https://www.tinkercad.com/things/jdiJfGV5nMW-argumentos?sharecode=2D0_DPWHgmg3TFyGWkidN2zVk-wXpkeTOVU2U5ogfyg

---

---
## CONDICIONALES

Las condicionales nos permiten controlar el comportamiento de nuestros sistemas, mediante la comparación de valores o variables.

if(condición)  
 El conjunto de instrucciones que se ejecutan sí se cumple la condición.

Con el msimo circuito  programacón del punto anterior.

Dentro de los paréntesis hay una condición. Esta puede ser la comparación de dos valores o de dos variables, podemos utilizar distintos tipos de comparaciones. 

Generalmnte el "if" se acompaña de un "else", este sirve para que en caso de la condición no se cumpla, el programa haga otra cosa (no tiene condición, simplemente es un descarte).

Ejemplo: 

https://www.tinkercad.com/things/5W9tQX11VWK-condicionales?sharecode=kKL-Sdk_ljMvli5APMGhopm4wAYew5Ga1tzHX2bF6BE

## MONITOR SERIAL

Nos permite establecer una comunicación entre el ARDUINO y nuestro ordenador, este nos permitira realizar distintos proyectos. 

--> Enviar y recibir datos.

A la variable le agregamos un valor, y probar que nos muestra. Para controlar el flujo de lectura agregamos una **condición** por ejemplo la función **serial*.
Hay tener en cuenta los paréntesis; donde conrrespondan. 

Ejemplo:


##

Todo lo que hemos visto anteriormente se aplicara en esta siguiente actividad.

Realizar un circuito en las cuales se cumplan las condiciones especificadas en la guia, siguiendo un orden para una mejor compresión como nombrando cada componente.

Lo que se pretnde es crear las siguientes funciones:

· EncenderTodos {}

·ApagarTodos {}

·SecuenciaUnoDespuesOtro {}

·SecuenciDosEnDos {}


En cada función incluir un argumento que permita controlar el tiempo, y programar una condiciol if.

Ejemplo:

## CICLO FOR

Este permite controlar las veces que se repite una función.

En proyectos esto nos permite ahorrar códigos y tambien generar variantes en el comportamiento de nuestros componentes. 
Se mostrara con el circuito de la anterior actividad 

---> for (valor inicial; valor final; incremento)

Instrucciones

Ejemplo:

