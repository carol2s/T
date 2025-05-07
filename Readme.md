**PROYECTO TINKERCAD**

En este proyecto lo que he relizado es compresión y práctica de los circuitos con una Placa de Arduino, Placa Protoboard y Leds. Anotando las cosas que consideraba importantes de cada actividad.


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



. Ha sido realizada sin ninguna dificultad.

## · CÓDIGO:

// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}


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

. Ha sido fácil realizar esta tarea.

## · CÓDIGO:

int tiempo=200;//la variable tiempo le aignamos el valor 200
int pin;//declaramos la variable pin,sin asignarle valor momentáneamente


void setup()
{
  for (pin=8; pin<=12; pin++)//inica pin con alor iniacial 8 y se va incrementando hasta 12 
  {
    pinMode (pin,OUTPUT);//pin asume el valor asignado y lo declara como salida
  }
}

void loop()
{
for (pin=8; pin<=12; pin++)
 { 
  digitalWrite (pin,HIGH);
  delay (tiempo);
  digitalWrite (pin,LOW);
  delay (tiempo);
 }  
}
---


## BLUCLE FOR

 Esta programación en bucle realiza procesos repetitivos de forma automática, ahorrando líneas de código y simplificar tus programas. Encendido/apagado luces leds simultaneamente.



Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (5)

> · Led (5)

---

. Ha sido fácil realizar esta tarea, sin ninguna complicación. 


## · CÓDIGO.

int tiempo=100;
int pin;

void setup()
{
for (pin=7;pin<=12;pin++)
 {
  pinMode(pin,OUTPUT);   
 }
}
void loop()
{
secuencia_uno();
secuencia_dos();
}  
//Sunrutinas  
void secuencia_uno()
{
for(pin=7;pin<=12;pin++)
{
  digitalWrite(pin,HIGH);
  delay (tiempo);
  digitalWrite(pin,LOW);
  delay(tiempo);
  }
}
void secuencia_dos()
{
for(pin=12;pin>=7;pin--)
 {
  digitalWrite(pin,HIGH);
  delay (tiempo);
  digitalWrite(pin,LOW);
  delay(tiempo);
 }
}
---


## SUBRUNITAS

El uso de funciones o subrutinas en la programación de Aurdio, esta forma nos permite a ordenar nuestro código en tareas más pequeñas, y además ayuda a las tareas posteriores de depuración.

Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (6)

> · Led (6)

---

. Ha sido sencillo.

## · CÓDIGO:

// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
---

## SALIDAS ANALÓGICAS

Uso de las de salida analógicas, que emulan voltajes analógicos de 0 a 5 volt, por los puertos de ARDUINO habilitados para esta función.
PWM; salidas utilizadas para porder controlar el nivel de intensidad lumínica de los led o poder contralar las revoluciones o velocidad de ciertos motores que soporten control por señal PWM.


Componentes:

---
> · Arduino (1)

> · Protoboard (Placa, 1)

> · Resistencia (3)

> · Led (3)

---

. Ha sido una tarea fácil de realizar. 

## · CÓDIGO:

int LedRojo=12;
int LedAzul=11;
int LedNaranja=10;

void setup()
{
pinMode(LedRojo,OUTPUT);
pinMode(LedAzul,OUTPUT);
pinMode(LedNaranja,OUTPUT);
}

void loop()
{
digitalWrite (LedRojo,HIGH);
delay (300);
digitalWrite (LedRojo,LOW);
delay (300);
digitalWrite (LedAzul,HIGH);
delay (300);
digitalWrite (LedAzul,LOW);
delay (300);
digitalWrite(LedNaranja,HIGH);
delay (300);
digitalWrite(LedNaranja,LOW);             
delay (300);
 }
---

