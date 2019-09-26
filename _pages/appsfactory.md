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
        class: multiple_row_image
    - item:
        image_path: /assets/images/suedkurier-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/home-automation-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/mercedes-me-logo.jpg
        class: multiple_row_image
    title: First Projects
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
truetzschler_row:
  - images:
    - item:
        image_path: /assets/images/bbva-link-logo.jpg
        class: multiple_row_image
    title: Trützschler
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut. (trü ios)'
    size: teaser-medium
beurer_row:
  - images:
    - item:
        image_path: /assets/images/irl-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/suedkurier-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/home-automation-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/mercedes-me-logo.jpg
        class: multiple_row_image
    title: Beurer
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut. (beurer ios)'
    size: teaser-medium
backend_row:
  - images:
    - item:
        image_path: /assets/images/irl-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/suedkurier-logo.jpg
        class: multiple_row_image bottom
    title: Backend
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
---

<div style="margin-top:30px;">
  {% include feature_row type="center" %}
  {% include feature_multiple_row id="ios_row" type="left" rows="2" %}
  {% include feature_multiple_row id="truetzschler_row" type="right" rows="1" %}
  {% include feature_multiple_row id="beurer_row" type="left" rows="2" %}
  {% include feature_multiple_row id="backend_row" type="right" rows="2" %}
</div>