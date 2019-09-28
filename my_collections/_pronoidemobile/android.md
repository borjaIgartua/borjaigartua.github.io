---
layout: default
title: 'Developing applications for Android'
position: Trainer
company: CLE Formación
duration: 30 horas
date: 2017-10-25
header:
  teaser: /assets/images/android-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/android-logo.jpg
    text: "Trainer"
  - title: level
    text: level_advance
accordion:  
  - item:
      name: Introduction
      haschildren: true
      subitems:
        - item:
            name: What is Android?
            haschildren: false
        - item:
            name: Android SDK Installation, Android Studio, Eclipse and ADT
            haschildren: false
        - item:
            name: The APK files
            haschildren: false
        - item:
            name: Emulators and phisycal devices
            haschildren: false
        - item:
            name: XML file and AndroidManifest.xml
            haschildren: false
        - item:
            name: Sign  APK and distribution
            haschildren: false
  - item:
      name: Applications
      haschildren: true
      subitems:
        - item:
            name: Application characteristics
            haschildren: false
        - item:
            name: Activities
            haschildren: false
        - item:
            name: Activities life cycle
            haschildren: false
        - item:
            name: Intents
            haschildren: false
  - item:
      name: Generation user interfaces
      haschildren: true
      subitems:
        - item:
            name: Layouts y views
            haschildren: false
        - item:
            name: ViewGroups
            haschildren: false
        - item:
            name: Advanced views
            haschildren: false
        - item:
            name: Screens resolutions
            haschildren: false
        - item:
            name: ListView y Adapters
            haschildren: false
        - item:
            name: How to handle an event
            haschildren: false
        - item:
            name: Styles and themes
            haschildren: false
  - item:
      name: Menu, Dialogs and Notifications
      haschildren: true
      subitems:
        - item:
            name: Contextual menu
            haschildren: false
        - item:
            name: Menu items, submenu and contextual menu
            haschildren: false
        - item:
            name: Dialogs
            haschildren: false
        - item:
            name: Toasts
            haschildren: false
        - item:
            name: Notifications
            haschildren: false
  - item:
      name: Data persistancy and content providers
      haschildren: true
      subitems:
        - item:
            name: Preferences and screen states
            haschildren: false
        - item:
            name: Files
            haschildren: false
        - item:
            name: Android SQLite
            haschildren: false
        - item:
            name: Content providers
            haschildren: false
  - item:
      name: Graphics and 2D, 3D Animations
      haschildren: false
  - item:
      name: Background services
      haschildren: true
      subitems:
        - item:
            name: How to execute
            haschildren: false
        - item:
            name: Local and remote services
            haschildren: false
        - item:
            name: Threads and AsyncTask
            haschildren: false
  - item:
      name: Sensors
      haschildren: true
      subitems:
        - item:
            name: Camera photo
            haschildren: false
        - item:
            name: Network conection and bluetooth
            haschildren: false
        - item:
            name: Location services
            haschildren: false
        - item:
            name: 'Sensor Manager, how to: accelerometer, orientation'
            haschildren: false
        - item:
            name: Vibration
            haschildren: false
  - item:
      name: App Widgets and Live Folders
      haschildren: false
  - item:
      name: Publishing an app
      haschildren: false
  - item:
      name: Google APIS
      haschildren: false
  - item:
      name: Native code with Android NDK
      haschildren: false
  - item:
      name: testing Android apps
      haschildren: false
  - item:
      name: How to acces remote services
      haschildren: true
      subitems:
        - item:
            name: HTTP / SOAP / Rest Requests
            haschildren: false
        - item:
            name: Processing XML / JSON
            haschildren: false
  - item:
      name: Frameworks to develop apps
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
            <p>{{ site.data.ui-text[site.locale].android_desc_1 }}</p>
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>