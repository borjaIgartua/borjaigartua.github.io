---
layout: default
name: 'Groovy, Spock & Geb'
position: Trainer
company: Panel
duration: 16 horas
date: 2016-10-24
header: 
  teaser: /assets/images/spock-geb-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/spock-geb-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: 'Esta acción formativa va dirigida a Programadores, Analistas y Jefes de proyecto que
            necesiten conocer cómo realizar test de unitarios, de integración y funcionales con los
            frameworks Spock y Geb.'
accordion:
    - item:
        name: Lenguaje Groovy
        haschildren: true
        subitems:
            - item:
                name: Tipos de datos simples. Cadenas
                haschildren: false
            - item:
                name: Creación y manejo de colecciones
                haschildren: false
            - item:
                name: Estructuras de control, Funciones y Clausuras
                haschildren: false
            - item:
                name: POO con Groovy. Clases e interfaces
                haschildren: false
            - item:
                name: Librerías de Groovy
                haschildren: true
                subitems:
                    - item:
                        name: MarkupBuilder y XmlSlurper. Tratamiento de XML
                        haschildren: false
                    - item:
                        name: GroovySQL Bases de datos
                        haschildren: false
                    - item:
                        name: Groovy Builders
                        haschildren: false
                    - item:
                        name: Expandos, Metaprogramacíon y DSL´s
                        haschildren: false
    - item:
        name: Spock
        haschildren: true
        subitems:
            - item:
                name: Instalación
                haschildren: true
                subitems:
                    - item:
                        name: Uso desde maven
                        haschildren: false
                    - item:
                        name: Uso desde gradle
                        haschildren: false
                    - item:
                        name: Uso desde Eclipse
                        haschildren: false
            - item:
                name: Terminología
                haschildren: true
                subitems:
                    - item:
                        name: Especificaciones
                        haschildren: false
                    - item:
                        name: Features y Fixtures
                        haschildren: false
            - item:
                name: Bloques
                haschildren: false
            - item:
                name: Condiciones
                haschildren: false
            - item:
                name: Data Driven Testing
                haschildren: false
            - item:
                name: Excepciones
                haschildren: false
            - item:
                name: Interacciones
                haschildren: false
            - item:
                name: Extensiones
                haschildren: false
            - item:
                name: Test de integración
                haschildren: true
                subitems:
                    - item:
                        name: Bases de datos
                        haschildren: false
                    - item:
                        name: Spring
                        haschildren: false
                    - item:
                        name: Conceptos avanzados
                        haschildren: false
    - item:
        name: Geb
        haschildren: true
        subitems:
            - item:
                name: Instalación y configuración
                haschildren: false
            - item:
                name: El objeto Browser
                haschildren: false
            - item:
                name: Interactuar con el contenido
                haschildren: false
            - item:
                name: Paginas
                haschildren: false
            - item:
                name: Módulos
                haschildren: false
            - item:
                name: Asertos implícitos
                haschildren: false
            - item:
                name: Testing JavaScript y Ajax
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
          <p>Spock is a testing and specification framework for Java and Groovy applications. What makes it stand out from the crowd is its beautiful and highly expressive specification language. Thanks to its JUnit runner, Spock is compatible with most IDEs, build tools, and continuous integration servers.</p>
          <p>Geb is a browser automation solution. It brings together the power of WebDriver, the elegance of jQuery content selection, the robustness of Page Object modelling and the expressiveness of the Groovy language. It can be used for scripting, scraping and general automation — or equally as a functional/web/acceptance testing solution via integration with testing frameworks such as Spock, JUnit & TestNG.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>