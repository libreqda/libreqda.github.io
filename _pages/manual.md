---
title: "Manual"
header:
  overlay_color: "#DFBC42"
  overlay_image: /assets/images/lqda-header-manual.png
permalink: /manual/
excerpt: "Introducción a la utilización de libreQDA"
modified: 2016-11-03T10:01:43-04:00
gallery:
  - url: /assets/images/manual/01-Login.png
    image_path: /assets/images/manual/01-Login-th.png
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/manual/02-NuevoProyecto.png
    image_path: /assets/images/manual/02-NuevoProyecto-th.png
gallery2:
- url: /assets/images/manual/04-NuevoProyecto-2b.png
  image_path: /assets/images/manual/04-NuevoProyecto-2b-th.png
  alt: "placeholder image 1"
  title: "Image 1 title caption"
- url: /assets/images/manual/05-AbrirProyecto.png
  image_path: /assets/images/manual/05-AbrirProyecto-th.png

---

En esta sección presentamos un breve manual de uso de libreQDA

{% include toc %}

# Acceso y creación de un proyecto

Al acceder a la interfaz web, se nos solicitará nuestro nombre de usuario y contraseña. Una vez que nos hemos identificado, aparecerá la pantalla principal de proyectos, con la lista de proyectos a los que tiene acceso el usuario que hemos utilizado para identificarnos y la posibilidad de crear un nuevo proyecto clicando en el botón "Nuevo proyecto".

{% include gallery caption="This is a sample gallery with **Markdown support**." %}

Introduciremos el nombre del nuevo proyecto y una descripción del mismo y clicamos en el botón "Confirmar". Una vez creado el proyecto, podemos abrirlo clicando en el nombre del mismo, con lo que nos aparecerá la ventana principal del proyecto.

{% include gallery id="gallery2" %}

En la ventana principal, además de los botones que nos permitirán realizar diversas acciones relacionadas con el análisis, encontramos tres pestañas: "General", "Documentos" y "Usuarios".

En la primera de ellas, "General", podemos visualizar información relativa al proyecto, como versión, fecha de creación y de modificación, persona que ha creado el proyecto, y número de documentos, códigos y citas del mismo. En la segunda pestaña, "Documentos", tendremos la referencia de los documentos que constituyen nuestros datos de análisis, mientras que en la tercera, "Usuarios", aparecerán los identificadores de los usuarios que tienen acceso al proyecto, y los roles que tienen asignados.

Proyecto 	Proyecto: Documentos 	Proyecto: Usuarios

# Trabajar con documentos

Para poder empezar a trabajar, añadiremos a nuestro proyecto los documentos que ćonstituirán nuestros datos de análisis (no es imprescindible que añadamos todos los documentos en este momento, podemos añadir nuevos a nuestro proyecto nuevos documentos en cualquier momento). Seleccionamos la pestaña "Documentos" y clicamos en "Agregar documento", con lo que nos aparecerá una nueva ventana en la que seleccionaremos (en nuestro disco) el archivo que queremos añadir y le asignaremos un nombre (puede ser diferente al nombre de archivo) y una breve descripción.

El tipo de archivos que podemos añadir son: TXT, PDF, RTF y DOCX. Sea cual sea el tipo que utilicemos, LibreQDA realizará una transformación a texto plano, es decir, que no se conservarán códigos de formato como negritas, cursivas, etc.

Actualmente el proceso de añadir archivos tiene que realizarse "uno a uno", no pueden añadirse varios archivos en una misma operación, algo que será posible en próximas versiones del programa.

A medida que vamos añadiendo archivos, en la pestaña "Documentos" podemos ver la descripción de los mismos. Tenemos además la posibilidad de eliminarlos (con lo que evidentemente si hemos realizado algún análisis sobre el mismo, éste se perderá) y de abrirlo para visualizar y analizar.




Una vez que hemos seleccionado un documento, podremos verlo en la pantalla principal de análisis.

Si queremos cambiar el documento activo, sólo tenemos que desplazar el cursos hacia el margen izquierdo, clicar en el documento que queremos visualizar, y una vez que visualizamos su descripción clicar nuevamente en el botón "Ver".

Visualizar documento

Visualizar lista de documentos
