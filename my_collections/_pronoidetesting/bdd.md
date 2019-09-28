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
        name: Introduction
        haschildren: true
        subitems:
            - item:
                name: What is BDD?
                haschildren: false
            - item:
                name: BDD nowadays
                haschildren: false
    - item:
        name: Requirements definition process on BDD
        haschildren: true
        subitems:
            - item:
                name: User Stories
                haschildren: false
            - item:
                name: Three Amigos
                haschildren: false
            - item:
                name: 'Bussines goals: features'
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
        name: Codification
        haschildren: true
        subitems:
            - item:
                name: Scene automatization
                haschildren: false
            - item:
                name: Cucumber
                haschildren: false
            - item:
                name: Gherkin
                haschildren: false
    - item:
        name: Improving the code
        haschildren: true
    - item:
        name: Acceptance test for user interface layer
        haschildren: true
        subitems:
            - item:
                name: Acceptance test
                haschildren: false
            - item:
                name: Selenium
                haschildren: false
    - item:
        name: Documents management
        haschildren: true
    - item:
        name: How to build on BDD
        haschildren: true
        subitems:
            - item:
                name: Continuos integration
                haschildren: false
            - item:
                name: Documentation
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
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>