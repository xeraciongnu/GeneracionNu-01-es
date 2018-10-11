---
description: Laboratorio de Música
---

# Hydrogen. Un secuenciador profesional de batería.

![](.gitbook/assets/image%20%2823%29.png)

## Hydrogen. Un secuenciador profesional de batería, multiplataforma y de licencia libre

### Introducción: un ritmo para gobernarlos a todos

Montar un grupo musical o poner una base rítmica elaborada a nuestras canciones y ensayos no siempre es fácil, especialmente si no contamos con un batería o percursionista que nos ayude con la tarea. Para ello, tenemos las llamadas cajas de ritmos y los secuenciadores de batería, con los cuáles podremos crear una serie de patrones rítmicos con distintos sonidos \(por ejemplo, los propios de una batería de jazz\) que servirán de base para nuestros experimentos musicales.

Sin embargo, el problema suele ser lo mecánico de estos programas, con una precisión tan extrema en el ritmo que se pierde el “factor humano”, aquello que separa lo secuenciado por la máquina de lo creado por el hombre. Como primer paso frente a ello, y bajo el paraguas del software libre, llega un programa cargado de utilidad: Hydrogen.

![He aqu&#xED;, el logo de Hydrogen](.gitbook/assets/image%20%285%29.png)

 Hydrogen \([https://sourceforge.net/projects/hydrogen/](https://sourceforge.net/projects/hydrogen/)\) es un secuenciador de batería multiplataforma y de licencia libre desarrollado por el programador italiano Alessandro Cominu \(aka Comix\), útil y accesible tanto por la aparente “sencillez” del programa como por un entorno gráfico muy intuitivo, siendo una herramienta de trabajo y creación tanto para percursionistas y compositores con experiencia como para aquellos más nuevos en la materia.

El programa se basa en la creación de distintos patrones rítmicos, que serán modificados en función a diversas variables \(velocidad o tempo, tipo de sonido, duración, etc...\), para ser posteriormente mezclados/producidos y enlazados unos con otros para dar lugar, finalmente, a un fichero de audio \(.wav\). Hablemos, pues, de este software.

###  Acercándonos a Hydrogen: funcionamiento básico

Hydrogen presenta un interfaz gráfico basado en QT, y en su pantalla principal posee tres ventanas fundamentales a través de las cuales el usuario podrá interactuar para crear sus patrones y secuencias rítmicas: ‘Pattern Editor’, ‘Song Editor’ y ‘Mixer’.

Al margen de estas, en las que ahondaremos a continuación, encontraremos una barra de herramientas básicas, enfocadas a reproducir el audio creado y partes de este o establecer un tempo determinado, entre otros. Sin embargo, interactuaremos espacialmente a través las ventanas anteriormente mencionadas.

![Arriba del todo, la barra de herramientas. Justo debajo, el &apos;Song Editor&#x2019;. Abajo a la izquierda, el &apos;Pattern Editor&apos;. Abajo a la derecha, el &apos;Instrument Editor&apos;...](.gitbook/assets/image%20%2878%29.png)

La primera de ellas, el ‘Pattern Editor’, nos permite crear los patrones rítmicos básicos sobre las que vamos a trabajar para dar forma a las distintas secuencias. Aquí podremos controlar los instrumentos o sonidos que formarán parte del patrón, así como la intensidad de estos o su aparición a lo largo del propio patrón \(que admite valores de entre 1 y 32 pulsos\).  
Cada una de las notas que se aplican a la secuencia pueden ser introducidas mediante clicks o a través de dispositivos MIDI. De este modo, a través del ‘Pattern Editor’ entramos en la primera fase de la creación de nuestra secuencia rítmica, dando lugar a los eslabones rítmicos que, unidos, darán lugar a la secuencia o cadena.

Precisamente, será con el ‘Song Editor’ con el que controlaremos cómo se enlazan estos patrones en la línea del tiempo. De forma intuitiva \(a través de pequeños cuadrados azules\), podemos modificar y mover en el tiempo nuestros patrones, además de crear algunos nuevos.

Si bien en esta ventana encontraremos otras opciones \(sin profundizar especialmente en ellas, animando a todos los lectores a probarlo ellos mismo\), estas serán las básicas con las que podremos controlar nuestro trabajo.

Por último, el ‘Mixer’. Esta es la ventana en la que surge la magia, aquella que hace de Hydrogen un programa especial. La dividiremos en dos secciones, siendo la primera el mezclador como tal, aquello con lo que podremos producir y controlar con precisión el resultado sonoro de cada uno de los sonidos, de los patrones o de la secuencia la completo.  
Aquí podremos controlar los volúmenes, aplicar hasta cuatro efectos de audio por sonido \(a través de una biblioteca de complementos LADSPA [http://ladspa.org/](http://ladspa.org/)\) o “humanizar” el sonido al hacer más o menos irregulares los pulsos rítmicos, rompiendo así la precisión robótica, y haciendo más realista el resultado sonoro. Así mismo, la segunda sección es el ‘Instrument editor’, donde podremos cambiar la ganancia, el tono y otras características del sonido \(ataque y caída, añadir un tono aleatorio, darle una mayor resonancia,...\).

Al final, el ‘Mixer’ nos servirá para dar sentido, realismo y personalidad a nuestros pequeños experimentos rítmicos.

![ ... y aqu&#xED;, el &apos;Mixer&apos;.](.gitbook/assets/image%20%2835%29.png)

### **¿Por qué Hydrogen y no otro?**

La pregunta es: ¿por qué Hydrogen y no cualquier otro secuenciador de batería? Bueno, en primer lugar está el hecho de que es software libre, por supuesto. Pero más allá de eso, Hydrogen es un programa que destaca por su versatilidad, en todos los sentidos.  
Apto para expertos y para novatos, para aquellos que trabajen sobre sonidos predeterminados \(existiendo la opción de descargar kits completos de batería que se ajusten a nuestras necesidades\) o aquellos que busquen su propio sonido, para aquellos que necesiten un metrónomo y para los que necesitan una batería para sus creaciones,...

Hydrogen es fácil de usar y se adapta a lo que el usuario requiera.

No podemos olvidar las opciones de “humanizar” el sonido y la de generar un tono aleatorio para los distintos instrumentos/sonidos. Este apartado está especialmente cuidado en este programa, y los resultados de cara al usuario son únicos, con infinitas posibilidades.  
Por supuesto, el programa no puede sustituir al 100% a un batería humano \(tampoco tenemos claro que sea eso lo que queremos, ¿no?\) y tiene sus defectos, como todo, pero desde luego es una buena solución “en tiempos de crisis”. Es una máquina, si... pero una máquina genial.

Por todo ello, y por todas esas cosas que cada uno encontremos en Hydrogen... ¡A cacharrear!

Archivo sonoro: [https://ia801506.us.archive.org/26/items/Xeraciongnu-01/Prueba de Hydrogen.wav](https://ia801506.us.archive.org/26/items/Xeraciongnu-01/Prueba%20de%20Hydrogen.wav)​

Sobre el audio: se trata de un audio de prueba, una secuencia de cuatro patrones \(A, B, C y D\). El “Patrón A” se repite tres veces, siendo un ritmo base, y luego pasamos al “Patrón B” con otros sonidos diferentes.

Volvemos al “Patrón A”, que se repite dos veces, y pasamos a un “Patrón C” cuyo final se ha “humanizado” en exceso \(por eso el pulso suena “a destiempo”\).  
Finalmente, tras pasar un par de veces por el “Patrón A”, finalizamos con el “Patrón D”, ¡que da un cierre a nuestro pequeño experimento!

## [Siguiente artículo](la-aapp-que-favorece-unos-salarios-mediocres.md)

