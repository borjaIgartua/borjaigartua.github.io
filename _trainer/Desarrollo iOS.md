---
layout: default
name: 'Desarrollo de aplicaciones para iOS'
position: Trainer
company: Sunion
duration: 30 horas
date: 2016-09-20
header:
  teaser: https://picsum.photos/120/80?image=77&blur
sidebar:
  - title: "Role"
    image: https://picsum.photos/350/250?image=66&blur
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: Esta acción formativa  está destinada a  programadores de dispositivos móviles
accordion:
  - item:
      name: Introducción
      haschildren: true
      subitems:
        - item:
            name: iPhone SDK
            haschildren: false
        - item:
            name: Obtener iPhone SDK
            haschildren: false
  - item:
      name: Componentes (Xcode, iPhone Simulator, Constructor de interfaces …)
      haschildren: true
  - item:
      name: Objective-C
      haschildren: true
      subitems:
        - item:
            name: ¿Qué es Objective-C?
            haschildren: false
        - item:
            name: Características fundamentales del lenguaje
            haschildren: false
        - item:
            name: Uso de Objetos
            haschildren: false
        - item:
            name: Creación de clases
            haschildren: false
        - item:
            name: Intercambio de mensajes
            haschildren: false
        - item:
            name: Gestión de excepciones
            haschildren: false
        - item:
            name: Logging
            haschildren: false
        - item:
            name: Aserciones y testing
            haschildren: false
        - item:
            name: Objetos distribuidos
            haschildren: false
        - item:
            name: Biblioteca de clases básica
            haschildren: false
        - item:
            name: Integración con productos de Apple
            haschildren: false
  - item:
      name: Switf
      haschildren: true
      subitems:
        - item:
            name: Fundamentos
            haschildren: false
        - item:
            name: Operadores básicos
            haschildren: false
        - item:
            name: Cadenas y Caracteres
            haschildren: false
        - item:
            name: Tipos de colecciones
            haschildren: false
        - item:
            name: Funciones
            haschildren: false
        - item:
            name: Closures
            haschildren: false
        - item:
            name: Enumeraciones
            haschildren: false
        - item:
            name: Clases y estructuras
            haschildren: false
        - item:
            name: Métodos
            haschildren: false
        - item:
            name: Subscripts
            haschildren: false
        - item:
            name: Herencia
            haschildren: false
        - item:
            name: Inicialización y deinicialización
            haschildren: false
        - item:
            name: Conteo automático de referencias
            haschildren: false
        - item:
            name: Encadenamiento opcional
            haschildren: false
        - item:
            name: Conversión de tipos
            haschildren: false
        - item:
            name: Tipos anidados
            haschildren: false
        - item:
            name: Extensiones
            haschildren: false
        - item:
            name: Protocolos
            haschildren: false
        - item:
            name: Genéricos
            haschildren: false
        - item:
            name: Operadores avanzados
            haschildren: false
  - item:
      name: Arquitectura de iPhone OS
      haschildren: true
  - item:
      name: Componentes Visuales
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
            name: Rotación de pantalla
            haschildren: false
  - item: 
      name: Soporte multiplataforma (iPhone e iPad) 
      haschildren: true
  - item:
      name: Preferencias de aplicación
      haschildren: true
  - item:
      name: Manejo de ficheros
      haschildren: true
  - item:
      name: Almacenamiento en base de datos
      haschildren: true
  - item:
      name: Programación avanzada iOS
      haschildren: true
      subitems:
        - item:
            name: Animaciones y reproducción de video
            haschildren: false
        - item:
            name: Gestos
            haschildren: false
        - item:
            name: Acelerómetro
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
      <meta itemprop="headline" content="{{ page.name }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
        <section class="page__content" itemprop="text">
          <p>El alumno aprenderá las bases del lenguaje Objective-C / Swift, al mismo tiempo que conocerás las posibilidades que te brinda el framework Cocoa-Touch para crear interfaces gráficas, conectarte con un servidor, acceder a bases de datos SQL, y consultar la ubicación geográfica del usuario.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>