---
layout: default
title: 'Developing applications for iOS'
position: Trainer
company: Sunion
duration: 30 horas
date: 2016-09-20
header:
  teaser: /assets/images/apple-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/apple-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: This course is made for mobile developers. Some kind of experience is needed to take advantage of this lessons.

accordion:
  - item:
      name: introduction
      haschildren: true
      subitems:
        - item:
            name: iPhone SDK
            haschildren: false
        - item:
            name: ios_obtain_iphone_sdk
            haschildren: false
  - item:
      name: ios_components
      haschildren: true
  - item:
      name: Objective-C
      haschildren: true
      subitems:
        - item:
            name: ios_what_is_objc
            haschildren: false
        - item:
            name: ios_main_lang_features
            haschildren: false
        - item:
            name: ios_use_object
            haschildren: false
        - item:
            name: ios_create_class
            haschildren: false
        - item:
            name: ios_messaging
            haschildren: false
        - item:
            name: ios_exceptions
            haschildren: false
        - item:
            name: Logging
            haschildren: false
        - item:
            name: ios_testing
            haschildren: false
        - item:
            name: ios_distributed_obj
            haschildren: false
        - item:
            name: ios_classes_library
            haschildren: false
        - item:
            name: ios_apple_integration
            haschildren: false
  - item:
      name: Switf
      haschildren: true
      subitems:
        - item:
            name: ios_foundations
            haschildren: false
        - item:
            name: ios_basic_operators
            haschildren: false
        - item:
            name: ios_char_strings
            haschildren: false
        - item:
            name: ios_collection_types
            haschildren: false
        - item:
            name: ios_functions
            haschildren: false
        - item:
            name: ios_closures
            haschildren: false
        - item:
            name: ios_enums
            haschildren: false
        - item:
            name: ios_classes_and_strucs
            haschildren: false
        - item:
            name: ios_methods
            haschildren: false
        - item:
            name: ios_subscripts
            haschildren: false
        - item:
            name: ios_inheritance
            haschildren: false
        - item:
            name: ios_initialization_deinit
            haschildren: false
        - item:
            name: ios_arc
            haschildren: false
        - item:
            name: ios_optional_chaining
            haschildren: false
        - item:
            name: Conversión de tipos
            haschildren: false
        - item:
            name: ios_nest_types
            haschildren: false
        - item:
            name: ios_extensions
            haschildren: false
        - item:
            name: ios_protocols
            haschildren: false
        - item:
            name: ios_generics
            haschildren: false
        - item:
            name: ios_advance_operators
            haschildren: false
  - item:
      name: ios_architecture_title
      haschildren: true
  - item:
      name: ios_visual_comp
      haschildren: true
      subitems:
        - item:
            name: View Controllers
            haschildren: false
        - item:
            name: Views, Outlets y Actions
            haschildren: false
        - item:
            name: Input Keyboard
            haschildren: false
        - item:
            name: Table view
            haschildren: false
        - item:
            name: ios_screen_rotation
            haschildren: false
  - item: 
      name: ios_cross_platform_suport
      haschildren: true
  - item:
      name: ios_user_defaults
      haschildren: true
  - item:
      name: ios_files
      haschildren: true
  - item:
      name: ios_data_bases
      haschildren: true
  - item:
      name: ios_advance_coding
      haschildren: true
      subitems:
        - item:
            name: ios_animations
            haschildren: false
        - item:
            name: ios_gestures
            haschildren: false
        - item:
            name: ios_acelerometer
            haschildren: false
  - item:
      name: Network Programming
      haschildren: true
      subitems:
        - item:
            name: Web Services
            haschildren: false
        - item:
            name: Bluetooth
            haschildren: false
        - item:
            name: Bonjour
            haschildren: false
        - item:
            name: Apple Push Notification Service
            haschildren: false
        - item:
            name: Mapas
            haschildren: false
  - item:
      name: Background apps
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
          <p>{{ site.data.ui-text[site.locale].ios_desc_1 }}</p>
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>