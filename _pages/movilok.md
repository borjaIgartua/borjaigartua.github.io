---
title: Movilok
layout: splash
permalink: /movilok/

feature_row:
    - excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
windows_phone:
  - images:
    - item:
        image_path: /assets/images/bbva-next-logo.jpg
        url: /movilok/windows-phone/bbva-next
        class: multiple_row_image
    - item:
        image_path: /assets/images/bbva-compass-logo.jpg
        url: /movilok/windows-phone/bbva-compass
        class: multiple_row_image bottom
    title: Windows Phone
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-small
    url: "/movilok/windows-phone"
    btn_label: "Read More"
    btn_class: "btn--primary"
ios_multiple_row:
  - images:
    - item:
        image_path: /assets/images/twitter-logo.jpg
        url: /movilok/ios/tweetmeter
        class: multiple_row_image
    - item:
        image_path: /assets/images/bbva-next-logo.jpg
        url: /movilok/ios/bbva-next
        class: multiple_row_image
    - item:
        image_path: /assets/images/bbva-compass-logo.jpg
        url: /movilok/ios/bbva-compass
        class: multiple_row_image
    - item:
        image_path: /assets/images/bbva-netcash-logo.jpg
        url: /movilok/ios/bbva-netcash
        class: multiple_row_image
    title: iOS
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
    url: "/movilok/ios"
    btn_label: "Read More"
    btn_class: "btn--primary"
link_multiple_row:
  - images:
    - item:
        image_path: /assets/images/bbva-link-logo.jpg
        url: /movilok/ios/bbva-link
        class: multiple_row_image
    title: BBVA Link
    excerpt: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi neque purus, volutpat ut purus nec, ultrices venenatis erat. Maecenas fermentum scelerisque justo, ullamcorper tristique tortor tristique ut.'
    size: teaser-medium
    url: "/movilok/ios/bbva-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
<div style="margin-top:30px;">
{% include feature_row type="center" %}
{% include feature_multiple_row id="windows_phone" type="left" rows="2" %}
{% include feature_multiple_row id="ios_multiple_row" type="right" rows="2" style="margin-top: 5px;" %}
{% include feature_multiple_row id="link_multiple_row" type="left" rows="1" style="margin-top: 5px;" %}
</div>