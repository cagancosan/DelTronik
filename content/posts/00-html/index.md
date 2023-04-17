---
title: "HTML"
subtitle: "Hypertext Markup Language"
date: 2023-04-16T21:32:45-03:00
lastmod: 2023-04-16T21:32:45-03:00
draft: true
author: "DanyRDia"
authorLink: "https://www.facebook.com/DanyRdia"
description: "El café con leche es como el café pero con leche"
license: "MIT"
images: [pre.jpg]

tags: ["html","desarrollo","css","introducción","programación"]
categories: ["Desarrollo Web"]

featuredImage: ""
featuredImagePreview: "pre.jpg"

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

Como su nombre lo indica es un lenguaje de marcado el cual es utilizado para estructurar el contenido de una pagina web. Es decir, es quien le dice al navegador cual es el contenido a mostrar de una pagina

<!--more-->

## Etiquetas

HTML esta compuesto de elementos llamados etiquetas, estos en la mayoría de los casos para su escritura respetan la siguiente estructura:

```html
<etiqueta_de_apertura> Contenido de la etiqueta </etiqueta_de_cierra>
```

Podemos notar 3 partes principales que componen un elemento en HTML:

1. Etiqueta de apertura: Todos los elementos en html llevan una etiqueta de apertura que por lo general es el nombre de la etiqueta en medio de los símbolos menor que y mayor que ("<" y ">").

2. El contenido: este el contenido del elemento, el cual puede ser texto, una imagen u inclusive otra etiqueta 

3. Etiqueta de cierre: La gran mayoría de los elementos lleva la etiqueta de cierre que a diferencia de la apertura se le añade una barra lateral junto al signo menor que ("</" y ">")

## Función de una Etiqueta

Existen múltiples etiquetas en HTML pero podemos diferenciarlas por su uso de la siguiente manera:

###### Etiquetas de contenidos

    Aquí podemos hallar todas aquellas  cuya característica principal es brindar contenido a la pagina por ejemplo: textos, contenido multimedia y vídeos

###### Etiquetas de estructuras

    Las etiquetas de estructuras se usan para definir el espacio que ocupa cada una de las secciones de una pagina, por ejemplo define los limites entre la cabecera de la pagina, el cuerpo, el pie de pagina, un menú, una barra lateral, etc. 

## Estructura de un documento HTML

Como vimos en html existen un sin fin de etiquetas para introducir contenido o definir la estructura de nuestra pagina. Esto es posible gracias a su funcionamiento como 'árbol', es decir, un documento html es un árbol de etiquetas el cual esta compuesto por un elemento o tronco principal del cual derivan sus ramas.

```html
<documento_html>
           <tronco_principal>
                    <cabecera>
                        <etiqueta_de_contenido>
                                Menu de nuestro sitio web
                        </etiqueta_de_contenido>
                    </cabecera>

                    <cuerpo>
                        <etiqueta_de_contenido>
                                Contenido de nuestro sitio web
                        </etiqueta_de_contenido>
                    </cuerpo>
                     <pie_de_pagina>
                                   contenido del pie de pagina
                     </pie_de_pagina>
            </tronco_principal>
</documento_html>
```

{{< mermaid >}}
    graph LR
    A[Documento_HTML] --> B[Tronco_Principal]
    B --> C[Cabecera_de_Pagina_Web]
    C --> D[Menu_de_Pagina_Web]
    C --> G[Titulo_de_la_pagina ]
    B --> E[Contenido_del_Sitio ]
    E --> H[Publicaciones]
    E -->I[articulos]
    B --> F[Pie_de_Pagina]
    F -->J[derechos_de_autor]
    F -->K[redes_sociales ]

{{< /mermaid >}}

A esto se lo conoce como DOM (Document Object Model) y como vemos se organiza de forma jerárquica, lo cual a futuro con otras tecnologías nos sirve para manipular el comportamiento de nuestra pagina web 

## Estructura de una pagina Web

Otra forma típica de ver la estructura de un documento HTML es hacerlo desde el punto de vista de desarrollo Web, como una estructura de cuadros o bloques que representen las secciones tipicas de una pagina web

![DomHTML](./TreeMapHTML.png)

Notese como el documento HTML contiene el elemento padre "Pagina Web", y este contiene el cuerpo principal el cual contiene la cabecera, el contenido de la página, una barra lateral y el pie de página

### Bloques y Lineas

Una de las características presentes en esta forma de representar un documento HTML es la de los elementos en bloque y los elementos en lineas, veraz las etiquetas en html pueden categorizarce tambien en:

- Elementos en Bloque: Son aquellos elementos cuyo espacio de ocupación es lineal, es decir, elementos como en este caso "cabecera" que si agregáramos un elemento ya sea anterior o posterior a este, el mismo se imprimiría/mostraría arriba o debajo

- Elementos en Linea: estos elementos son aquellas etiquetas cuya característica es que pueden ponerse alineadamente uno detrás de otro, como en este caso "contenido de pagina" y "barra lateral". Aunque siendo mucho mas especifico esta propiedad se encuentra presente con mas notoriedad en las etiquetas de textos  