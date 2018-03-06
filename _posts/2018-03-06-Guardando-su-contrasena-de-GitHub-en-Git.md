---
layout: post
title: "Guardando su contraseña de GitHub en Git"
date: 2018-03-06
description: Decirle a Git que recuerde su nombre de usuario y contraseña de GitHub en windows.
image: 'http://res.cloudinary.com/ernestoaguaysol/image/upload/c_scale,h_399,w_760/v1520358473/password_voczbf.jpg'
category: 'tips'
tags:
- github
- git
- vscode
twitter_text: Decirle a Git que recuerde su nombre de usuario y contraseña de GitHub en windows.
introduction: Decirle a Git que recuerde su nombre de usuario y contraseña de GitHub en windows.
---

 Para recordar contraseña primero debe instalar un shell nativo de Git, como Git para Windows . Con Git para Windows, ejecutar lo siguiente en la línea de comando almacenará sus credenciales:

 ```
  git config --global credential.helper wincred
 ```

> NOTA: solo con windows.

-----

Referencia <a href="https://help.github.com/articles/caching-your-github-password-in-git/#platform-windows">Github.</a>
