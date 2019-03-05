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
  - title: level
    text: level_basic
  - title: go_for
    text: c_plus_course_for
accordion:  
    - item:
        name: c_plus_introduction
        haschildren: true
        subitems:
            - item:
                name: c_plus_history
                haschildren: false
            - item:
                name: c_plus_basics
                haschildren: false
    - item:
        name: c_plus_language_basics
        haschildren: true
        subitems:
            - item:
                name: c_plus_var_operator_type
                haschildren: false
            - item:
                name: c_plus_control_flow
                haschildren: false    
    - item:
        name: c_plus_array_point
        haschildren: true
        subitems:
            - item:
                name: c_plus_arrays
                haschildren: false
            - item:
                name: c_plus_swap
                haschildren: false
            - item:
                name: c_plus_pointers
                haschildren: false
            - item:
                name: c_plus_memory
                haschildren: false            
            - item:
                name: c_plus_ref
                haschildren: false
            - item:
                name: c_plus_atributes
                haschildren: false
            - item:
                name: c_plus_void_pointers
                haschildren: false
    - item:
        name: c_plus_poo
        haschildren: true
        subitems:
            - item:
                name: c_plus_classes
                haschildren: false
            - item:
                name: c_plus_visibility
                haschildren: false
            - item:
                name: c_plus_this_pointer
                haschildren: false
            - item:
                name: c_plus_header_and_code
                haschildren: false
            - item:
                name: c_plus_consts
                haschildren: false
            - item:
                name: c_plus_statics
                haschildren: false
            - item:
                name: c_plus_friend
                haschildren: false
    - item:
        name: c_plus_op_overload
        haschildren: true
    - item:
        name: c_plus_ag_comp
        haschildren: true
    - item:
        name: c_plus_inheritance
        haschildren: true
        subitems:
            - item:
                name: c_plus_inherit_intro
                haschildren: false
            - item:
                name: c_plus_inherit_basic
                haschildren: false
            - item:
                name: c_plus_access_spec
                haschildren: false
            - item:
                name: c_plus_change_access
                haschildren: false
            - item:
                name: c_plus_multi_inherit
                haschildren: false
            - item:
                name: c_plus_virtual_classes
                haschildren: false
    - item:
        name: c_plus_virutal_func
        haschildren: true
        subitems:
            - item:
                name: c_plus_point_parent
                haschildren: false
            - item:
                name: c_plus_virtual_func
                haschildren: false
            - item:
                name: c_plus_abstract_class
                haschildren: false
            - item:
                name: c_plus_interfaces
                haschildren: false
    - item:
        name: c_plus_files
        haschildren: true
        subitems:
            - item:
                name: c_plus_ofstream
                haschildren: false
            - item:
                name: c_plus_ifstream
                haschildren: false
            - item:
                name: c_plus_random_data_access
                haschildren: false
            - item:
                name: c_plusfstream
                haschildren: false
    - item:
        name: c_plus_templates
        haschildren: true
        subitems:
            - item:
                name: c_plus_func_temp
                haschildren: false
            - item:
                name: c_plus_classes_temp
                haschildren: false
            - item:
                name: c_plus_specialization
                haschildren: false
    - item:
        name: c_plus_exceptions
        haschildren: true
        subitems:
            - item:
                name: c_plus_try_catch_throw
                haschildren: false
            - item:
                name: c_plus_catch_all
                haschildren: false
            - item:
                name: c_plus_exc_inheritance
                haschildren: false
    - item:
        name: c_plus_stl
        haschildren: true
        subitems:
            - item:
                name: c_plus_intro
                haschildren: false
            - item:
                name: c_plus_collections
                haschildren: false
            - item:
                name: c_plus_iteractors
                haschildren: false
            - item:
                name: c_plus_algorithms
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