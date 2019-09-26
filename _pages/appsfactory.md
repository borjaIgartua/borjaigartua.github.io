---
layout: splash
title: Appsfactory
permalink: /appsfactory/

feature_row:
    - excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
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
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
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
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut. (trü ios)'
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
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut. (beurer ios)'
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
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
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