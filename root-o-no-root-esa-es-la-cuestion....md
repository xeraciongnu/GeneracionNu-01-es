---
description: Laboratorio Android
---

# root o no root? Esa es la cuestión…

![](.gitbook/assets/image%20%2872%29.png)

## root o no root? Esa es la cuestión…

**\(parafraseando a Hamlet, -acto tercero, escena primera- de W. Shakespeare\)**

Es de sobras conocido que Android, el sistema operativo móvil\* más utilizado del mundo \(desarrollado y mantenido por Google\) está basado en el kernel \(núcleo\) de GNU/Linux y, por ello, hereda muchas de sus características.

\* Entendamos aquí por “móvil” cualquier smartphone, tablet, wareable, IoT o dispositivo empotrado que porte Android.

![](.gitbook/assets/image%20%2855%29.png)

fuente de la imagen: [https://pixabay.com/es/android-sistema-operativo-reinicio-2995824/](https://pixabay.com/es/android-sistema-operativo-reinicio-2995824/)

Una de esas características es el control de acceso al sistema en base a perfiles/permisos de usuario, como cualquier sistema operativo Unix o derivado \(entre otros\).

Una gran diferencia respecto a sus hermanos mayores es que, por defecto, Android no nos ofrece la posibilidad de acceder al sistema como administradores \(admin o root, en lenguaje linuxero\). Una decisión alabada y criticada a partes iguales que condiciona claramente la manera en la que interactuamos con nuestros dispositivos.

Google justifica su decisión en base a que, como usuarios, podemos manejar perfectamente nuestro dispositivo móvil\* sin tener acceso a partes importantes \(y/o imprescindibles\) del sistema y sin la capacidad de poder modificarlas. Nos permite instalar aplicaciones y modificar la configuración básica del sistema para personalizarla al gusto del usuario \(colores, fondos, iconos, …\). Claramente una decisión que simplifica la gestión de la seguridad del dispositivo y que le ahorra al usuario inexperto “dolores de cabeza”.

![](.gitbook/assets/image%20%2846%29.png)

fuente de la imagen: [https://pixabay.com/es/comprimido-pantalla-apps-android-1442900/](https://pixabay.com/es/comprimido-pantalla-apps-android-1442900/)

Esta actitud paternalista se asemeja peligrosamente al “despotismo ilustrado” tan de moda en la Europa de finales del Siglo XVIII. “Todo para el pueblo, pero sin el pueblo”. Es decir, démosle el mejor sistema operativo a los usuarios pero impidamos que puedan tomar sus propias decisiones \(por su seguridad\). Quién mejor que Google o el fabricante del hardware para decirnos qué es lo mejor para nosotros?

![](.gitbook/assets/image%20%2814%29.png)

fuente de la imagen: [https://pixabay.com/es/seguridad-protecci%C3%B3n-antivirus-265130/](https://pixabay.com/es/seguridad-protecci%C3%B3n-antivirus-265130/)

Hasta aquí parece que simplemente estemos planteando problemas metafísicos sobre si es conveniente una u otra “filosofía de uso” de nuestros dispositivos. Pero nada más lejos de la realidad. Cuando compramos uno de estos equipos no estamos adquiriendo el derecho de poder usarlo libremente. Sólo tenemos el derecho a usarlo.

Y esa diferencia es fundamental. La propia Google o el fabricante del dispositivo pueden decidir que nuestro sistema operativo debe contener una aplicación \(preinstalada y que no se puede desinstalar\) de cualquier índole. Un antivirus, un juego, una app de control de la salud, un sistema de pago contactless, una configuración predeterminada, … 

Al no ser root no podremos modificar ciertas partes del sistema \(una de ellas es el control sobre las aplicaciones precargadas\) y no podremos desinstalarlas o, por poner otro ejemplo, parar ciertos servicios que no sean de nuestro interés.

Pero no acaba ahí la cosa. Aunque Android nos permite \(con cierto reparo\) instalar aplicaciones que no provengan de su propia tienda de software, algunas de estas aplicaciones no podremos instalarlas sin tener privilegios de administrador.  
No hay que pensar en pretender instalar oscuras aplicaciones para fines oscuros: sirva como ejemplo uno de los mejores programas de copias de seguridad que existen. Estamos hablando de Titanium Backup.

![](.gitbook/assets/image%20%2837%29.png)

fuente de la imagen: [https://play.google.com/store/apps/details?id=com.keramidas.TitaniumBackup](https://play.google.com/store/apps/details?id=com.keramidas.TitaniumBackup)

Paradójicamente, podemos encontrarlo en Google Play \(ver el enlace de la anterior imagen\), tiene más de 10 millones de descargas y una puntuación de 4’6 sobre 5 \(con más de 350.000 valoraciones\) pero, lógicamente, necesita de permisos root para poder funcionar \(para poder copiar o restaurar partes del sistema es imprescindible tener acceso de admin\). Vuelta al despotismo ilustrado.

Con todo esto no estamos diciendo que sea conveniente que el dispositivo venga desprotegido \(rooteado\) por defecto pero sí que sería recomendable que un usuario con conocimientos avanzados tuviera la oportunidad de desbloquearlo, de manera oficial, para poder acceder completamente a SU sistema.

Ojo! No hablamos de cambiar la versión del sistema operativo \(o sustituirlo por otro distinto\), simplemente pretendemos disponer de una cuenta en él \(en la versión oficial que viene con el equipo\) con permisos de administrador.

Algo que parece trivial en otros sistemas operativos, es una utopía en Android.

Esto significa que no podemos desbloquear nuestro móvil o tablet? No, no significa eso. Si disponemos de los conocimientos técnicos suficientes podremos desbloquearlo para conseguir ser administradores \(rootearlo\).

Cuál es el problema, pues? El problema es que, si hacemos eso, lanzamos una serie de catastróficas desdichas en nuestra contra… podemos perder la garantía del dispositivo \(cláusula que se me antoja, cuando menos, abusiva\), perdemos las actualizaciones oficiales de Android e, incluso, hay ciertas aplicaciones que no se podrán utilizar \(sobre todo apps de gestión de contenidos, streamming de tv/video, apps de pagos NFC, …\).

A veces compensa rootear nuestro sistema, otras no. Lo cierto es que existe una gran cantidad de usuarios, sobre todo con un nivel avanzado de conocimientos, que se lanzan a rootear sus dispositivos porque las ventajas de tener control total sobre la configuración del equipo son evidentes \(instalación de terminales de comandos, posibilidad de reajustar la configuración de parámetros de red, desinstalar aplicaciones preinstaladas no deseadas, cambiar la frecuencia del microprocesador, … las opciones son infinitas\). Eso ya es decisión de cada cual; lo que sí está claro es que no lo facilitan.

![](.gitbook/assets/image%20%2827%29.png)

fuente de la imagen: [https://pixabay.com/es/configuraci%C3%B3n-opciones-software-265131/](https://pixabay.com/es/configuraci%C3%B3n-opciones-software-265131/)

Que cómo rooteamos un dispositivo Android?

Bueno... esa es otra historia…

## [Siguiente artículo](el-ecosistema-de-openstreetmap.md)

