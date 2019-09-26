---
layout: splash
title: Trützchler
permalink: /appsfactory/mywires
position: Developer
date: 2015-03-01
header:
  teaser: /assets/images/revival-logo.jpg
feature_row:
  - image_path: /assets/images/revival-logo.jpg
    title: "Trützchler - My Wires"
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    image_size: medium
gallery:
  - image_path: /assets/screens/iOS/truetzschler/mywires/01.jpg
  - image_path: /assets/screens/iOS/truetzschler/mywires/02.jpg
  - image_path: /assets/screens/iOS/truetzschler/mywires/03.jpg
  - image_path: /assets/screens/iOS/truetzschler/mywires/04.jpg
  - image_path: /assets/screens/iOS/truetzschler/mywires/06.jpg
  - image_path: /assets/screens/iOS/truetzschler/mywires/07.jpg
---

<div style="margin-top:30px;">
  {% include feature_row type="left" %}
  <div class="project-container left">
    <section class="page__content" itemprop="text">
      {% include gallery layout="half" class="remove_margin_top" %}
    </section>
  </div>
  <div class="project-container right">        
    <section class="page__content" itemprop="text">
      <p>{{ site.data.ui-text[site.locale].my_wires_desc_1 }}</p>
      <p>{{ site.data.ui-text[site.locale].my_wires_desc_2 }}</p>
      <p>{{ site.data.ui-text[site.locale].my_wires_desc_3 }}</p>
    </section>         
  </div>
</div>
