---
layout: splash
title: Pronoide
permalink: /pronoide/

feature_row:
    - excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
mobile_row:
  - images:
    - item:
        image_path: /assets/images/apple-logo.jpg
        url: /pronoide/mobile/ios-development
        class: multiple_row_image
    - item:
        image_path: /assets/images/android-logo.jpg
        url: /pronoide/mobile/android
        class: multiple_row_image bottom
    title: Mobile
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
    url: "/pronoide/mobile"
    btn_label: "Read More"
    btn_class: "btn--primary"
big_data_row:
  - images:
    - item:
        image_path: /assets/images/elasticsearch-logo.jpg
        url: /pronoide/big-data/elasticsearch
        class: multiple_row_image
    - item:
        image_path: /assets/images/hadoop-logo.jpg
        url: /pronoide/big-data/hadoop
        class: multiple_row_image bottom
    title: Big Data
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
    url: "/pronoide/big-data"
    btn_label: "Read More"
    btn_class: "btn--primary"
testing_row:
  - images:
    - item:
        image_path: /assets/images/spock-geb-logo.jpg
        url: /pronoide/testing/groovy-spock-geb
        class: multiple_row_image
    - item:
        image_path: /assets/images/bdd-logo.jpg
        url: /pronoide/testing/bdd
        class: multiple_row_image
    - item:
        image_path: /assets/images/selenium-logo.jpg
        url: /pronoide/testing/selenium
        class: multiple_row_image
    - item:
        image_path: /assets/images/soapui-logo.jpg
        url: /pronoide/testing/soap-ui
        class: multiple_row_image
    title: Testing
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
    url: "/pronoide/testing"
    btn_label: "Read More"
    btn_class: "btn--primary"
html_row:
  - images:
    - item:
        image_path: /assets/images/html-css-logo.jpg
        url: /pronoide/front-end/html5-css3
        class: multiple_row_image
    - item:
        image_path: /assets/images/html-frameworks.jpg
        url: /pronoide/front-end/html5-frameworks
        class: multiple_row_image bottom
    title: Front end
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
    url: "/pronoide/front-end"
    btn_label: "Read More"
    btn_class: "btn--primary"
others_row:
  - images:
    - item:
        image_path: /assets/images/c-logo.jpg
        url: /pronoide/more/c 
        class: multiple_row_image
    - item:
        image_path: /assets/images/java-logo.jpg
        url: /pronoide/more/java-development
        class: multiple_row_image bottom
    title: More curses
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
    url: "/pronoide/more"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

<div style="margin-top:30px;">
  {% include feature_row type="center" %}
  {% include feature_multiple_row id="mobile_row" type="left" rows="2" %}
  {% include feature_multiple_row id="big_data_row" type="right" rows="2" %}
  {% include feature_multiple_row id="testing_row" type="left" rows="2" %}
  {% include feature_multiple_row id="html_row" type="right" rows="2" %}
  {% include feature_multiple_row id="others_row" type="left" rows="2" %}
</div>