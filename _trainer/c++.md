---
layout: default
name: 'Programación Orientada a Objetos con C++'
position: Trainer
company: Indra
duration: 30 horas
date: 2016-07-18
header:
  teaser: /assets/images/c-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/c-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Básico
  - title: "Dirigido a"
    text: Esta acción formativa va dirigida a Programadores que quieran adquirir el dominio del lenguaje C++
accordion:  
    - item:
        name: Introducción a C++
        haschildren: true
        subitems:
            - item:
                name: Historia
                haschildren: false
            - item:
                name: Conceptos básicos
                haschildren: false
    - item:
        name: Bases del lenguaje
        haschildren: true
        subitems:
            - item:
                name: Variables, operadores y  tipos
                haschildren: false
            - item:
                name: Control de flujo
                haschildren: false    
    - item:
        name: Arrays y punteros
        haschildren: true
        subitems:
            - item:
                name: Arrays
                haschildren: false
            - item:
                name: Swap
                haschildren: false
            - item:
                name: Punteros
                haschildren: false
            - item:
                name: Memoria dinámica, new y delete
                haschildren: false            
            - item:
                name: Variables de referencia
                haschildren: false
            - item:
                name: Acceso a los atributos y métodos
                haschildren: false
            - item:
                name: Puntero void
                haschildren: false
    - item:
        name: Programación Orientada a Objetos
        haschildren: true
        subitems:
            - item:
                name: Clases en C++
                haschildren: false
            - item:
                name: Visibilidad
                haschildren: false
            - item:
                name: El puntero this
                haschildren: false
            - item:
                name: Cabecera (.h) y código (.cpp) de una clase
                haschildren: false
            - item:
                name: Objetos const
                haschildren: false
            - item:
                name: Atributos y métodos static
                haschildren: false
            - item:
                name: Funciones y clases friend
                haschildren: false
    - item:
        name: Sobrecarga de operadores
        haschildren: true
    - item:
        name: Agregación, composición, inicializadores de constructor
        haschildren: true
    - item:
        name: Herencia
        haschildren: true
        subitems:
            - item:
                name: Introducción a la herencia
                haschildren: false
            - item:
                name: Herencia básica
                haschildren: false
            - item:
                name: Especificaciones de acceso (visibilidad)
                haschildren: false
            - item:
                name: Accediendo a miembros y cambiando su visibilidad
                haschildren: false
            - item:
                name: Herencia Múltiple
                haschildren: false
            - item:
                name: Clases bases virtuales
                haschildren: false
    - item:
        name: Funciones virtuales
        haschildren: true
        subitems:
            - item:
                name: Punteros a la clase padre y a la clase hija
                haschildren: false
            - item:
                name: Funciones virtuales
                haschildren: false
            - item:
                name: Clases abstractas y Funciones virtuales puras
                haschildren: false
            - item:
                name: Clases interface
                haschildren: false
    - item:
        name: Trabajando con ficheros
        haschildren: true
        subitems:
            - item:
                name: ofstream
                haschildren: false
            - item:
                name: ifstream
                haschildren: false
            - item:
                name: Ficheros de acceso aleatorio
                haschildren: false
            - item:
                name: fstream
                haschildren: false
    - item:
        name: Templates
        haschildren: true
        subitems:
            - item:
                name: Funciones con templates
                haschildren: false
            - item:
                name: Clases con templates
                haschildren: false
            - item:
                name: Especialización
                haschildren: false
    - item:
        name: Excepciones
        haschildren: true
        subitems:
            - item:
                name: try, catch y throw
                haschildren: false
            - item:
                name: catch all y especificadores de excepciones
                haschildren: false
            - item:
                name: Herencia y la clase Exception
                haschildren: false
    - item:
        name: Standard Template Library (STL)
        haschildren: true
        subitems:
            - item:
                name: Introducción
                haschildren: false
            - item:
                name: Colecciones
                haschildren: false
            - item:
                name: Iteradores
                haschildren: false
            - item:
                name: Algoritmos
                haschildren: false
---

<div id="main" role="main">
    {% include sidebar.html %}
    <article class="page" itemscope itemtype="https://schema.org/CreativeWork">
      <meta itemprop="headline" content="{{ page.name }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
        <section class="page__content" itemprop="text">
          <p>Los alumnos entenderán los fundamentos del lenguaje de programación C++ y las técnicas de programación orientada a objetos, creando una base sólida de conceptos y conocimientos que luego utilizaran en su día a día profesional.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>