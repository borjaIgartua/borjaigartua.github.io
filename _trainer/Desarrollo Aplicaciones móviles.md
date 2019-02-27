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