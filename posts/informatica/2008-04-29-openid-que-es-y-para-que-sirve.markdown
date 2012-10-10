---
comments: true
date: 2008-04-29 18:46:52
layout: post
slug: openid-que-es-y-para-que-sirve
title: OpenID Que es y para que sirve
wordpress_id: 527
categories:
- informatica
tags:
- identidad
- OpenID
- seguridad

---

 OpenID es un sistema de identificación digital descentralizado pensado específicamente para la web.

Es una manera sencilla de identificarte en multitud de sitios web con los mismos datos, sin tener que recordar diferentes datos de acceso (usuario/contraseña) para cada una de las web que visites.

Una identidad OpenID viene dada por una URL cualquiera que soporte el protocolo OpenId, como la dirección de un blog o de cualquier página web genérica que poseas. Y si no tienes ninguna página propia, puedes usar cualquier servidor OpenId disponible.

¿Por qué usar OpenID ?

La principal ventaja es que solo es necesario teclear una dirección web para identificarte, sin tener que recordar un nombre de ususario ni una constraseña para cada sitio que visitas.

Otro aspecto importante es su carácter abierto. Gracias a ello, es mucho más seguro, extensible y universalizable que los servicios de identificación tradicionales. Debido a su infraestructura, la seguridad de tus datos depende completamente del servidor que los aloje, y si no encuentras ningún servidor de confianza, siempre puedes montarte uno propio.

¿Cómo funciona OpenId?

El protocolo es muy sencillo, y se puede resumir en estos pasos:
	
  1. Creas una cuenta en un servidor de confianza.
	
  2. Opcionalmente, añades un par de líneas a tu web personal, para poder usarla como identificación.
	
  3. Al entrar en un servicio web que soporte OpenID, introduces la URL de tu perfil OpenID o, si has seguido el paso 2, la URL de tu web personal.

  4. Este dato se envía hasta el servidor que elegiste, mostrándote un formulario de entrada en el que tendrás que introducir tu contraseña.

  5. Acto seguido, debes autorizar los datos que quieres compartir con el servicio.
	
  6. El servidor devuelve el control al servicio web, que ya conoce quién eres.

Si te fijas detenidamente, verás por qué OpenID es seguro: el servicio web no tiene acceso a tu contraseña, al contrario de los sistemas tradicionales. Solo tiene acceso a los datos que tú quieres y en el momento que quieres.

Fuente: [http://openid.blogs.es/](http://openid.blogs.es/) y [http://openid.es/](http://openid.es/)

Enlaces relacionados:
	
  * Página oficial OpenID [http://openid.net/](http://openid.net/)
	
  * Servidor de cuentas OpenID [http://www.myopenid.com/](http://www.myopenid.com/)
	
  * OpenID en la Wikipedia: [http://es.wikipedia.org/wiki/OpenID](http://es.wikipedia.org/wiki/OpenID)


 

 
