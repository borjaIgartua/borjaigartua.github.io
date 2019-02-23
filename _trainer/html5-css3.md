---
layout: default
name: HTML5 y CSS3 Avanzado
position: Trainer
company: CMC
duration: 16 horas
date: 2017-02-06
header:
  teaser: /assets/images/html-css-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/html-css-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: 'Esta acción formativa va dirigida a Maquetadores, Programadores y Analistas.'
accordion:
    - item:
        name: Geolocalización
        haschildren: true
        subitems:
            - item:
                name: ¿Para qué se usa la Geolocalización?
                haschildren: false
            - item:
                name: Soporte del navegador para la geolocalización
                haschildren: false
            - item:
                name: El objeto Geolocation
                haschildren: false
            - item:
                name: API de Geolocalización
                haschildren: false
            - item:
                name: Propiedades del objeto PositionOptions
                haschildren: false
            - item:
                name: Atributos de la interfaz Position
                haschildren: false
    - item:
        name: Mensajería Web
        haschildren: true
        subitems:
            - item:
                name: Métodos de Mensajería Web
                haschildren: false
            - item:
                name: Establecimiento de confianza entre dominios
                haschildren: false
            - item:
                name: Establecimiento de confianza con ORIGEN
                haschildren: false
            - item:
                name: Cross Origin Resource Sharing (CORS)
                haschildren: false
            - item:
                name: Puertos y canales de mesnsajes
                haschildren: false
            - item:
                name: Métodos de MessagePort
                haschildren: false
            - item:
                name: El objeto Message Event
                haschildren: false
            - item:
                name: Controles de seguridad adicional
                haschildren: false
    - item:
        name: Web Workers
        haschildren: true
        subitems:
            - item:
                name: ¿Por qué utilizar Web Workers?
                haschildren: false
            - item:
                name: Características disponibles
                haschildren: false
            - item:
                name: ¿Cómo funcionan los Web Workers?
                haschildren: false
            - item:
                name: 'WorkerGlobalScope: Propiedades, métodos y eventos'
                haschildren: false
            - item:
                name: Soporte del navegador para Web Workers
                haschildren: false
            - item:
                name: Tipos de Web Workers
                haschildren: false
            - item:
                name: Terminación del trabajador desde script
                haschildren: false
    - item:
        name: Arrastrar y soltar
        haschildren: true
        subitems:
            - item:
                name: ¿Qué es drag and drop?
                haschildren: false
            - item:
                name: Arrastrar y soltar con una "carga útil" de datos
                haschildren: false
            - item:
                name: Eventos de arrastre
                haschildren: false
            - item:
                name: Evento soltar
                haschildren: false
    - item:
        name: Aplicaciones desconectadas
        haschildren: true
        subitems:
            - item:
                name: Soporte del navegador para Desconectado Aplicaciones
                haschildren: false
            - item:
                name: Vaciado de la caché del navegador
                haschildren: false
            - item:
                name: Entendimiento applicationCache
                haschildren: false
            - item:
                name: La propiedad navigator.online
                haschildren: false
            - item:
                name: Asociación del Manifiesto caché con una Página Web
                haschildren: false
    - item:
        name: XMLHttpRequest Nivel 2
        haschildren: true
        subitems:
            - item:
                name: Beneficios de XHR2
                haschildren: false
            - item:
                name: 'El objeto XHR: Estados'
                haschildren: false
            - item:
                name: 'El objeto XHR: Controladores de eventos'
                haschildren: false
            - item:
                name: 'El objeto XHR: Métodos'
                haschildren: false
            - item:
                name: 'El objeto XHR: Propiedades'
                haschildren: false
    - item:
        name: Web Sockets
        haschildren: true
        subitems:
            - item:
                name: Introducción Web Sockets
                haschildren: false
            - item:
                name: Propiedades de los WebSocket
                haschildren: false
            - item:
                name: Controladores de eventos
                haschildren: false
            - item:
                name: Métodos
                haschildren: false
            - item:
                name: Uso de un servidor WebSocket con el API WebSocket
                haschildren: false
    - item:
        name: Eventos enviados por el servidor
        haschildren: true
        subitems:
            - item:
                name: Mensajes del servidor
                haschildren: false
            - item:
                name: Creación de un EventSource
                haschildren: false
            - item:
                name: Propiedades EventSource
                haschildren: false
            - item:
                name: Eventos desde un EventSource
                haschildren: false
            - item:
                name: Las ventajas de los eventos enviados por el servidor
                haschildren: false
            - item:
                name: Las desventajas de  los eventos enviados por el servidor
                haschildren: false
    - item:
        name: CSS3
        haschildren: true
        subitems:
            - item:
                name: Selectores
                haschildren: false
            - item:
                name: Especificidad
                haschildren: false
            - item:
                name: Contenido generado
                haschildren: false
            - item:
                name: Mediaqueries
                haschildren: false
            - item:
                name: Depuración
                haschildren: false
            - item:
                name: Colores
                haschildren: false
            - item:
                name: Fuentes, sombras y efectos de texto
                haschildren: false
            - item:
                name: Bordes y Fondos
                haschildren: false
            - item:
                name: Degradados
                haschildren: false
            - item:
                name: Transformaciones
                haschildren: false
            - item:
                name: Transiciones y animaciones
                haschildren: false
            - item:
                name: Otras características de CSS
                haschildren: false
            - item:
                name: 'Programando en CSS: Sass'
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
            <p>HTML5  es la última versión de HTML. El término representa dos conceptos diferentes:
            <br/>Se trata de una nueva versión de HTML, con nuevos elementos, atributos y comportamientos. <br/>Contiene un conjunto más amplio de tecnologías que permite a los sitios Web y a las aplicaciones ser más diversas y de gran alcance. A este conjunto se le llama HTML5</p>
            <p>CSS3 es la última evolución del lenguaje de las Hojas de Estilo en Cascada (Cascading Style Sheets), y pretende ampliar la versión CSS2.1. Trae consigo muchas novedades altamente esperadas , como las esquinas redondeadas, sombras, gradientes , transiciones o animaciones, y nuevos layouts como multi-columnas, cajas flexibles o maquetas de diseño en cuadrícula (grid layouts).</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>