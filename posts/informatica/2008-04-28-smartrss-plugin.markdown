---
comments: true
date: 2008-04-28 20:04:24
layout: post
slug: smartrss-plugin
title: SmartRSS Plugin para WordPress
wordpress_id: 525
categories:
- informatica
tags:
- rss
- wordpress

---

SmartRSS es un Plugin para WordPress que te permite insertar automáticamente entradas en tu blog transforma tu blog mediante la sindicación a multiples feed RSS

**Opciones:**

- Herramienta para la administración de los rss feeds
- Cada feed puede asignarse a una categoría.
- Una vez importado el feed se puede relacionar con otros feed añadiendo un poco de código
- Necesita el uso de los trabajos cron para importar los feed de forma periódica y automática (si no se tiene acceso a programar el cron en vuestro servidor podeis usar el servicio  en esta web: [http://www.webcron.org/](http://www.webcron.org/) que hara el mismo trabajo :-)

**El paquete contiene:**

- smart_rss.php file - Propiamente el plugin
- wp_smartrss.php - El archivo cron que se encarga de importar los feed

**Instalacion:**

- Subir los archivos smart_rss.php a la carpeta  wp-content/plugins de tu instalación de wordpress
- Accede a la pantalla **Plugins **del panel del administrador y **actívalo **
- En la pestaña **Opciones** ->**SmartRss** podras añadir los feed que desees importar.
- Sube el archivo wp_smartrss.php al directorio raiz de tu wordpress. Por razones de seguridad es conveniente renombrar el archivo.
- Para iniciar el proceso de importación visita la pagina http://tudominio/wp_smartrss.php. Si quieres que este proceso sea automático deberas configurar un proceso cron que ejecute este php.
- Para configurar un trabajo cron puedes usar escribir una orden parecidad a esta:

		“_nice –adjustment=19 /usr/bin/php /$full-path-to-the-file/wp_smartrss.php_” 
		or
		“_nice –adjustment=19 /usr/bin/php /$full-path-to-the-file/your_file_name.php_”

- Si prefieres subir el cron en otro servidor edita las siguiente línea del archivo wp_smartrss.php:

    	_require_once(’wp-config.php’);_  
      
  y sustituyela por algo asi como:

    	_require_once(’/$full-path-to-wordpress/wp-config.php’);_
    
   donde $full-path-to-wordpress es el path completo a tu instalación de wordpress

- **Visualizar Artículos Relacionados: **

  Añade este código al archivo single.php del diseñó de plantilla que estes usando:

        < ?php smartrss_related_posts(5, 10, '<li><b style="font-size:14px;">', '</b>', '', '', false, false); ?>**

**Parámetros de la Función:** 

	smartrss_related_posts(limit, len, before_title, after_title , before_post, after_post , show_pass_post, show_limit)

- limit = Número de entradas relacionadas a visualizar
- len = Número de palabras a incluir, si show_limit esta activado
- before_title = Código html code a añadir antes del título
- after_title = Código html code a añadir después del título
- before_post = Código html code a añadir antes de la entrada
- after_post =Código html code a añadir después de la entrada
- show_past_post = Incluir las entradas protegidas por contraseña
- show_limit = Indica si se limita el número de palabras (ver -len)

[Puedes bajar el Plugin desde aquí](http://www.devplug.net/download/smartrss.zip)

Fuente: [http://www.devplug.net/smartrss-plugin/](http://www.devplug.net/smartrss-plugin/)


