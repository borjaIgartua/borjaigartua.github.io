---
layout: default
title: My tab
position: Developer
date: 2019-09-01
header:
  teaser: /assets/images/truetzchler_logo.jpg
---

<div id="main" role="main">    
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap" style="margin: 30px;">
      <div class="project-container">        
        <section class="page__content" itemprop="text">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
        </header>
            <h3>Internal application to manage all tests made on Trützschler machines</h3>
            <p>Trützschler needed a system to control all the tests made on their lines (group of machines) under certain circustances. My Tab stores all this information and provides it on an usable way.</p>
            <p>My Tab is a .net 3.0 project based on events to provide all the changes made in our data. The data is store on Azure Storage Account using blobs and table storage.</p>
            <p>I've have been working on backend since the beginning for around one year.</p>
        </section>
         </div>
       </div>       
</div>