---
layout: default
title: 'Elasticsearch'
position: Trainer
company: CLE
date: 2016-06-20
duration: 16 horas
header:
  teaser: /assets/images/elasticsearch-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/elasticsearch-logo.jpg
    text: "Trainer"
  - title: level
    text: level_advance
  - title: go_for
    text: course_for
accordion:  
    - item:
        name: introduction
        haschildren: true
        subitems:
            - item:
                name: elastic_terminology
                haschildren: false
            - item:
                name: elastic_basics
                haschildren: false
            - item:
                name: elastic_configuration
                haschildren: false
    - item:
        name: elastic_distributed
        haschildren: true
        subitems:
            - item:
                name: elastic_cluester
                haschildren: false
            - item:
                name: elastic_fragments_replica
                haschildren: false
            - item:
                name: elastic_config
                haschildren: false
            - item:
                name: elastic_local_access
                haschildren: false       
    - item:
        name: elastic_tenancy
        haschildren: true
        subitems:
            - item:
                name: elastic_multiple_index
                haschildren: false
            - item:
                name: elastic_aliases
                haschildren: false
            - item:
                name: elastic_index_op
                haschildren: false
            - item:
                name: elastic_data_intro
                haschildren: false
    - item:
        name: elastic_indexes
        haschildren: true
        subitems:
            - item:
                name: elastic_analisis
                haschildren: false
            - item:
                name: elastic_assignments
                haschildren: false
            - item:
                name: elastic_index_operations
                haschildren: false
            - item:
                name: elastic_version_control
                haschildren: false
            - item:
                name: elastic_adjustments
                haschildren: false
    - item:
        name: elastic_searches
        haschildren: true
        subitems:
            - item:
                name: elastic_DSL_queries
                haschildren: false
            - item:
                name: elastic_sort
                haschildren: false
            - item:
                name: elastic_facets
                haschildren: false
            - item:
                name: elastic_search_types
                haschildren: false
            - item:
                name: elastic_highligting
                haschildren: false
            - item:
                name: elastic_routing
                haschildren: false
    - item:
        name: elastic_advanced_search
        haschildren: true
        subitems:
            - item:
                name: elastic_nested_docs
                haschildren: false
            - item:
                name: elastic_parent_child
                haschildren: false
            - item:
                name: elastic_location
                haschildren: false
            - item:
                name: elastic_perco
                haschildren: false
            - item:
                name: elastic_relevance
                haschildren: false
    - item:
        name: elastic_adv_dist_model
        haschildren: true
        subitems:
            - item:
                name: elastic_recover_cluster
                haschildren: false
            - item:
                name: elastic_low_level_replicas
                haschildren: false
            - item:
                name: elastic_recover_fragments
                haschildren: false
    - item:
        name: elastic_big_data
        haschildren: true
        subitems:
            - item:
                name: elastic_multiple_index
                haschildren: false
            - item:
                name: elastic_reroute
                haschildren: false
            - item:
                name: elastic_routing_aliases
                haschildren: false
            - item:
                name: elastic_data_architecture
                haschildren: false
    - item:
        name: elastic_prod_ready
        haschildren: true
        subitems:
            - item:
                name: elastic_performance
                haschildren: false
            - item:
                name: elastic_data_stream
                haschildren: false
            - item:
                name: elastic_memory
                haschildren: false
    - item:
        name: elastic_prod_exec
        haschildren: true
        subitems:
            - item:
                name: elastic_monitoring
                haschildren: false
            - item:
                name: elastic_alerts
                haschildren: false
            - item:
                name: elastic_statics
                haschildren: false
    - item:
        name: Logstash
        haschildren: true
    - item:
        name: Kibana
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
            <p>{{ site.data.ui-text[site.locale].elastic_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].elastic_desc_2 }}</p>
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>