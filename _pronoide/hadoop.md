---
layout: default
title: Hadoop
position: Trainer
company: CMC
duration: 16 horas
date: 2016-12-12
header:
  teaser: /assets/images/hadoop-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/hadoop-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: 'Esta acción formativa va dirigida a Programadores, Analistas y Administradores de sistemas.'
accordion:
  - item:
      name: Introducción a Hadoop
      haschildren: true
      subitems:
        - item:
            name: Big Data y Hadoop
            haschildren: false
        - item:
            name: Historia
            haschildren: false
        - item:
            name: Introducción al HDFS, YARN y MapReduce
            haschildren: false
  - item:
      name: Hadoop Distributed File System (HDFS)
      haschildren: true
      subitems:
        - item:
            name: Conceptos HDFS
            haschildren: false
        - item:
            name: Lectura en HDFS
            haschildren: false
        - item:
            name: Escritura en HDFS
            haschildren: false
        - item:
            name: Comandos del HDFS
            haschildren: false
        - item:
            name: Herramientas de HDFS
            haschildren: false
        - item:
            name: API Java de HDFS
            haschildren: false
  - item:
      name: MapReduce
      haschildren: true
      subitems:
        - item:
            name: Preparar el entorno
            haschildren: false
        - item:
            name: Map
            haschildren: false
        - item:
            name: Reduce
            haschildren: false
        - item:
            name: Combiner
            haschildren: false
        - item:
            name: Ejemplo avanzado
            haschildren: false
  - item:
      name: MRUnit
      haschildren: true
      subitems:
        - item:
            name: Instalación
            haschildren: false
        - item:
            name: Casos de uso
            haschildren: false
  - item:
      name: HIVE
      haschildren: true
      subitems:
        - item:
            name: Introducción
            haschildren: false
        - item:
            name: Consola Hive
            haschildren: false
        - item:
            name: HiveQL
            haschildren: false
  - item:
      name: Spark
      haschildren: true
      subitems:
        - item:
            name: Introducción
            haschildren: false
        - item:
            name: Resilient Distributed Datasets (RDD)
            haschildren: false
        - item:
            name: Spark Shell
            haschildren: false
        - item:
            name: Transformaciones sobre RDDs
            haschildren: false
        - item:
            name: Acciones sobre RDDs
            haschildren: false
        - item:
            name: API Java de Spark
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
            <p>The Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing.</p>
            <p>The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.</p>
          <!-- <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %} -->
        </section>
      </div>
    </article>
</div>