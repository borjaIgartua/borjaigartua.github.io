---
layout: splash
title: Pronoide
permalink: /pronoide/

feature_row:
  - image_path: /assets/images/revival-logo.jpg
    title: "Pronoide"
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    image_size: medium
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
        class: multiple_row_image
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
---

<div style="margin-top:30px;">
  {% include feature_row type="left" %}
  {% include feature_multiple_row id="mobile_row" type="right" rows="2" %}
  {% include feature_multiple_row id="big_data_row" type="left" rows="2" %}
</div>