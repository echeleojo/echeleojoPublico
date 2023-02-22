# Plataforma echele ojo

Para aportar a la visibilidad de los procesos de Control Social realizados por Veedurías Ciudadanas de Bogotá, se decide hacer público el código fuente de la plataforma échele ojo mediante licencia Creative Commons (CC). Esto permitirá a los diferentes interesados hacer uso de esta herramienta y adaptarla a las necesidades específicas de su comunidad. 

# Tipo de licencia Creative Commons seleccionada

La licencia Creative Commons (CC) con la que se publicará el código fuente de la herramienta es atribución no comercial compartir igual CC BY-NC-SA .

Esta licencia permite a la ciudadanía en general que adapte y desarrolle su herramienta web sin fines comerciales usando de base el código compartido, siempre y cuando le den crédito al autor principal y licencien sus adaptaciones basadas en este código bajo los mismos términos.

# Función principal

Esta herramienta digital web permite la socialización de ejercicios de control social que están siendo realizados por Veedurías Ciudadanas en Bogotá. Las Veedurías Ciudadanas pueden acceder a la herramienta y publicar sus actividades, avances y resultados los cuales serán de ayuda para otros ciudadanos que estén interesados en iniciar un ejercicio de control social en la ciudad. La herramienta también es una plataforma en la cual pueden ampliar sus conocimientos sobre control social aquellas personas interesadas que no conozcan mucho el tema.

Versión de sistema administrador de contenidos: La página está desarrollada bajo Drupal 8.9.8.
Tipo de base de datos: MySQL.

# Instalación

Requisitos:
Para instalar esta herramienta en un ambiente web se requiere un hosting con las siguientes características: 

 PHP 7.3 o superior. 

 MySQL 5.6.51 o superior. 

 300MB de espacio para aplicación. 

 100 MB espacio para base de datos. 

 Espacio en disco prospectivo teniendo en cuenta crecimiento esperado.

Pasos:

 Descargar archivos

 Subir y descomprimir en carpeta raiz del sitio web

 Restaurar copia de la base de datos y crear usuario con privilegios 

 Editar archivo de configuración de Drupal en sites/default/settings/settings.php

 Ingresar al sitio como administrador con los datos del manual

 Cambiar pantalla de inicio por node/1 en menú principal y en configuración/Sistema/Configuraciones básicas del sitio

 Cambiar dato de acceso del administrador

# Secciones
Inicio: desde aquí se accede a todas las secciones.

Participe: esta sección describe las tres formas en las que los usuarios pueden participar de forma activa en échele ojo.

Échele mente: esta sección permite la publicación de vínculos a cursos virtuales sobre Control Social.

Explore – Veedurías ciudadanas: esta sección permite a los usuarios visualizar las veedurías enviadas por la ciudadanía. En esta sección se publican todas las veedurías compartidas por los usuarios que se inscriben con rol Le estoy echando ojo.

Explore – Casos enviados por la ciudadanía: esta sección permite visualizar todos los casos enviados por la ciudadanía en general que no está realizando ejercicios de control social, pero está interesada en que se le haga seguimiento a un caso en particular.

Sobre nosotros: esta sección le permite a los usuarios conocer más acerca de la iniciativa échele ojo.

Contáctenos: esta sección permite a los usuarios comunicarse por medio de un formulario con el equipo échele ojo.

Créditos: esta sección muestra un listado de las personas que participaron en la construcción de la herramienta en todas sus fases. Esta sección de atribución no debe ser eliminada.

# Roles

Usuario anónimo o visitante, moderador, le estoy echando ojo, quiero echarle ojo, administrador. Los roles de la herramienta están asociados a secciones o funcionalidades específicas. Cada rol tiene permitidas diferentes acciones sobre la herramienta.

Usuario anónimo o visitante: este es el usuario con menos privilegios en la plataforma, tiene permitido el envío de casos por medio de la opción Échele un ojo por mí. Estos casos son revisados y aprobados por el rol Moderador.

Usuario quiero echarle ojo: este usuario es el interesado en empezar a echarle ojo a alguna situación pública de la ciudad, pero quiere adquirir conocimiento al respecto. Para esto debe registrarse en la plataforma. Una vez registrado tiene acceso a la siguiente sección personal.

Usuario le estoy echando ojo: este rol también debe registrarse en la página de registro descrita en el rol anterior, pero seleccionando el rol Le estoy echando ojo. Una vez se ha registrado podrá acceder a la siguiente sección personal llamada Mi espacio, que le permite agregar veedurías que está realizando y acceder a las que ya haya compartido en la herramienta. También puede agregar participantes con diferentes roles a su veeduría, este participante debe estar registrado en la plataforma.

Los participantes pueden editar la veeduría, pero la revisión deberá ser aprobada por el creador de la veeduría.

Usuario moderador: este usuario tiene la labor de aprobar casos enviados por Échele un ojo por mí, gestionar completamente casos enviados, aprobar la primera publicación de una veeduría, gestión completa de veedurías publicadas, cambiar el rol de un participante de quiero echarle el ojo a le estoy echando el ojo.

Usuario administrador: este usuario cuenta con todos los privilegios sobre la herramienta y es el encargado de la estabilidad de la misma. Cualquier actualización, instalación, edición adicional que se requiera deberá realizarla en este perfil.
