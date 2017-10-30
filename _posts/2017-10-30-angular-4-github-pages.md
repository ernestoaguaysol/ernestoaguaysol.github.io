---
layout: post
title: "Publicar proyecto Angular 4 en GitHub Pages"
date: 2017-10-30
description: Como haceer un deploy utilizando github pages y angular-cli-ghpages.
image: 'http://res.cloudinary.com/ernestoaguaysol/image/upload/c_scale,h_399,w_760/v1509405111/angularygitgubpages_yk2ikv.jpg'
category: 'angular'
tags:
- angular 4
- github
- npm
twitter_text: LComo haceer un deploy utilizando github pages y angular-cli-ghpages.
introduction: Como haceer un deploy utilizando github pages y angular-cli-ghpages.
---

Para hacer un Deploy de nuestra App hecho en Angular hacia Github Pages, primero tenemos que tener nuestro repositorio remoto listo, después devemos intalar un modulo en forma global de node, si ya lo tienes puedes saltar este paso.

### instalar angular-cli-ghpages
Este comando tiene los siguientes requisitos previos:
* Node.js 4.x
* Git 1.7.6 o superior
* opcional: proyecto angular creado a través angular-cli

Para instalar el comando, ejecute lo siguiente:
`npm i -g angular-cli-ghpages`

Ejecute.

`ng build --prod --base-href https://USERNAME.github.io/REPOSITORY_NAME/`

eperemos que termine, y luego ejecutamos

``angular-cli-ghpages``

o también hay un comando mas corto

```agh```

y esperamos a que la consola nos devuelva el mensaje: ``Successfully published!``

> Nota: Este último comando suele tardar un poco y no muestra ningun proceso, asi que solo nos queda esperar...

Listo, ahora podemos ir a la url que le pasamos    https://USERNAME.github.io/REPOSITORY_NAME/   
y deveriamos entrar a nuestra web hacha con angular 4

-----

Mas info? <a href="https://www.npmjs.com/package/angular-cli-ghpages">angular-cli-ghpages.</a>
