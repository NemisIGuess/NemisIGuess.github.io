---
layout: post
title:  "Publishing to GitHub Pages"
date:   2025-07-02 21:39:00 +0200
tags: 
excerpt_separator: <!--more-->
---
Probando a ver que tal funciona.
<!--more-->

Ha sido muy facil configurar la pagina para que aparezca en .github.io directamente.

Esta bastante incorporado en github en si, con nombrar el repositorio correctamente y configurarlo
en la parte de `Pages` de los settings del repo ya es suficiente.

He añadido proteccion a `main` para que no se pueda pushear directamente, que tenga que ser por PR
y ahora añadire que haga la build con Jekyll en las PRs contra `main` intentando asegurar asi que no se
rompa.