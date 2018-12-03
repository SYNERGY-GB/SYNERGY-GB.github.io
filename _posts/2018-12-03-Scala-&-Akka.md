---
layout: inner
date: '2018-12-03 13:24 -0400'
categories: Conocimientos
published: false
ref: Scala & Akka
lang:
  - es
tags:
  - Lenguajes de Programación
  - Concurrencia
  - Robustez
  - Allways ON
  - Seguridad
  - Escalabilidad
  - Omnichannel
  - Blockchain
  - Scala
  - Akka
  - Máquina virtual Java JVM
  - 'Erlang '
  - Banking
  - Trends
  - Latinoamérica
  - Latam
  - Innovación
  - Synergy-GB
local_featured_image: Scala_y_Akka.jpg
author: José Rivera
author_pic: Jose_Rivera.jpg
author_email: jose.rivera@synergy-gb.com
lead_text: >-
  Ante los requerimientos de canales digitales transaccionales de espectro
  masivo como el Canal Bancario, donde la constante es la concurrencia, la
  robustez, el principio de “Allways ON”, la seguridad y la escalabilidad; Scala
  & Akka son, por así decirlo, ¡roca sólida!
---
## “Hablemos de nuestro Stack Tecnológico: ¿Por qué Scala & Akka?”


Siendo **Synergy-GB** una empresa de desarrollo de productos y soluciones de software para el sector bancario a escala latinoamericana, es fundamental ser muy escrupulosos en la escogencia de los componentes que conforman el _**Stack Tecnológico**_ sobre los cuales construimos nuestras soluciones.

Hoy quisiéramos conversar en relación con nuestra escogencia de **Scala & Akka** como núcleo fundamental de nuestro motor Multicanal y Omnicanal en nuestra capa midleware, de nuestra arquitectura SOA.

Por temas estratégicos, en **Synergy-GB** decidimos enfocar todos nuestros esfuerzos en la escogencia de _Stack Web_ en el frontend y esto ha implicado darle seguimiento a diferentes arquitecturas y tecnologías que están en ebullición y en constante evolución, tanto en el mismo frontend como en el backend.

Por supuesto, también hemos seguido de cerca las iniciativas y las escogencias de los grandes de la tecnología en el mundo, ie, Google, Amazon, Facebook, Apple, … por nombrar los más representativos.

En estas revisiones comprobamos que la tendencia iba en la línea de seleccionar patrones de programación funcional & objetos en detrimento de la orientación tradicional de solo a objetos, en busca de un código más limpio, las ventajas que aporta a la hora de tratar temas complejos de ingeniería de software y la flexibilidad de ofrecerle al programador dos paradigmas que pueden aplicar indistintamente de acuerdo con el problema a resolver.

Podemos decir que **Scala & Akka** es uno de los lenguajes y _framework_, respectivamente, en donde se integran de manera eficiente las características de los lenguajes orientados a objetos y los funcionales.

>¿Qué es **Scala**?
**Scala** es un lenguaje de propósito general diseñado para expresar los patrones de programación más comunes de una manera sencilla, elegante y segura. Integra características de orientación a objetos y lenguajes funcionales, permitiendo mayor productividad. Scala es un lenguaje basado en la JVM (Java Virtual Machine) que se integra perfectamente con Java y su ecosistema (tolos, IDEs, librerías, …). Por lo tanto, se beneficia del rendimiento y estabilidad de dicha plataforma.


>¿Qué es **Akka**?
**Akka** es una plataforma (o framework) inspirado por Erlang que busca el desarrollo simple de aplicaciones escalables y multi-hilo. **Akka** funciona sobre **Scala** y por tanto corre sobre la máquina virtual Java JVM. Si en los lenguajes más tradicionales como Java la concurrencia se basa en la memoria compartida entre varios hilos y los métodos de sincronización, **Akka** ofrece un modelo de concurrencia basado en actores, donde un actor es un objeto con el que puedes interactuar enviándole mensajes: cada actor puede procesar mensajes y enviarles mensajes a otros actores. En una máquina virtual JVM pueden correr miles de actores a la vez construyendo una jerarquía padre (supervisor)-hijo, con los padres monitorizando el comportamiento de los hijos.

**¿Cuáles fueron los principales aspectos que consideramos y que nos ocupó en la selección de los componentes de nuestro Stack Tecnológico?**

¡La concurrencia, la robustez, el principio de _“Allways ON”_, la seguridad y la escalabilidad!

En el modelo tradicional basado en hilos los programas son ‘picados’ en múltiples unidades de ejecución (threads) operando en segmentos de memoria compartida. Este enfoque en ocasiones genera problemas de distintas índoles (no es el caso caer en detalles en este artículo), básicamente en la lógica que maneja los segmentos de memoria compartida (programación compleja).

**Scala & Akka** adoptan un enfoque completamente diferente, a través de un modelo basado en ‘actores’. Un actor es un modelo matemático de computación concurrente en el que se encapsulan datos, código y su propio hilo de control, comunicándose de manera asíncrona, mediante técnicas de paso de mensajes inmutables. Trabajar con hilos requiere un mayor nivel técnico, pero **Scala & Akka** surgen en este escenario, abstrayendo todos estos conceptos en el actor. **Scala & Akka** permiten a los programadores escribir programas que puedan ejecutar cientos de tareas en paralelo. 

Adicionalmente **Scala & Akka** toman conceptos y técnicas de Erland para construir modelos de tolerancia a fallos para que las aplicaciones puedan continuar su funcionamiento cuando algún componente del sistema falla, a fin de que se recuperen de un problema tan rápido como sea posible.

**¿Por qué para nosotros es un tema tan sensible la resolución de este tipo de problemas en nuestra arquitectura?**

Porque precisamente en los sistemas de canales digitales transaccionales de espectro masivo, la constante es la concurrencia, la robustez, el principio de _“Allways ON”_, la seguridad y la escalabilidad.

**En palabras sencillas, Scala & Akka son, por así decirlo, ¡roca sólida!**


En [Synergy-GB][1] seguimos comprometidos en la línea de generar valor a nuestros clientes, ya que nos mueve el profundo respeto que les tenemos.



[1]: http://synergy-gb.com "Synergy-GB Web Page"
[2]: http://blog.synergy-gb.com "Synergy-GB Blog"
