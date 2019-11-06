# PLA4

Actividad 1, partes:
1.	Ir a los ejemplos del MK1000 y volcar el ejemplo “Blink”.
2.	Modificar el código del ejemplo cambiando la función “delay()” por un código basado la función “millis()”.
      a.	Explicar que diferencia hay entre usar una y la otra.
3.	Vamos a reproducir el ejemplo “Blink” para ahora usando interrupciones. Se trata de usar un PIN digital de salida, el que queramos, para que oscile periódicamente entre 0 y 1 (BAJO y ALTO). Luego usaremos los estados de este PIN como fuente de una interrupción, haciendo que nuestro LED (el que tenemos soldado en la placa del MK1000) se encienda cada vez que el PIN de salida esté en ON.

Actividad 2:
Se define el siguiente escenario: se conecta el Arduino a la Raspberry PI usando un cable USB. Desde la Raspberry PI ahora podemos ver un nuevo dispositivo USB-serie conectado.
● comando: lsusb	
Abrimos puerto serie para comunicarnos con Arduino desde la Raspberry PI:
● comando: screen /dev/PUERTO_SERIE_DEL_ARDUINO 9600
Desde la consola serie debemos mandar los siguientes comandos a Arduino y este debe responder como procede:
● comando: ON - respuesta: LED ON
● comando: OFF - respuesta: LED OFF
El alcance de la actividad es desarrollar el código para Arduino para que cuando este se conecte a la Raspberry PI se comporte de la forma descrita anteriormente. Se deberá subir el código de la actividad a GITHUB
