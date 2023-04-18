---
title: "Etiquetas"
subtitle: "Caracteristicas y propiedades de etiquetas en html"
date: 2023-04-17T17:33:25-03:00
lastmod: 2023-04-17T17:33:25-03:00
draft: true
author: "DanyRdia"
authorLink: "https://www.facebook.com/DanyRdia"
description: "El café con leche es como el café pero con leche"
license: "MIT"
images: []

tags: ["html","desarrollo web","programación","estructura","css","js"]
categories: ["Desarrollo Web"]

featuredImage: ""
featuredImagePreview: "pre.png"

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: false
lightgallery: true
ruby: true
fraction: true
fontawesome: true
linkToMarkdown: true
rssFullText: false

toc:
  enable: true
  auto: true
code:
  copy: true
  maxShownLines: 50
math:
  enable: false
  # ...
mapbox:
  # ...
share:
  enable: true
  # ...
comment:
  enable: true
  # ...
library:
  css:
    # someCSS = "some.css"
    # located in "assets/"
    # Or
    # someCSS = "https://cdn.example.com/some.css"
  js:
    # someJS = "some.js"
    # located in "assets/"
    # Or
    # someJS = "https://cdn.example.com/some.js"
seo:
  images: []
  # ...
---

En HTML todo el contenido y estructura se defina bajo etiquetas, y por si solas estas etiquetas pueden hasta cierto punto describir la apariencia de un documento pero existen propiedades y características llamados "atributos" que permiten una mayor flexibilidad de los elementos en HTML.

<!--more-->

## características de una Etiqueta

Un elemento en html se compone de 3 partes esenciales:

- Etiqueta de apertura: <nombre_de_la_etiqueta>
- Etiqueta de cierre: </nombre_de_la_etiqueta>
- Contenido: Son los datos que van en medio de la etiqueta de apertura y de cierre

```html
<Etiqueta> Contenido </Etiqueta>
```

Por otro lado deberíamos tener en cuenta que existen ciertas etiquetas que no necesariamente requieren de la etiqueta de cierre.

Y dependiendo de su uso puede ser una etiqueta:

- Etiquetas de contenido: Son aquellas utilizadas para incrustar contenido como texto, títulos, imágenes, etc.

- Etiquetas de estructuras: Son aquellas etiquetas utilizadas para darle forma al documento, es decir, aquellas que limitan espacios o secciones como el menú, el pie de pagina, una barra lateral, el contenido principal, un artículo, etc.

- Etiquetas semanticas: son aquellas utilizadas para alterar el contenido ser poner el texto en negrita, cursiva, etc.

- Etiquetas de Metadatos: Son aquellas utilizadas para enlazar archivos de configuración u darle propiedades iniciales al documento mediante la indexación o inclusión de elementos de terceros

### Disposición en pantalla

Los elementos de un documento html pueden representarce como bloques o secciones en pantalla, los cuales, dependiendo de su uso o categoría posee un espacio inicial especifico en pantalla.

###### Elementos "vacíos"

    Aquellas etiquetas de Metadatos por lo general al escribirlas en el documento pasan, visualmente para el usuario, desapercibidas por el navegador. Por ejemplo una etiqueta que anuncie el idioma en el cual estará escrito el contenido de la pagina o el enlace a una característica de terceros para enriquecer el documento o mejorar su funcionamiento. Ejemplo:

```html
<html>
    <Etiqueta_de_estructura>
        <Etiqueta_de_configuración>
    </Fin_Etiqueta_de_estructura>
</html>
```

Por lo general, estas etiquetas son importantes para el navegador, así enlazar y configurar propiedades señalas por el desarrollador en un principio, Pero son imperceptibles visualmente por el usuario.

##### Elementos en bloque

Son aquellos elementos cuyo espacio de impresión en principio seria el 100% del ancho de pantalla, y que si agregáramos otro elemento junto al mismo este solo se imprimiría después de un salto de linea. Ejemplo:

| Cabecera del sitio web  |
|:-----------------------:|
| Cuerpo del sitio web    |
| Pie de pagina del sitio |

Estos elementos, en principio, son etiquetas de estructuras que acaparan el 100% del ancho en pantalla

##### Elementos en linea

Los elementos en linea tiene la particularidad de ser mas flexibles en principio, ya que o permiten la impresión de múltiples elementos en una misma linea, Por lo general esto se aprecia mucho en aquellas etiquetas utilizadas para alterar el texto. Ejemplo

| Elemento 1 | Elemento 2 | Elemento 3 |
| ---------- | ---------- | ---------- |

Si, suponemos que cada elemento es una fracción de texto con diversas propiedades, intuimos que pueden ser impresos sucesivamente uno detrás de otro y en la misma linea

## Propiedades

Los elementos en HTML por lo general podemos decir que destacan dos propiedades básicas

#### 1 - Contenido

El contenido de una etiqueta se ve definido por el tipo de etiqueta que estemos utilizando, por ejemplo las etiquetas que son de texto tendrán texto como contenido, etiquetas de enlaces serán hipervinculos, las etiquetas multimedia deberán tener vídeo, imágenes u contenido de terceros. Pero por otro lado las etiquetas pueden tener como contenido otras etiquetas, por ejemplo las etiquetas de estructuras tendrán otras etiquetas de estructuras dentro y estas pueden tener otras, o pueden tener etiquetas de contenido

```html
<etiqueta_de_estructura>
            <etiqueta_de_menu>
                    <etiqueta_de_vinculos> 
                            www.Dirección_de_pagina_web.com
                    </fin_etiqueta_de_vinculos>
            </fin_etiqueta_de_menu>
</fin_etiqueta_de_estructura> 
```

Como podemos ver aquí, la etiqueta de estructura posee como contenido otra etiqueta de estructura que señala la sección de un menú de direcciones, el cual es contenido de la misma

#### 2 - Atributos

Sabemos que un elemento posee una etiqueta de inicio, el contenido y una etiqueta de cierre. Ademas de esto cada elemento posee propiedades especiales que nos permite enriquecer el documento o cambiar el comportamiento de la pagina mediante tecnologías ajenas a html o en base a las propiedades extendidas de cada elemento llamadas atributos.

```html
<Etiqueta_de_Apertura> Contenido </Etiqueta_de_cierre> 
```

Sabemos que esta es la estructura básica de un elemento en html, ahora, si quisiéramos añadirle determinados atributos a este elemento haríamos escribiendo los mismo dentro de a etiqueta de apertura y a continuación del nombre de la etiqueta.

```html
<Etiqueta_de_apertura Atributo="valor">Contenido</Etiqueta_de_cierre>
```