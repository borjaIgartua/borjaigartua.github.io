---
layout: default
title: Behavior Driven Development
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
  - title: level
    text: level_advance
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
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
        </header>
        <section class="page__content" itemprop="text">
            <p>{{ site.data.ui-text[site.locale].bdd_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].bdd_desc_2 }}</p>
            <p>{{ site.data.ui-text[site.locale].bdd_desc_3 }}</p>
          <!-- <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %} -->
        </section>
      </div>
    </article>
</div>