---
# weight: 100 (Peso o importancia de la pagina en el Blog)
title: "Historia de la computación y la informática"
subtitle: "Fundamentos de Programación"
date: 2023-06-30T18:29:27-03:00
lastmod: 2023-06-30T18:29:27-03:00
draft: false # False publicar, True modo Borrador
author: "DANH"
authorLink: "deltronik.net"
description: " Bien sabemos que la idea de un computador es algo que se fue construyendo poco a poco a lo largo de los años, no es de sorpresa que todo es gracias a toda la evolución en el campo de las matemáticas, la electronica, mecánica y muchas otras areas que se relacionaron de alguna manera con la creación de maquinas de cálculos aritméticos y a algunas personas excepcionales que contribuyeron de manera directa o indirectamente a la evolución de las mismas."
license: "CC BY-NC-SA 4.0"
images: ["banner.png"]

tags: ["programación","informática","fundamentos","desarrollo","sistemas","introducción","computación"]
categories: ["Elementos de Programación"]

featuredImage: "banner.png"
featuredImagePreview: "banner.png"
#RSS
#featured_image: "banner.png"
#image: "banner.png"

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: true
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
  images: [banner.png]
  # ...
---
Bien sabemos que la idea de un computador es algo que se fue construyendo poco a poco a lo largo de los años, no es de sorpresa que todo es gracias a toda la evolución en el campo de las matemáticas, la electronica, mecánica y muchas otras areas que se relacionaron de alguna manera con la creación de maquinas de cálculos aritméticos y a algunas personas excepcionales que contribuyeron de manera directa o indirectamente a la evolución de las mismas.
<!--more-->

Pero no es mi intención llevar en profundidad el desarrollo del mismo, hacerlo seria agobiante, la idea es repasar superficialmente algunos de los detalles que consideremos importantes a lo largo de la historia.

## Precursores

Años antes de la aparición del Gandalf de la biblia, casi unos 1000 A.C para ser un poco exactos apareció la primera herramienta que funciono como soporte para los cálculos., El Ábaco
{{< image src="image/abacus.jpg" caption="Imagen por Michelle Scott" alt="abaco">}}

En la antigüedad el ábaco fue popular en Oriente Próximo,Europa, China y Rusia. Consiste en una fila de cuentas mociles o similares ensartadas en un alambre. Estos representan dígitos y se manipulan para realizar operaciones o incluso cálculos mas 'avanzados' como raíces

### Blaise Pascal (1642)

La maquina de Pascal (Máquina aritmética o Pascalina) fue una calculadora mecánica, esta podia sumar y restar de forma directa mientras que las multiplicaciones y divisiones las realizaba a través de sumas o restas de forma repetitivas (repetidas)

{{< image src="image/pascal.jpg" caption="Carlo Nardone from Roma, Italy" alt="Pascalina">}}

### Gotfried Leibniz (1671)

Mejoro la maquina de cálculos de Blaise Pascal de manera que facilitara las Divisiones y Multiplicaciones.


{{< image src="image/leibniz.jpg" caption="Imagen de Hajotthu-Wikipedia" alt="Calculadora de Leibniz" >}}

Pero esta no fue la única contribución de Leibniz al mundo de la computación e informática., Podemos destacar una calculadora conocida como el Stepped Reckoner, también, y mas importante me atrevería a decir el sistema binario y la teoría de la información algorítmica que anticiparon la idea de "La Máquina de Turing".

### Charles Babbage (1812)

  Babbage presento un proyecto llamado "ingenio diferencial",Su diseño se parecía mucho al de las computadoras modernas ,este consistía en crear una calculadora automática que pudiera tabular funciones matemáticas mediante el método de las diferencias finitas.

  {{<image src="image/babbage.jpg" caption="imagen por Victuallers | Wikimedia commons" alt="PLanos máquina analítica">}}

#### Ada Lovelace
Aunque ninguna de las maquinas de Babbage pudieron construirse en la época debido a problemas técnicos, económicos y personales. El segundo proyecto de Babbage contó con la ayuda Ada Lovelace, una matemática y escritora que tradujo y amplió un articulo sobre la "Maquina Analítica". Lovelace se escribió el primer algoritmo para la máquina analítica, demostrando su potencial más allá de los cálculos numéricos

{{< admonition tip "Ada Lovelace" false >}}
Augusta Ada King, condesa de Lovelace (Londres, 10 de diciembre de 1815-íd., 27 de noviembre de 1852), registrada al nacer como Augusta Ada Byron y conocida habitualmente como Ada Lovelace, fue una matemática y escritora británica, célebre sobre todo por su trabajo acerca de la computadora mecánica de uso general de Charles Babbage, la denominada máquina analítica. Fue la primera en reconocer que la máquina tenía aplicaciones más allá del cálculo puro y en haber publicado lo que se reconoce hoy como el primer algoritmo destinado a ser procesado por una máquina, por lo que se la considera como **la primera programadora de ordenadores**.

Fuente: [Wikipeda](https://es.wikipedia.org/wiki/Ada_Lovelace)
{{< /admonition >}}

### Herman Hollerith (1980)

IMB es una empresa muy reconocida hoy en dia, su fundador Hollerith construye la primera máquina eléctrica, Mejor conocida como máquina tabuladora, usaba tarjetas perforadas para almacenar y procesar los datos de la población.

{{<image src="image/hollerith.jpg" caption="Jennifer | flickr.com" alt="Máquina tabular">}}

En 1911 luego del éxito de su empresa Tabulating Machine Company (o Tabuling Recording Company según mis apuntes de la universidad) la empresa cambia el nombre a la ya conocida Internacional Bussines Machine (IBM) y con ello las tabuladoras empiezan a ampliarse para usos mas generales como manipular datos, contar, acumuladoras y proporcionar funciones matemáticas avanzadas

### Howard Aiken (1944)

La Mark I, fue el primer ordenador electromecánico, se basaba en la maquina analítica de Babbage. Fue utilizada para el calculo del censo y cálculos militares. Utilizaba tarjetas perforadas para recibir instrucciones, realizaba operaciones aritméticas y funciones matemáticas.

{{<image src="image/mark1.jpg" caption="wikimedia commons" alt="Mark I">}}

### John Von Neumann (1945)

Neumann introdujo los conceptos decisivos para el calculo automático., Propuso un modelo (o diseño) para computadoras digitales que pretendía el uso de una memoria compartida para almacenar datos e instrucciones, una unidad de procesamiento que precisaba de una unidad aritmética lógica y una de registros, una unidad de control que contiene el registro de las instrucciones, un contador de programas y los mecanismos de entrada y salida 

{{<image src="image/modelnewmann.jpg" caption="De David strigoi | Wikimedia commons" alt="Modelo de Von Newmann">}}

Dejando de lado los problemas como el cuello de botella de von Neumann, este diseño permitió el desarrollo de computadoras más complejas y avanzadas que pudieron ejecutar programas almacenados en memoria y realizar operaciones con mayor velocidad y flexibilidad.

### John Pesper Eckert y John W. Mauchly (1946)
{{<image src="image/eniac.jpg" alt="ENIAC" caption="International Communications Agency | Wikimedia Commons">}}

La Electrical Numerical Integracion Automatic Computer o simplemente ENIAC fue la primera máquina con circuitos electrónicos, Pesaba cerca de 30 toneladas, poseía cerca de 180000 válvulas de vació, consumía cerca de 15000 voltios de potencia y era capas de realizar 5000 sumas/segundo (1000 veces mas rapida que la MARKI)

### EDVAC (1951)

Neumann diseño la EDVAC (Electronic Discrete Variable Automatic Computer) y en 1945 la empresa Eckert-Mauchly empezó su construcción la cual finalizaría en 1951. EL EDVAC fue de las primeras computadoras electrónicas que podían almacenar datos como instrucciones en una memoria interna, lo que permitía ejecutar programas de forma mas rápida y flexible. Su uso fue principalmente para fines militares y científicos como cálculos balísticos, meteorológicos y genéticos.

{{<image src="image/envac.jpg" alt="EDVAC" caption="Wikimedia Commons">}}

##  1960: Inicio de la revolución digital
A partir de 1959, con la llegada del silicio las computadoras empezaron a presentar un avance significativo y mas acelerado que con sus antecesoras.

### 1959 - 1964: Segunda Generación
  Aparecieron los transistores, con ello una carrera por la miniaturización, la arquitectura de Neumann se hizo presente gracias a las cintas magnéticas. Aparecieron los primeros lenguajes de computación como FORTRAN, ALGOL y el conocido COBOL

```Cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HOLA-MUNDO.
PROCEDURE DIVISION.
    DISPLAY 'HELLO, WORLD'.
    STOP RUN.
```

### 1965 - 1972: Tercera Generación

Los avances en la electrónica no se quedaron en los transistores., ¡No! a algún genio de por allí se le ocurrió que podía juntar muchos de estos diminutos interruptores en un circuito y crear dispositivos mas complejos capaces de procesar información.Y tal vez a otro genio se le ocurrió que podia reducir aún más el tamaño de estos circuitos, envolverlos en una cápsula y bautizarlos como circuitos integrados. Estos circuitos integrados
Los circuitos integrados facilitaron la multiprogramación y multiprocesamiento, aparecieron lenguajes estructurados como PL/1 y ALGOL 68, también llegaron los discos magnéticos

{{<image src="image/ibm200mb.jpg" caption="Arnold Reinhold | Wikimedia Commons" alt="Discos sin cubiertas protectoras, ibm de 200mb">}}

## El alba de las computadoras inteligentes

No se con certeza si estamos transitando la quinta generación de las computadoras, tengo entendido que esta comenzó en el año 1980 y continua hasta nuestros días, pero como hemos visto, la historia de estas mismas se basa en la innovación, creatividad y desafíos. Desde los primeros intentos por automatizar el cálculo hasta las actuales máquinas inteligentes, cada generación con sus características, ventajas y limitaciones.
Hoy estamos atravesando el uso de la inteligencia artificial, la inferencia lógica, el procesamiento paralelo y las redes de comunicación. Las computadoras actuales son capaces de aprender, razonar, resolver problemas y comunicarse entre si y con los humanos. Sin embargo también plantean nuevos retos éticos, sociales y económicos que debemos afrontar con responsabilidad y criterio.
