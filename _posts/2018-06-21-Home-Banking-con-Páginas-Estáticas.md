---
layout: inner
date: '2018-06-21 23:30 -0400'
categories: Conocimientos
published: false
ref: 'Páginas estáticas en el Home Banking: llegó su momento '
lang:
  - es
tags:
  - JEKYLL
  - PAGINAS ESTATICAS
  - WORDPRESS
  - SEGURIDAD
  - PANAMA PAPERS
local_featured_image: banners-06.jpg
author: Alexander Ramirez
author_pic: Alexander_Ramirez.jpg
author_email: alexander.ramirez@synergy-gb.com
lead_text: 'Garantizando seguridad en el Home Banking: superando el WordPress !!'
---
Si el objetivo es implementar una página web con administración simple, con alto desempeño y segura, la opción es generar páginas web estáticas con Jekyll.

En el Siglo XXI hemos sido testigos del crecimiento exponencial del contenido y en especial de la disponibilidad y acceso a diversas páginas web construidas en HTML5, CSS3 y JavaScript. También hemos presenciado la necesidad de gestionar el contenido de la página web y mantenerla vigente y actualizada. El perfil de las personas que gestionan el contenido tiende a ser más de las áreas relacionadas con medios de comunicación que con tecnología.
 
En todo este escenario también hay que considerar particularmente lo susceptibles que pueden ser las páginas web si no cuentan con la seguridad suficiente. Dependiendo del perfil de la empresa, estas pueden ser víctimas de ataques más impactantes y riesgosos para los usuarios de dichas páginas.
 
En tal sentido son dos aspectos en tensión que queremos resaltar en este artículo, en particular, la necesidad de proveer herramientas para gestionar y administrar el contenido, así como el mantenimiento seguro del contenido y la protección en contra de los ataques.
 
Inicialmente nos pareció que la solución era Wordpress, ya que cuenta con una interfaz madura, se ha popularizado su uso y además cuenta con una comunidad viva de desarrolladores que colaboran con nuevos componentes o **plugins** que permiten agregar funcionalidades a las páginas sin requerir más desarrollos. 

Desde el incidente de [Panama Papers](https://www.wordfence.com/blog/2016/04/panama-papers-wordpress-email-connection/) y la exposición de vulnerabilidades de Wordpress, nos hizo pensar de forma muy seria en la exposición que tienen los Bancos que utilizan Wordpress para administrar su contenido y las prácticas de actualización de componentes para mantener la página web minimizando las vulnerabilidades.
 
Lo que era un beneficio, la existencia de componentes aportados por la comunidad, se convirtió en el Talón de Aquiles de Wordpress. No hay garantía de que los diferentes componentes aportados por la comunidad cumplan con las mejores prácticas de desarrollo seguro y cuiden el acceso a los datos de manera no autorizada.
 
Ante esta situación y evaluando diferentes alternativas nos decantamos por las páginas web estáticas generadas con [Jekyll](https://jekyllrb.com). Las razones principales son:
•	Simplicidad
•	Velocidad
•	Seguridad
 
Jekyll es un generador de páginas web basado en plantillas escritas con Liquid. El diseño del sitio se divide colecciones de documentos que utilizan una plantilla (diseño) que Jekyll ensambla de forma jerárquica. Liquid proporciona comandos para controlar el flujo de la generación de una página, con ciclos y condicionales que se utilizan para navegar las colecciones de documentos y generar las diversas páginas. Una vez que está generada la página, esta se publica en un servidor web.
 
El esfuerzo de desarrollo de la página se centra en la construcción de una experiencia amigable para el usuario. Agregar contenido implica que el escritor se enfoque en el texto que desea agregar en formato Markdown. Esto implica que el que escribe debe aprender a redactar utilizando este formato. De hecho si conoce un poco de HTML también puede darle vida a su contenido. Dependiendo de la persona y su disposición a aprender, el hecho de aprender Markdown y HTML básico puede ser un beneficio por la versatilidad del contenido que se puede generar o se puede ver como una desventaja. Una vez que los escritores se familiarizan con la forma de escribir el contenido, es muy productivo el proceso de publicar y agregar más artículos.
 
Las páginas estáticas (pre generadas) son más rápidas ya que no dependen de bases de datos o procesos de generación programados en el servidor. Esto simplifica el acceso al contenido y este se sirve con un desempeño alto.
 
Adicionalmente el mayor de los beneficios para un Banco es que no está expuesto a los problemas de seguridad que se derivan del uso de componentes de terceros. Hay que aclarar que todo software es susceptible de ataques, pero al no utilizar Wordpress se minimiza significativamente y después de todo se trata de gerenciar el riesgo.
 
Algunas referencias importantes como el sitio web de Netflix, el sitio web de la campaña del Barack Obama, entre otros se genera con Jekyll.
 
Para completar el proyecto y facilitar el proceso de generación de contenido y gestión de versiones estamos utilizando [Github Pages](https://pages.github.com) y [Prose](http://prose.io). Con Github se gestionan las fuentes de la página web y el contenido además que se publica la página estática. Github ya ofrece facilidades para utilizar un nombre de dominio propio y recientemente ya permite el uso de **https** con certificados generados por ellos mismos. Por otra parte **Prose** permite generar planillas amigables para publicar artículos en la página. Prose simplifica la publicación de nuevo contenido a los usuarios con menos interés en los aspectos ligeramente técnicos.
 
Ya hemos implementado varias páginas web para nuestros clientes con esta arquitectura y una vez que se supera la curva de aprendizaje, logran gerenciar su página y el contenido de forma independiente.

Son millones de usuarios que utilizan nuestra aplicaciones Bancarias en Latinoamérica, que se benefician de una experiencia funcional y enriquecida. 

Visita [nuestra página principal http://synergy-gb.com](http://synergy-gb.com) y entérate de nuestra propuesta de valor.

 

