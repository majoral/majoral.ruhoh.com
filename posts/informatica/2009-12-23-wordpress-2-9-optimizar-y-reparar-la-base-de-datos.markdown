---
comments: true
date: 2009-12-23 21:31:33
layout: post
slug: wordpress-2-9-optimizar-y-reparar-la-base-de-datos
title: 'Wordpress 2.9 Optimizar y Reparar la base de datos '
wordpress_id: 1029
categories:
- informatica
tags:
- mysql
- wordpress

---

> Una de las pocas ventajas de **WordPress 2.9** es que puede **optimizar y reparar la base de datos** y así contribuir a un mejor rendimiento de tu blog. Para activar esta opción solo hay que editar el archivo _wp_confing.php_ que se encuentra en la raíz de la instalación y agregar la siguiente línea:


    define('WP_ALLOW_REPAIR', true);


> Después puedes correr el script desde la URL:

    http://midominio.com/wpadmin/maint/repair.php

 ![](http://blogandweb.com/wp-content/uploads/2009/12/wordpressoptimizar.png)

> Lo que hará simplemente es correr tres funciones de SQL [ANALYZE TABLE](http://dev.mysql.com/doc/refman/5.1/en/analyze-table.html), [REPAIR TABLE](http://dev.mysql.com/doc/refman/5.1/en/repair-table.html) y [OPTIMIZE TABLE](http://dev.mysql.com/doc/refman/5.1/en/optimize-table.html), que de hecho, pueden ejecutarse desde el panel de mySQL; también existen plugins que realizan esta tarea y que WP 2.9 simplemente los agrega.
> 
> Puede ser poco práctico hacer esto periódicamente, aunque hacerlo desde MySQL puede ser aun menos práctico. Ojalá en una futura versión lo tengamos en el panel de administración.
> 
> Vía: [WP Engineer](http://wpengineer.com/wordpress-database-repair-script-in-2-9/


via [Blog and Web](http://feedproxy.google.com/~r/blogandweb/~3/2IdVo3K3rkA/)


  

