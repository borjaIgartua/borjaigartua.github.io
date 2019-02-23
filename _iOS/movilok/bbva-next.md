---
layout: default
name: BBVA Next
position: Developer
date: 2013-06-01
header:
  teaser: /assets/images/bbva-next-logo.jpg
gallery:
  - image_path: /assets/screens/iOS/next/uno.png
  - image_path: /assets/screens/iOS/next/dos.png
  - image_path: /assets/screens/iOS/next/tres.png
  - image_path: /assets/screens/iOS/next/cuatro.png
---

<div id="main" role="main">    
      <meta itemprop="headline" content="{{ page.name }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap" style="margin: 30px;">
      <div class="project-container left">
        <section class="page__content" itemprop="text">
             {% include gallery layout="half" class="remove_margin_top" %}
         </section>
      </div>
      <div class="project-container right">        
        <section class="page__content" itemprop="text">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
            <p>BBVA Next. Spanish banking application awarded best world wide app according to <a href="https://www.forrester.com/report/Global+Mobile+Banking+Benchmark+2017/-/E-RES137691">Forrester Research</a> 2017 and 2018.</p>
            <p>Whithin this app I have develop voice recognition integration. Pilot project: SDK voice recognition of Nuance<span style="font-size:0.6em;">&copy;</span> integrated for Mobile Banking Spain application. You can control part of the application by voice thanks to the incorporation of Nuance<span style="font-size:0.6em;">&copy;</span> SDK.</p>
            <p>Once the user has logged in, he has access to main screen where he can also activate the button to start the voice commands. The users can access one they have used these commands. transfer screens and stocks display screen.</p>
        </section>         
         </div>
       </div>       
</div>