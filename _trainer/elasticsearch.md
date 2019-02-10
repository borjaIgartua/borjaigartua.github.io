---
layout: default
name: 'Elasticsearch'
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
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: Esta acción formativa va dirigida a Programadores, Analistas y Administradores de sistemas.
accordion:  
    - item:
        name: Introducción
        haschildren: true
        subitems:
            - item:
                name: Terminología
                haschildren: false
            - item:
                name: Conceptos básicos
                haschildren: false
            - item:
                name: Configuración y operaciones básicas
                haschildren: false
    - item:
        name: Modelo distribuido
        haschildren: true
        subitems:
            - item:
                name: Cluster Elasticsearch
                haschildren: false
            - item:
                name: Fragmentos y réplicas
                haschildren: false
            - item:
                name: Configuración
                haschildren: false
            - item:
                name: APIs y acceso local
                haschildren: false       
    - item:
        name: Multi Tenancy
        haschildren: true
        subitems:
            - item:
                name: Múltiples índices
                haschildren: false
            - item:
                name: Alias de índices
                haschildren: false
            - item:
                name: Operaciones entre índices
                haschildren: false
            - item:
                name: Introducción al flujo de datos
                haschildren: false
    - item:
        name: Índice Elasticsearch
        haschildren: true
        subitems:
            - item:
                name: Análisis
                haschildren: false
            - item:
                name: Asignaciones
                haschildren: false
            - item:
                name: Operaciones de índices
                haschildren: false
            - item:
                name: Control de versiones
                haschildren: false
            - item:
                name: APIs y ajustes
                haschildren: false
    - item:
        name: Búsquedas
        haschildren: true
        subitems:
            - item:
                name: DSL de consulta
                haschildren: false
            - item:
                name: Ordenación
                haschildren: false
            - item:
                name: Facetas
                haschildren: false
            - item:
                name: Tipos de búsqueda
                haschildren: false
            - item:
                name: Resaltado
                haschildren: false
            - item:
                name: Enrutado y otros componentes de búsqueda
                haschildren: false
    - item:
        name: Búsquedas avanzadas y Mapeos
        haschildren: true
        subitems:
            - item:
                name: Documentos anidados
                haschildren: false
            - item:
                name: Relaciones padre / hijo
                haschildren: false
            - item:
                name: Geo-localización
                haschildren: false
            - item:
                name: Percolación
                haschildren: false
            - item:
                name: Relevancia
                haschildren: false
    - item:
        name: Modelo distribuido avanzado
        haschildren: true
        subitems:
            - item:
                name: Swift y Objective C
                haschildren: false
            - item:
                name: Aplicaciones con Swift
                haschildren: false
    - item:
        name: Distribución de aplicaciones
        haschildren: true
        subitems:
            - item:
                name: Recuperación del estado del clúster
                haschildren: false
            - item:
                name: Replicación de bajo nivel
                haschildren: false
            - item:
                name: Recuperación de bajo nivel y de fragmentos
                haschildren: false
    - item:
        name: Patrón de diseño Big Data
        haschildren: true
        subitems:
            - item:
                name: Índices múltiples
                haschildren: false
            - item:
                name: Sobreasignación
                haschildren: false
            - item:
                name: Enrutamiento y alias
                haschildren: false
            - item:
                name: Forma de abordar la arquitectura de datos
                haschildren: false
    - item:
        name: Preparación para la Producción
        haschildren: true
        subitems:
            - item:
                name: Ajuste del rendimiento
                haschildren: false
            - item:
                name: Flujo de datos
                haschildren: false
            - item:
                name: Asignación de memoria
                haschildren: false
    - item:
        name: Ejecución en producción
        haschildren: true
        subitems:
            - item:
                name: Monitorización
                haschildren: false
            - item:
                name: Alertas
                haschildren: false
            - item:
                name: API de Detalles/Estadísticas
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
      <meta itemprop="headline" content="{{ page.name }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
        <section class="page__content" itemprop="text">
            <p>Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected.</p>
            <p>El curso tiene como objetivo proporcionar una base sólida en la búsqueda y recuperación de información, a partir de los conceptos básicos fundamentales y componentes internos en todo las mejores prácticas, características y desarrollo de aplicaciones de búsqueda distribuida con Elasticsearch. Al final de la capacitación que tendrá una profunda comprensión de cómo funciona Elasticsearch, el alumno será capaz de analizar de forma fiable, comprender y resolver problemas comunes y estará listo para construir aplicaciones de búsqueda.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>