---
layout: default
name: 'Desarrollo Aplicaciones móviles III Edición'
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
    text: "Profesor desarrollo de aplicaciones para dispositivos iOS y del Proyecto iOS & Android"
accordion:  
  - item:
      name: Introducción
      haschildren: true
      subitems:
        - item:
            name: ¿Qué cubre el curso?
            haschildren: false
        - item:
            name: Cómo empezó Apple
            haschildren: false
        - item:
            name: Herramientas necesarias
            haschildren: false
  - item:
      name: Objective C
      haschildren: true
      subitems:
        - item:
            name: Descripción del entorno
            haschildren: false
        - item:
            name: Clases
            haschildren: false
        - item:
            name: Punteros
            haschildren: false
        - item:
            name: Propiedades
            haschildren: false
        - item:
            name: NSString y NSNumber
            haschildren: false
        - item:
            name: Colecciones
            haschildren: false
        - item:
            name: Herencia
            haschildren: false
  - item:
      name: iOS
      haschildren: true
      subitems:
        - item:
            name: Entorno de desarrollo
            haschildren: false
        - item:
            name: Controladores y Vistas
            haschildren: false
        - item:
            name: Componentes visuales
            haschildren: false
        - item:
            name: Comunicación vista controlador
            haschildren: false
        - item:
            name: Constraints
            haschildren: false
        - item:
            name: Navegaciones entre vistas
            haschildren: false
  - item:
      name: Persistencia
      haschildren: true
      subitems:
        - item:
            name: Ficheros Plist
            haschildren: false
        - item:
            name: SQLite
            haschildren: false
  - item:
      name: Componentes avanzados
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
      name: Servicios remotos
      haschildren: true
      subitems:
        - item:
            name: Introducción
            haschildren: false
        - item:
            name: Servicios REST
            haschildren: false
  - item:
      name: Swift
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
            name: Registro
            haschildren: false
        - item:
            name: iTunes Connect
            haschildren: false
        - item:
            name: Distribución
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
          <p>Dado que las apps móviles siguen experimentando un boom a nivel mundial y que España es uno de los países europeos con mayor utilización de aplicaciones móviles, este curso de Fundación Telefónica se perfila como opción para formarse y abrirse paso en un sector laboral con múltiples oportunidades para estos profesionales.</p>
          <p>Los participantes aprenderán el sistema operativo Android e iOS, a familiarizarse con el lenguaje JAVA como Objective C, acceder desde las apps a todas las funcionalidades del terminal y publicar las apps en los repositorios de Apple y Google para que puedan ser descargadas.</p>
          <p>El curso comprende un total de 4 meses separados en un bloque de formación troncal sobre arquitectura de aplicaciones, diseño web, desarrollo web con Phone Gap y programación JAVA, un bloque de formación específica sobre desarrollo de apps para Android, iOS, más desarrollo de proyecto, así como un bloque de habilidades para la empleabilidad para mejorar la marca personal, la búsqueda de empleo 2.0 e incrementar las competencias profesionales.</p>
          <br/>
          <p>Profesor de la parte de desarrollo de aplicaciones para iOS. Durante la parte del proyecto los alumnos se dividían en equipos de 5 o 6 personas y junto con una empresa colaboradora desarrollaban una aplicación que luego expondrían en un evento. En esta parte del curso trabajé ayudando y guiando a los equipos para que pudieran terminar sus proyectos tanto de iOS como de Android.</p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>