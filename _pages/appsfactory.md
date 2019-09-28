---
layout: splash
title: Appsfactory
permalink: /appsfactory/

feature_row:
    - excerpt: 'Back to the roots. I moved to Germany and went back iOS development. I wanted to put in practice my expertise gained as trainer, also I missed being part of a team and develop products that the people can use. I am working here **since 2018**'
ios_row:
  - images:
    - item:
        image_path: /assets/images/irl-logo.jpg
        url: /appsfactory/first-projects/invest-region-leipzig
        class: multiple_row_image
    - item:
        image_path: /assets/images/suedkurier-logo.jpg
        url: /appsfactory/first-projects/suedkurier
        class: multiple_row_image
    - item:
        image_path: /assets/images/home-automation-logo.jpg
        url: /appsfactory/first-projects/home-automation
        class: multiple_row_image
    - item:
        image_path: /assets/images/mercedes-me-logo.jpg
        url: /appsfactory/first-projects/mercedes-me
        class: multiple_row_image
    title: First Projects
    excerpt: 'Almost one year of iOS development. I did alone some projects, had the opportunity to work on Silicon Valley and I worked with a huge international team.'
    size: teaser-medium
    url: "/appsfactory/first-projects"
    btn_label: "Read More"
    btn_class: "btn--primary"
truetzschler_row:
  - images:
    - item:
        image_path: /assets/images/truetzchlermw_logo.jpg
        url: /appsfactory/mywires
        class: multiple_row_image
    title: Trützschler
    excerpt: 'This was my bigest project in Germany. I lead the iOS development of this project working together with a team of 10 people. We worked around 4 months to finish it'
    size: teaser-medium
    url: "/appsfactory/mywires"
    btn_label: "Read More"
    btn_class: "btn--primary"
beurer_row:
  - images:
    - item:
        image_path: /assets/images/freshhome.jpg
        url: /appsfactory/beurer/freshhome
        class: multiple_row_image
    - item:
        image_path: /assets/images/cosynight.jpg
        url: /appsfactory/beurer/cosynight
        class: multiple_row_image bottom
    title: Beurer
    excerpt: 'Due to company needs I had to take care of two iOS projects and fix some mayor problems that they had. I did some small features too.'
    size: teaser-small
    url: "/appsfactory/beurer"
    btn_label: "Read More"
    btn_class: "btn--primary"
backend_row:
  - images:
    - item:
        image_path: /assets/images/truetzchlermp_logo.jpg
        url: /appsfactory/backend/myproduction
        class: multiple_row_image
    - item:
        image_path: /assets/images/beurer-logo.jpg
        url: /appsfactory/backend/beurersso
        class: multiple_row_image bottom
    title: Backend
    excerpt: 'After settle down in Germany I wanted new challenges and I requested to become part of the fullstack team. As everything has a beginning I started refactoring a quite old project and taking care of small features and bugs.'
    size: teaser-small
    url: "/appsfactory/backend"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

<div style="margin-top:30px;">
  {% include feature_row type="center" %}
  {% include feature_multiple_row id="ios_row" type="left" rows="2" %}
  {% include feature_multiple_row id="truetzschler_row" type="right" rows="1" %}
  {% include feature_multiple_row id="beurer_row" type="left" rows="2" %}
  {% include feature_multiple_row id="backend_row" type="right" rows="2" %}
</div>