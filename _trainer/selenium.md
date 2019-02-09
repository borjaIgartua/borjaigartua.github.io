---
layout: default
name: 'Selenium'
position: Trainer
company: Coritel
duration: 16 horas
date: 2016-11-07
header:
  teaser: https://picsum.photos/120/80?image=77&blur
sidebar:
  - title: "Role"
    image: https://picsum.photos/350/250?image=66&blur
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: 'Esta acción formativa va dirigida a Programadores, Analistas, Jefes de proyecto y Arquitectos que deseen implementar pruebas funcionales con Selenium en sus proyectos.'
accordion:
  - item:
      name: Introducción a Selenium
      haschildren: true
      subitems:
        - item:
            name: Propósito
            haschildren: false
        - item:
            name: Selenium IDE
            haschildren: false
  - item:
      name: Utilizando Selenium IDE
      haschildren: true
      subitems:
        - item:
            name: Grabación y reproducción de casos de prueba
            haschildren: false
        - item:
            name: Verificación de casos de prueba 
            haschildren: false
        - item:
            name: Trabajar con bancos de pruebas
            haschildren: false
        - item:
            name: Informes HTML de los caso de prueba
            haschildren: false
  - item:
      name: Configuración Selenium WebDriver
      haschildren: true
      subitems:
        - item:
            name: Configuración con Eclipse
            haschildren: false
        - item:
            name: Helpers
            haschildren: false
        - item:
            name: Plantillas
            haschildren: false
  - item:
      name: Scripts de pruebas
      haschildren: true
      subitems:
        - item:
            name: Configuración de secuencias de comandos de test en Eclipse
            haschildren: false
        - item:
            name: Localización de elementos Web
            haschildren: false
        - item:
            name: Instrucciones de verificación
            haschildren: false
        - item:
            name: Creación de un archivo de registro
            haschildren: false
        - item:
            name: Creación de informes de prueba
            haschildren: false        
  - item:
      name: Mejora de la escritura de la pruebas
      haschildren: true
      subitems:
        - item:
            name: Métodos WebElement
            haschildren: false
        - item:
            name: Creación de mapas de destino
            haschildren: false
        - item:
            name: Modularización de las pruebas
            haschildren: false
  - item:
      name: Identificación de objetos
      haschildren: true
      subitems:
        - item:
            name: Métodos de identificación (Nombre, ID, CSS, DOM, etc ...)
            haschildren: false
        - item:
            name: Manipulación de objetos dinámicos
            haschildren: false
        - item:
            name: Captura de Datos y Validación
            haschildren: false
  - item:
      name: Captura de datos
      haschildren: true
      subitems:
        - item:
            name: Captura y validación de datos de tablas
            haschildren: false
        - item:
            name: Captura y validación de datos de listas
            haschildren: false
        - item:
            name: Captura y validación de árboles HTML
            haschildren: false
  - item:
      name: Opciones de rastreo y trazas
      haschildren: true
      subitems:
        - item:
            name: Trabajar con trazas en Excel
            haschildren: false
        - item:
            name: Adición de capturas de pantalla en archivos
            haschildren: false
        - item:
            name: Diferentes opciones de registro
            haschildren: false
  - item:
      name: Expresiones regulares
      haschildren: true
      subitems:
        - item:
            name: Operadores
            haschildren: false
        - item:
            name: Uso de expresiones regulares para la captura de datos
            haschildren: false
  - item:
      name: Pruebas basadas en datos
      haschildren: true
      subitems:
        - item:
            name: Conexión de fuentes de datos
            haschildren: false
        - item:
            name: Trabajar con parámetros
            haschildren: false
        - item:
            name: Creación de las sentencias dinámicas de validación
            haschildren: false
  - item:
      name: Trabajar con bases de datos
      haschildren: true
      subitems:
        - item:
            name: Conexión a Bases de Datos
            haschildren: false
        - item:
            name: Ejecutar consultas
            haschildren: false
        - item:
            name: Analizar a través de conjuntos de resultados
            haschildren: false
  - item:
      name: Pruebas Multi Browser
      haschildren: true
      subitems:
        - item:
            name: Configuración necesaria para ejecutar las pruebas como IE y Chrome
            haschildren: false
        - item:
            name: Modificación de pruebas para ejecutar en múltiples navegadores
            haschildren: false
        - item:
            name: Creación de prueba Suites va a ejecutar en múltiples navegadores
            haschildren: false
  - item:
      name: Selenium Grid
      haschildren: true
      subitems:
        - item:
            name: Ejecución de la pruebas en las máquinas múltiples
            haschildren: false
        - item:
            name: Ejecución de forma secuencial
            haschildren: false
        - item:
            name: Ejecución en paralelo
            haschildren: false
  - item:
        name: Pruebas de aplicaciones móviles
        haschildren: true
        subitems:
          - item:
              name: Android Driver
              haschildren: false
          - item:
              name: Appium
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
          <p>Selenium automates browsers. That's it! What you do with that power is entirely up to you. Primarily, it is for automating web applications for testing purposes, but is certainly not limited to just that. Boring web-based administration tasks can (and should!) be automated as well.</p>
          <p>Selenium has the support of some of the largest browser vendors who have taken (or are taking) steps to make Selenium a native part of their browser. It is also the core technology in countless other browser automation tools, APIs and frameworks.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>