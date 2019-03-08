---
layout: default
title: 'Introduction to MATLAB'
position: Trainer
company: Indra
duration: 12 horas
date: 2017-09-13
header:
  teaser: /assets/images/matlab-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/matlab-logo.jpg
    text: "Trainer"
  - title: level
    text: level_basic
  - title: go_for
    text: 'Management and forecast demands department.'
accordion:
    - item:
        name: Introducción
        haschildren: true
    - item:
        name: Operadores matemáticos
        haschildren: true
    - item:
        name: Introducción a funciones básicas
        haschildren: true
    - item:
        name: Cálculo matricial
        haschildren: true
    - item:
        name: Ampliación de conceptos
        haschildren: true
    - item:
        name: Filtrado de datos y otras utilidades
        haschildren: true
    - item:
        name: Introducción a la programación Matlab
        haschildren: true
    - item:
        name: Puesta en marcha del caso práctico individual
        haschildren: true
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
            <p>Tanto si tiene que analizar datos como desarrollar algoritmos
            o crear modelos, MATLAB se ha diseñado para la forma en que piensa y el trabajo que realiza.</p>
            <p>MATLAB combina un entorno de escritorio perfeccionado para el análisis iterativo y los procesos de diseño con un lenguaje de programación que expresa las matemáticas de matrices y arrays directamente.</p>
            <p>Las apps de MATLAB le permiten ver cómo funcionan diferentes algoritmos con sus datos. Realice iteraciones hasta obtener los resultados deseados y, después, genere automáticamente un programa de MATLAB para reproducir o automatizar su trabajo.</p>
            <p>Escale sus análisis para la ejecución en clusters, GPUs y nubes únicamente con cambios menores en el código. No es necesario volver a escribir el código ni aprender programación para Big Data y técnicas de manejo de datos fuera de memoria.</p>
            <p>El objetivo de este curso es proporcionar los conceptos de Matlab necesarios para
            que el alumno pueda desarrollar parte de su trabajo diario en un entorno de matlab,
            aprovechando las ventajas que esta herramienta ofrece para el tratamiento de datos. El
            curso será totalmente práctico y se examinan todos los aspectos básicos de Matlab -
            tipos de datos (escaleras y matriciales), funciones, creación de gráficos e importación/
            exportación de datos. Se realiza también una pequeña introducción a la programación en
            Matlab.</p>
          <!-- <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %} -->
        </section>
      </div>
    </article>
</div>