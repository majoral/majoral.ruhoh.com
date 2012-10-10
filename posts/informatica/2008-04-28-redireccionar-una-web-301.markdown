---
comments: true
date: 2008-04-28 15:05:11
layout: post
slug: redireccionar-una-web-301
title: Redireccionar una web 301
wordpress_id: 523
categories:
- informatica
tags:
- 301
- Redireccionar

---

Se trata de utilizar un “Error 301″ (Movido permanentemente) cuando la URL cambia para que:

  1. Los visitantes vean la nueva dirección.

  2. Los buscadores actualicen a tu nueva dirección.

  3. No tener contenido duplicado en la red.

Es algo muy sencillo de hacer siempre que aún conserves acceso al sitio antiguo, el mejor método es mediante un fichero `.htaccess` en el directorio raíz del sitio con el siguiente código:

	Redirect permanent / http://nuevaurl


O una redirección _completa_ (recomiendo esta):
  
	RewriteEngine on
	RewriteCond %{HTTP_HOST} !^nuevaurl.com$ [NC]
	RewriteRule ^(.*)$ http://nuevaurl.com/$1 [R=301,L]    

Otro método es con PHP:
    
	<?php
	Header( "HTTP/1.1 301 Moved Permanently" );
	Header( "Location: http://nuevaurl" );
	?>

[Fuente](http://sigt.net/archivo/redirecciones-301-algo-que-se-olvida-cuando-migras.xhtml)

