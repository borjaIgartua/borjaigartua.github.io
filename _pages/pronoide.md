---
layout: splash
title: Pronoide
permalink: /pronoide/

feature_row:
    - excerpt: "After five years as an iOS developer, I discovered that there were other paths to explore. By becoming a Trainer I wanted to learn all about what I didn't know. I was a Trainer for around **two years** and I can say that it was one of the most gratefull jobs I have ever done."
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
    excerpt: 'My first courses as a Trainer were the ones in which I was more experienced. I taught **359 hours** of iOS and Android courses of a lot of different levels from the most basic to the most advanced ones.'
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
    excerpt: 'Two courses to understand what is behind big data, demystify and master it. In both of them we tried to implement a real environment to learn how it works through the development. I gave **56 hours** of this kind of courses.'
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
    excerpt: '**108 hours** where I instructed more than how to write tests. From a BDD course to more specific topics like Selenium or SoapUI. As in all the courses I tried to build a real world enviroment and then test it. On the BDD course we followed the methodology from the conception of the idea to the test implementation.'
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
    excerpt: 'All related web development. Three courses with a total of **146 hours**. Basic HTML and CSS, new frameworks on HTML5, Angular, NodeJS.'
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
    excerpt: 'Different courses that I had to teach for different reasons. C++, Java and Matlab with a total of **86 hours**'
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