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
      name: Introducción a Android y al entorno de desarrollo
      haschildren: true
      subitems:
        - item:
            name: ¿Qué es Android?
            haschildren: false
        - item:
            name: Instalación Android SDK, Android Studio, Eclipse y ADT
            haschildren: false
        - item:
            name: Los archivos APK
            haschildren: false
        - item:
            name: Emuladores y dispositivos físicos
            haschildren: false
        - item:
            name: El uso de ficheros XML y el archivo AndroidManifest.xml
            haschildren: false
        - item:
            name: Firmado con APK y distribución
            haschildren: false
  - item:
      name: Aplicaciones
      haschildren: true
      subitems:
        - item:
            name: Características de las aplicaciones
            haschildren: false
        - item:
            name: Actividades
            haschildren: false
        - item:
            name: Ciclo de vida de las actividades
            haschildren: false
        - item:
            name: Intents
            haschildren: false
  - item:
      name: Generación de interfaces de usuario
      haschildren: true
      subitems:
        - item:
            name: Layouts y vistas
            haschildren: false
        - item:
            name: ViewGroups
            haschildren: false
        - item:
            name: Vistas avanzadas
            haschildren: false
        - item:
            name: Resoluciones y tamaños de pantalla
            haschildren: false
        - item:
            name: ListView y Adapters
            haschildren: false
        - item:
            name: Manejo de eventos
            haschildren: false
        - item:
            name: Estilos y temas
            haschildren: false
  - item:
      name: Menús, Diálogos y Notificaciones
      haschildren: true
      subitems:
        - item:
            name: Menús de opciones y contextuales
            haschildren: false
        - item:
            name: Menú ítems, submenús y menús contextuales
            haschildren: false
        - item:
            name: Dialogos
            haschildren: false
        - item:
            name: Toasts
            haschildren: false
        - item:
            name: Notificaciones
            haschildren: false
  - item:
      name: Persistencia de datos y content providers
      haschildren: true
      subitems:
        - item:
            name: Preferencias y estados de pantalla
            haschildren: false
        - item:
            name: Ficheros
            haschildren: false
        - item:
            name: Bases de datos Android SQLite
            haschildren: false
        - item:
            name: Proveedores de contenido
            haschildren: false
  - item:
      name: Gráficos y animaciones 2D y 3D
      haschildren: false
  - item:
      name: Servicios en segundo plano
      haschildren: true
      subitems:
        - item:
            name: Modelo de ejecución
            haschildren: false
        - item:
            name: Servicios Locales y Remotos
            haschildren: false
        - item:
            name: Threads y AsyncTask
            haschildren: false
  - item:
      name: Dispositivos y Sensores
      haschildren: true
      subitems:
        - item:
            name: La cámara de fotos
            haschildren: false
        - item:
            name: La conexión de red y bluetooth
            haschildren: false
        - item:
            name: Posicionamiento y ubicación
            haschildren: false
        - item:
            name: 'Sensor Manager y uso de sensores: acelerómetro, orientación'
            haschildren: false
        - item:
            name: Vibración
            haschildren: false
  - item:
      name: App Widgets y Live Folders
      haschildren: false
  - item:
      name: Publicación de aplicaciones
      haschildren: false
  - item:
      name: Librerías Google APIS
      haschildren: false
  - item:
      name: Uso de código nativo con Android NDK
      haschildren: false
  - item:
      name: Pruebas de las aplicaciones Android
      haschildren: false
  - item:
      name: Acceso a servicios remotos
      haschildren: true
      subitems:
        - item:
            name: Peticiones HTTP / SOAP / Rest
            haschildren: false
        - item:
            name: Procesado de XML / JSON
            haschildren: false
  - item:
      name: Frameworks para desarrollo de aplicaciones
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
            <p>Aprender a desarrollar una aplicación en el sistema operativo para móviles Android. Conocer los programas y entornos para su desarrollo así como las etapas necesarias hasta su publicación y posterior comercialización.</p>
          <!-- <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %} -->
        </section>
      </div>
    </article>
</div>