---
layout: default
name: 'Selenium'
position: Trainer
company: Coritel
duration: 16 horas
date: 2016-11-07
header:
  teaser: /assets/images/selenium-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/selenium-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: level_advance
  - title: go_for
    text: sel_course_go_for
accordion:
  - item:
      name: introduction
      haschildren: true
      subitems:
        - item:
            name: sel_purpouse
            haschildren: false
        - item:
            name: sel_ide
            haschildren: false
  - item:
      name: sel_using
      haschildren: true
      subitems:
        - item:
            name: sel_record_use_case
            haschildren: false
        - item:
            name: sel_verify_uc
            haschildren: false
        - item:
            name: sel_work_test_suites
            haschildren: false
        - item:
            name: sel_html_docs
            haschildren: false
  - item:
      name: sel_driver_config
      haschildren: true
      subitems:
        - item:
            name: sel_eclipse
            haschildren: false
        - item:
            name: sel_helpers
            haschildren: false
        - item:
            name: sel_template
            haschildren: false
  - item:
      name: sel_scripts
      haschildren: true
      subitems:
        - item:
            name: sel_config_comands
            haschildren: false
        - item:
            name: sel_find_el
            haschildren: false
        - item:
            name: sel_verify_instruct
            haschildren: false
        - item:
            name: sel_register_file
            haschildren: false
        - item:
            name: sel_create_doc
            haschildren: false        
  - item:
      name: sel_improving_tests
      subitems:
        - item:
            name: sel_we_el_method
            haschildren: false
        - item:
            name: sel_target_maps
            haschildren: false
        - item:
            name: sel_modular_tests
            haschildren: false
  - item:
      name: sel_obj_identify
      haschildren: true
      subitems:
        - item:
            name: sel_obj_find_method
            haschildren: false
        - item:
            name: sel_dynamic_obj
            haschildren: false
        - item:
            name: sel_dynamic_obj
            haschildren: false
  - item:
      name: sel_get_data
      haschildren: true
      subitems:
        - item:
            name: sel_get_data_table
            haschildren: false
        - item:
            name: sel_get_data_list
            haschildren: false
        - item:
            name: sel_get_data_tree
            haschildren: false
  - item:
      name: sel_find_and_log
      haschildren: true
      subitems:
        - item:
            name: sel_excel
            haschildren: false
        - item:
            name: sel_screeshot
            haschildren: false
        - item:
            name: sel_log_options
            haschildren: false
  - item:
      name: sel_regex
      haschildren: true
      subitems:
        - item:
            name: sel_operators
            haschildren: false
        - item:
            name: sel_regex_capture_data
            haschildren: false
  - item:
      name: sel_data_driven
      haschildren: true
      subitems:
        - item:
            name: sel_ddd_conex
            haschildren: false
        - item:
            name: sel_ddd_params
            haschildren: false
        - item:
            name: sel_ddd_verify
            haschildren: false
  - item:
      name: sel_work_dd
      haschildren: true
      subitems:
        - item:
            name: sel_dd_conexion
            haschildren: false
        - item:
            name: sel_exec_query
            haschildren: false
        - item:
            name: sel_analize
            haschildren: false
  - item:
      name: sel_multi_browser
      haschildren: true
      subitems:
        - item:
            name: sel_multi_browser_config
            haschildren: false
        - item:
            name: sel_mult_b_changes
            haschildren: false
        - item:
            name: sel_mult_exec_suit
            haschildren: false
  - item:
      name: sel_grid
      haschildren: true
      subitems:
        - item:
            name: sel_nodes
            haschildren: false
        - item:
            name: sel_sequence
            haschildren: false
        - item:
            name: sel_parallel
            haschildren: false
  - item:
        name: sel_mobile
        haschildren: true
        subitems:
          - item:
              name: sel_android
              haschildren: false
          - item:
              name: sel_appium
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