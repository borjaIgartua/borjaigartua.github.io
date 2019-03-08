---
layout: default
title: HTML5 Frameworks
position: Trainer
company: CLE Formación
duration: 195 horas
date: 2017-04-25
header:
  teaser: /assets/images/html-frameworks.jpg
sidebar:
  - title: "Role"
    image: /assets/images/html-frameworks.jpg
    text: "Trainer"
  - title: level
    text: level_advance
accordion:
    - item:
        name: Repaso de HTML5 y CSS3
        haschildren: true
        subitems:
            - item:
                name: Estructura de la página
                haschildren: false
            - item:
                name: Etiquetas y marcas
                haschildren: false
            - item:
                name: Elementos estructurales
                haschildren: false
            - item:
                name: Elementos semánticos
                haschildren: false
            - item:
                name: Elementos desaprobados
                haschildren: false
            - item:
                name: CSS3
                haschildren: false
                subitems:
                - item:
                    name: Selectores
                    haschildren: false
                - item:
                    name: Pseudo-elementos y Pseudo-clases
                    haschildren: false
                - item:
                    name: Tratamiento de textos
                    haschildren: false
                - item:
                    name: Colores RGBA, HSL y HSLA
                    haschildren: false
                - item:
                    name: Bordes y Fondos
                    haschildren: false
                - item:
                    name: Efectos, Transformaciones y Animaciones
                    haschildren: false
            - item:
                name: Formularios y Elementos
                haschildren: false
            - item:
                name: Audio y vídeo
                haschildren: false
            - item:
                name: Programación HTML 5 y su API
                haschildren: true
                subitems:
                    - item:
                        name: Canvas y SVG
                        haschildren: false
                    - item:
                        name: API de Comunicaciones
                        haschildren: false
                    - item:
                        name: XMLHttpRequest Nivel 2
                        haschildren: false
                    - item:
                        name: Sockets Web
                        haschildren: false
                    - item:
                        name: Web Workers
                        haschildren: false
                    - item:
                        name: Geolocalización
                        haschildren: false
                    - item:
                        name: Almacenamiento
                        haschildren: false
    - item:
        name: Creación de aplicaciones Javascript Crossbrowser con JQuery
        haschildren: true
        subitems:
            - item:
                name: Configuración
                haschildren: false
            - item:
                name: Selectores
                haschildren: false
            - item:
                name: Filtros
                haschildren: false
            - item:
                name: Programación orientada a eventos
                haschildren: false
            - item:
                name: Manipulación de estilos
                haschildren: false
            - item:
                name: Animaciones
                haschildren: false
            - item:
                name: Modificación de html
                haschildren: false
            - item:
                name: Efectos
                haschildren: false
            - item:
                name: Formularios y validación
                haschildren: false
            - item:
                name: Peticiones Ajax y control del estado
                haschildren: false
    - item:
        name: Escribiendo CSS con SaSS
        haschildren: true
        subitems:
            - item:
                name: Configuración SASS
                haschildren: false
            - item:
                name: Reutilización de valores con variables
                haschildren: false
            - item:
                name: Reutilización de las normas con Mixins
                haschildren: false
            - item:
                name: Escribir CSS conciso vía reglas anidadas
                haschildren: false
            - item:
                name: Cálculos con operadores y funciones
                haschildren: false
            - item:
                name: Agrupación de elementos utilizando espacios de nombres
                haschildren: false
            - item:
                name: Importación de archivos
                haschildren: false
            - item:
                name: Precompilación
                haschildren: false
    - item:
        name: Testing con Jasmine
        haschildren: true
        subitems:
            - item:
                name: Configuración
                haschildren: false
            - item:
                name: Escribir la primera prueba Jasmine
                haschildren: false
            - item:
                name: Bloques describe
                haschildren: false
            - item:
                name: Comparadores (Matchers)
                haschildren: false
            - item:
                name: El desarrollo de comparadores personalizados
                haschildren: false
            - item:
                name: Pruebas asíncronas (Ajax) de código JavaScript
                haschildren: false
            - item:
                name: Probando con objetos
                haschildren: false
            - item:
                name: Probando aplicaciones
                haschildren: false
            - item:
                name: Ejecución de los test
                haschildren: false
    - item:
        name: JavaScript en el servidor con Node
        haschildren: true
        subitems:
            - item:
                name: ¿Qué es Node? Cuándo usarlo?
                haschildren: false
            - item:
                name: Módulos de Node. Instalando Node
                haschildren: false
            - item:
                name: Usando npm para instalar módulos
                haschildren: false
            - item:
                name: Eventos
                haschildren: false
            - item:
                name: Manejando el POST
                haschildren: false
            - item:
                name: Enrutamiento
                haschildren: false
            - item:
                name: Acceso a Bases de datos
                haschildren: false
            - item:
                name: WebSockets
                haschildren: true
                subitems:
                    - item:
                        name: Creación de un website
                        haschildren: false
                    - item:
                        name: Creación de una aplicación
                        haschildren: false
            - item:
                name: Sistemas de plantillas (Jade)
                haschildren: false            
    - item:
        name: Angular 2
        haschildren: true
        subitems:
            - item:
                name: Introducción
                haschildren: false
            - item:
                name: Arquitectura
                haschildren: false
            - item:
                name: Datos
                haschildren: false
            - item:
                name: Eventos de entradas de usuario
                haschildren: false
            - item:
                name: Formularios
                haschildren: false
            - item:
                name: Inyección de dependencias
                haschildren: false
            - item:
                name: Sintaxis de plantillas
                haschildren: false
            - item:
                name: Operadores de expresiones
                haschildren: false
    - item:
        name: Nuevas Tendencias
        haschildren: true
        subitems:
            - item:
                name: Polymer
                haschildren: false
            - item:
                name: React
                haschildren: false
---

<div id="main" role="main">
    {% include sidebar.html %}
    <article class="page" itemscope itemtype="https://schema.org/CreativeWork">
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
        </header>
        <section class="page__content" itemprop="text">
          <p>Al acabar el curso, el alumno será capaz de entender como desarrollar aplicaciones Web usando HTML5 y los frameworks: JQuery, SASS, Jasmine, Angular 2 y Node.</p>
          <!-- <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %} -->
        </section>
      </div>
    </article>
</div>