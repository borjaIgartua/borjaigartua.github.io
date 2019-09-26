---
layout: splash
title: Pronoide
permalink: /pronoide/

feature_row:
    - excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
mobile_row:
  - images:
    - item:
        image_path: /assets/images/telefonica-talentum-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/apple-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/android-logo.jpg
        class: multiple_row_image special-left
    title: Mobile
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
big_data_row:
  - images:
    - item:
        image_path: /assets/images/elasticsearch-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/hadoop-logo.jpg
        class: multiple_row_image bottom
    title: Big Data
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
testing_row:
  - images:
    - item:
        image_path: /assets/images/spock-geb-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/bdd-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/selenium-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/soapui-logo.jpg
        class: multiple_row_image
    title: Testing
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
html_row:
  - images:
    - item:
        image_path: /assets/images/html-css-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/html-frameworks.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/telefonica-educacion-digital-logo.jpg
        class: multiple_row_image
    title: Front end
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
others_row:
  - images:
    - item:
        image_path: /assets/images/c-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/spock-geb-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/java-logo.jpg
        class: multiple_row_image
    - item:
        image_path: /assets/images/matlab-logo.jpg
        class: multiple_row_image
    title: More curses
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
---

<div style="margin-top:30px;">
  {% include feature_row type="center" %}
  {% include feature_multiple_row id="mobile_row" type="left" rows="2" %}
  {% include feature_multiple_row id="big_data_row" type="right" rows="2" %}
  {% include feature_multiple_row id="testing_row" type="left" rows="2" %}
  {% include feature_multiple_row id="html_row" type="right" rows="2" %}
  {% include feature_multiple_row id="others_row" type="left" rows="2" %}
</div>