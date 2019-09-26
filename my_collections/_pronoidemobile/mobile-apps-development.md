---
layout: default
title: 'Mobile Application Development III Edition'
position: Trainer
company: Telefónica Educación Digital
date: 2016-04-01
header:
  teaser: /assets/images/telefonica-talentum-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/telefonica-talentum-logo.jpg
    text: "Trainer"
  - title: "Responsibilities"
    text: tlf_dev_tasks
accordion:  
  - item:
      name: introduction
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_what_is_about
            haschildren: false
        - item:
            name: tlf_dev_how_starts
            haschildren: false
        - item:
            name: tlf_dev_required_tools
            haschildren: false
  - item:
      name: Objective C
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_environment
            haschildren: false
        - item:
            name: tlf_dev_classes
            haschildren: false
        - item:
            name: tlf_dev_pointer
            haschildren: false
        - item:
            name: tlf_dev_properties
            haschildren: false
        - item:
            name: NSString y NSNumber
            haschildren: false
        - item:
            name: tlf_dev_collections
            haschildren: false
        - item:
            name: tlf_dev_inheritance
            haschildren: false
  - item:
      name: iOS
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_IDE
            haschildren: false
        - item:
            name: tlf_dev_view_controller
            haschildren: false                       
        - item:
            name: tlf_dev_visual_comp
            haschildren: false
        - item:
            name: tlf_dev_comunication_views
            haschildren: false
        - item:
            name: tlf_dev_contraints
            haschildren: false
        - item:
            name: tlf_dev_navigation
            haschildren: false
  - item:
      name: tlf_dev_persistence
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_plist_files
            haschildren: false
        - item:
            name: SQLite
            haschildren: false
  - item:
      name: tlf_dev_advance_comp
      haschildren: true
      subitems:
        - item:
            name: UITableView
            haschildren: false
        - item:
            name: UIPickerView
            haschildren: false
        - item:
            name: UIWebView
            haschildren: false
        - item:
            name: MKMapView
            haschildren: false
  - item:
      name: tlf_dev_remote_serv
      haschildren: true
      subitems:
        - item:
            name: introduction
            haschildren: false
        - item:
            name: tlf_dev_rest
            haschildren: false
  - item:
      name: Swift
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_swift_objc
            haschildren: false
        - item:
            name: tlf_dev_swift_apps
            haschildren: false
  - item:
      name: tlf_dev_apps_distribution
      haschildren: true
      subitems:
        - item:
            name: tlf_dev_apps_register
            haschildren: false
        - item:
            name: iTunes Connect
            haschildren: false
        - item:
            name: tlf_dev_dist
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
          <p>{{ site.data.ui-text[site.locale].tlf_desc_1 }}</p>
          <p>{{ site.data.ui-text[site.locale].tlf_desc_2 }}</p>
          <p>{{ site.data.ui-text[site.locale].tlf_desc_3 }}</p>
          <br/>
          <p>{{ site.data.ui-text[site.locale].tlf_desc_4 }}</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>