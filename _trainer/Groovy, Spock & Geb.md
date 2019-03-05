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
  - title: level
    text: level_advance
  - title: go_for
    text: spock_course_go_for
accordion:
    - item:
        name: spock_groovy
        haschildren: true
        subitems:
            - item:
                name: spock_data_types_string
                haschildren: false
            - item:
                name: spock_data_types_collec
                haschildren: false
            - item:
                name: spock_control_flow
                haschildren: false
            - item:
                name: spock_poo
                haschildren: false
            - item:
                name: spock_libraries
                haschildren: true
                subitems:
                    - item:
                        name: spock_lib_xml
                        haschildren: false
                    - item:
                        name: spock_lib_sql
                        haschildren: false
                    - item:
                        name: Groovy Builders
                        haschildren: false
                    - item:
                        name: spock_lib_dsl
                        haschildren: false
    - item:
        name: Spock
        haschildren: true
        subitems:
            - item:
                name: spock_install
                haschildren: true
                subitems:
                    - item:
                        name: spock_from_maven
                        haschildren: false
                    - item:
                        name: spock_from_gradle
                        haschildren: false
                    - item:
                        name: spock_from_eclipse
                        haschildren: false
            - item:
                name: spock_terms
                haschildren: true
                subitems:
                    - item:
                        name: spock_specs
                        haschildren: false
                    - item:
                        name: spock_features
                        haschildren: false
            - item:
                name: spock_blocks
                haschildren: false
            - item:
                name: spock_conditions
                haschildren: false
            - item:
                name: spock_ddd
                haschildren: false
            - item:
                name: spock_exceptions
                haschildren: false
            - item:
                name: spock_iteractors
                haschildren: false
            - item:
                name: spock_extensions
                haschildren: false
            - item:
                name: spock_integration_test
                haschildren: true
                subitems:
                    - item:
                        name: spock_dd
                        haschildren: false
                    - item:
                        name: spock_spring
                        haschildren: false
                    - item:
                        name: spock_advanced
                        haschildren: false
    - item:
        name: Geb
        haschildren: true
        subitems:
            - item:
                name: spock_geb_install
                haschildren: false
            - item:
                name: spock_geb_browser
                haschildren: false
            - item:
                name: spock_geb_content
                haschildren: false
            - item:
                name: spock_geb_pages
                haschildren: false
            - item:
                name: spock_geb_modules
                haschildren: false
            - item:
                name: spock_geb_asserts
                haschildren: false
            - item:
                name: spock_geb_ajax
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