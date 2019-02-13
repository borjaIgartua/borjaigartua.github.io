---
layout: default
name: Behavior Driven Development
position: Trainer
company: Indra
duration: 12 horas
date: 2017-09-25
header:
  teaser: /assets/images/bdd-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/bdd-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
accordion:  
    - item:
        name: Introducción a BDD
        haschildren: true
        subitems:
            - item:
                name: Definición y Origen
                haschildren: false
            - item:
                name: BDD en la actualidad
                haschildren: false
    - item:
        name: Definición de requisitos usando BDD
        haschildren: true
        subitems:
            - item:
                name: Historias de usuario
                haschildren: false
            - item:
                name: Three Amigos
                haschildren: false
            - item:
                name: 'Goals de negocio: features'
                haschildren: true
                subitems:
                - item:
                    name: Feature Injection
                    haschildren: false
                - item:
                    name: Impact Mapping
                    haschildren: false
                - item:
                    name: Purpose-Based Aligment Model
                    haschildren: false
    - item:
        name: Codificación
        haschildren: true
        subitems:
            - item:
                name: Automatización de escenarios
                haschildren: false
            - item:
                name: Cucumber
                haschildren: false
            - item:
                name: Gherkin
                haschildren: false
    - item:
        name: Mejorando el código
        haschildren: true
    - item:
        name: Aceptación para la capa de interface de usuario
        haschildren: true
        subitems:
            - item:
                name: Tests de aceptación
                haschildren: false
            - item:
                name: Selenium
                haschildren: false
    - item:
        name: Gestión de la documentación
        haschildren: true
    - item:
        name: El proceso de build en BDD
        haschildren: true
        subitems:
            - item:
                name: Integración continua
                haschildren: false
            - item:
                name: Documentación
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
            <p>Behavior Driven Development es un proceso de desarrollo de software que trata de combinar los aspectos puramente técnicos y los de negocio, de manera que tengamos un marco de trabajo, y un marco de pruebas, en el que los requisitos de negocio formen parte del proceso de desarrollo.</p>
            <p>BDD es una evolución de TDD (Test Driven Development o Desarrollo Dirigido por Pruebas). De hecho, el concepto de BDD fue inicialmente introducido por Dan North como respuesta a los problemas que surgían al enseñar TDD.</p>
            <p>Como hemos visto, en su origen DBB empezó siendo un sistema que sustituía a TDD aplicando estos modelos de comportamiento, actualmente se ha convertido en mucho mas, según su creador “using examples at múltiple levels to create a shared understanding and surface uncertainty to deliver software that matters”.</p>
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>