---
comments: true
date: 2008-04-28 22:10:30
layout: post
slug: '526'
title: Webcron Automatizar tareas en tu servidor
wordpress_id: 526
categories:
- informatica
tags:
- Crontab
- Linux
- servidor

---

Webcron es un servicio para automatizar tareas a determinadas horas. Si conoces Unix o Linux seguramente habras oído hablar de Crontab. **Webcron** es una adaptación Web de este Crontab. http://www.dominio.com/guardar_base.php


**Webcron** te permitirá lanzar tareas a horas concretas ejecutando un archivo desde tu web. Por ejemplo, para hacer un back-up de tu base de datos, solamente tendrás que escribir un programa guardar_base.php, el cual guardará tu base de datos en un archivo y alojarlo en tu web, luego añade una tarea en tu **Webcron** para lanzar la consulta SQL:


Ejemplos:

**Quiero ejecutar una vez al dìa mi programa, el cual va a guardar mi base de datos** 
	
* url : http://www.webcron.org/guardar_base.php

	
* hora : 6 para las 6

	
* los demàs campos se dejan en blanco o se pone una asterisco

**Quiero lanzar estadìsticas 1 vez al mes el dìa 1 a las 2 de la mañana**
	
* url : http://www.webcron.org/estadìsticas.php

	
* dìa del mes : 1 para el dìa 1 del mes

	
* hora : 2 para las 2

	
* los demàs campos se dejan en blanco o se pone una asterisco

**Quiero poner al día mis archivos RSS cada hora**
	
* url : http://www.webcron.org/rss.php

	
* hora : * para cada hora

	
* los demàs campos se dejan en blanco o se pone una asterisco

**Quiero mandar un email para felicitar el año nuevo a las doce el dìa 1de enero**
	
* url : http://www.webcron.org/mail.php

	
* hora : 0 para las doce

	
* mes : 1 para el mes de enero

	
* dìa del mes : 1 para el primero

	
* año : * para cada año

**Quiero mandar un email sólo el viernes 13 a las doce**
	
* url : http://www.webcron.org/mail_v13.php

	
* hora : 0 pour minuit

	
* dìa del mes : 13

	
* dìa de la semana : 5 para el viernes

	
* los demàs campos se dejan en blanco o se pone una asterisco *

Fuente: [http://www.webcron.org/](http://www.webcron.org/)
