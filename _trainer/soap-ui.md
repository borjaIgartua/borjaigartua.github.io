---
layout: default
name: 'Soap UI'
position: Trainer
company: Accenture
duration: 16 horas
date: 2016-11-07
header:
  teaser: /assets/images/soapui-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/soapui-logo.jpg
    text: "Trainer"
  - title: "Nivel"
    text: Avanzado
  - title: "Dirigido a"
    text: 'Esta acción formativa está destinada a desarrolladores de servicios web, departamento de calidad de aplicaciones o gestores de entornos de sistemas.'
accordion:
    - item:
        name: Conceptos previos
        haschildren: true
        subitems:
            - item:
                name: Repaso rápido del lenguaje XML
                haschildren: false
            - item:
                name: Servicios Web
                haschildren: false
            - item:
                name: Web Service Description Language
                haschildren: false
            - item:
                name: Versiones de SoapUI
                haschildren: false
    - item:
        name: Empezando a trabajar con SoapUI
        haschildren: true
        subitems:
            - item:
                name: Interfaz de SoapUI
                haschildren: false
            - item:
                name: Creación de proyectos
                haschildren: false
            - item:
                name: WSDL
                haschildren: false
            - item:
                name: Auto generación de código con Apache CXF
                haschildren: false
            - item:
                name: Operaciones y Peticiones
                haschildren: true
                subitems:
                    - item:
                        name: Simulación de peticiones a servicios web (Mocks)
                        haschildren: false
                    - item:
                        name: Conceptos básicos para el manejo de mensajes
                        haschildren: true
                        subitems:
                            - item:
                                name: XPath
                                haschildren: false
                            - item:
                                name: XQuery
                                haschildren: false
                    - item:
                        name: Simulación de servicios con scripts en Groovy
                        haschildren: false
    - item:
        name: Creación de planes de pruebas (Test Suites)
        haschildren: true
    - item:
        name: Creación/edición de casos de prueba (Test Cases) y pasos de prueba (Test Steps)
        haschildren: true
    - item:
        name: Propiedades de un “test case”
        haschildren: true
    - item:
        name: Tipos de aserciones
        haschildren: true
        subitems:
            - item:
                name: Aserciones basadas en expresiones XPath
                haschildren: false
            - item:
                name: Aserciones basadas en expresiones XQuery
                haschildren: false
            - item:
                name: De tiempo de respuesta (SLA)
                haschildren: false
            - item:
                name: De conformidad con el esquema XSD
                haschildren: false
            - item:
                name: De códigos de respuesta/error http
                haschildren: false
            - item:
                name: De respuesta válida SOAP / error SOAP
                haschildren: false
            - item:
                name: De presencia/ausencia de cadenas en el contenido
                haschildren: false
    - item:
        name: Ejecución y depuración de planes de prueba
        haschildren: true
        subitems:
            - item:
                name: 'Ejecución simple de planes de prueba: comprobación de aserciones'
                haschildren: false
            - item:
                name: Ejecución de planes de pruebas en modo depuración
                haschildren: false
            - item:
                name: Modularizaciones de los planes de prueba
                haschildren: false
            - item:
                name: Configuración y uso de diferentes entornos de ejecución
                haschildren: false
            - item:
                name: Creación y obtención de informes de ejecución
                haschildren: false
            - item:
                name: Test on Demand
                haschildren: false
            - item:
                name: Trazas y mensajes de rastreo
                haschildren: false
            - item:
                name: Scripting
                haschildren: false
    - item:
        name: Configuración de preferencias
        haschildren: true
        subitems:
            - item:
                name: Preferencias de la conexión HTTP y Proxy
                haschildren: false
            - item:
                name: Preferencias SSL y WSDL
                haschildren: false
            - item:
                name: Preferencias de la interfaz gráfica
                haschildren: false
            - item:
                name: Preferencias de editor y de herramientas externas
                haschildren: false
            - item:
                name: Preferencias globales
                haschildren: false
    - item:
        name: Tipos de pasos de pruebas
        haschildren: true
        subitems:
            - item:
                name: Peticiones (de muestreo)
                haschildren: false
            - item:
                name: Transferencias de propiedades entre peticiones
                haschildren: false
            - item:
                name: “Goto” condicional
                haschildren: false
            - item:
                name: Pasos de propiedad. Carga y guardado de propiedades desde/hacia fuentes o ficheros externos
                haschildren: false
            - item:
                name: Pasos de retardo
                haschildren: false
    - item:
        name: Pruebas de carga y rendimiento
        haschildren: true
        subitems:
            - item:
                name: Tipos de pruebas de carga
                haschildren: true
                subitems:
                    - item:
                        name: De carga
                        haschildren: false
                    - item:
                        name: De estrés
                        haschildren: false
                    - item:
                        name: De desbordamiento de memoria
                        haschildren: false
                    - item:
                        name: De escalabilidad
                        haschildren: false
            - item:
                name: Estrategias de pruebas de carga y rendimiento
                haschildren: false
            - item:
                name: Aserciones en las pruebas de carga
                haschildren: false
            - item:
                name: Obtención de métricas/gráficas e interpretación de resultados
                haschildren: false
    - item:
        name: Pruebas de seguridad de los servicios
        haschildren: true
        subitems:
            - item:
                name: Inyección SQL
                haschildren: false
            - item:
                name: Inyección xPath
                haschildren: false
            - item:
                name: Inyección mediante scripts
                haschildren: false
            - item:
                name: Fuzzing Scan
                haschildren: false
            - item:
                name: Envio de xml mal formado
                haschildren: false
    - item:
        name: Automatización de la ejecución de planes de pruebas
        haschildren: true
        subitems:
            - item:
                name: Integración y ejecución de planes de prueba desde JUnit
                haschildren: false
            - item:
                name: Integración y ejecución de planes de prueba desde Maven
                haschildren: false
            - item:
                name: Integración con otras herramientas de automatización (Jenkins, …)
                haschildren: false
    - item:
        name: Pruebas orientadas a datos (Data-Driven Test)
        haschildren: true
        subitems:
            - item:
                name: JDBC
                haschildren: false
            - item:
                name: Ficheros planos/CSV, ficheros Excel, o en tablas de bases de datos
                haschildren: false
    - item:
        name: Casos de prueba particulares
        haschildren: true
        subitems:
            - item:
                name: Generación de un proyecto dado un WSDL
                haschildren: false
            - item:
                name: Inyección SQL a un servicio propio y posterior securización del mismo
                haschildren: false
            - item:
                name: Inyección XPath a un servicio propio y posterior securización del mismo
                haschildren: false
            - item:
                name: Data Driven Development. Proyecto de realización de un plan de pruebas completo a una base de datos real
                haschildren: false
            - item:
                name: Validaciones con autenticación HTTP REST
                haschildren: false
            - item:
                name: Validaciones con Autenticación HTTP REST con formularios
                haschildren: false
            - item:
                name: Validaciones con OAuth 2
                haschildren: false
            - item:
                name: Generación automática de token de sesión en OAuth 2
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
            <p>SoapUI is a tool for testing Web Services; these can be the SOAP Web Services as well RESTful Web Services or HTTP based services. SoapUI is an Open Source and completely free tool with a commercial companion -SoapUI Pro- that has extra functionality for companies with mission critical Web Services.</p>
            <p>SoapUI has been downloaded more than 3 million times and is seen as the de facto standard for API Service Testing. </p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>