---
layout: default
name: Mercedes me
position: Developer
date: 2018-10-01
header:
  teaser: /assets/images/mercedes-me-logo.jpg
  description: "ole ole ole que ole que bonito proyecto este"
sidebar:
  - title: "Role"
    image: /assets/images/mercedes-me-logo.jpg
    text: "Designer, Front-End Developer"
  - title: "Responsibilities"
    text: "Reuters try PR stupid commenters should isn't a business model"
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
        <!-- content -->
        </section>
      </div>
    </article>
</div>

