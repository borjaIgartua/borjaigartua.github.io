---
layout: default
title: BBVA Compass
position: Developer
date: 2012-09-01
header:
  teaser: /assets/images/bbva-compass-logo.jpg
gallery:
  - image_path: /assets/screens/windows-phone/BMUS/dashboard.png
  - image_path: /assets/screens/windows-phone/BMUS/Accounts.png
  - image_path: /assets/screens/windows-phone/BMUS/billPayment.png
  - image_path: /assets/screens/windows-phone/BMUS/location.png
  - image_path: /assets/screens/windows-phone/BMUS/selectLanguage.png
  - image_path: /assets/screens/windows-phone/BMUS/TransactionDetail.png
  - image_path: /assets/screens/windows-phone/BMUS/transfers.png
---

<div id="main" role="main">    
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap" style="margin: 30px;">
      <div class="project-container left">
        <section class="page__content" itemprop="text">
             {% include gallery layout="half" class="remove_margin_top" %}
         </section>
      </div>
      <div class="project-container right">        
        <section class="page__content" itemprop="text">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
        </header>
            <p>The new BBVA Compass Mobile Banking 2.1 app is now fully bilingual (English/Spanish) and provides you a fast, easy and attractive way to manage your BBVA Compass accounts, allowing you to issue and view Bill Payments, Add Payees and manage Pay Accounts; display your balances and charts, view posted and pending transactions, transfer funds between accounts, see images of your paid checks, transaction receipts and find local branches.</p>
            <p>Application develop in Visual Studio for Window phone. I had been working developing the whole application.</p>
        </section>         
        <section class="page__content" itemprop="text" style="font-size: 0.8rem;">
              <blockquote>
                <p>BBVA Compass is a long-needed app that doesn’t disappoint. Its good, clean Windows Phone App-style UI matches the bank website’s blue and white color scheme perfectly. The app does everything you could want it to do, and so much more efficiently than going through the website on a phone. If you have the misfortune of banking with BBVA Compass (can you tell I love them?), don’t hesitate to grab the app today.</p>
              </blockquote>
              <blockquote>
                <p><cite>From Window Central, Paul Acevedo</cite></p>
              </blockquote>
         </section>
         <section class="page__content" itemprop="text">
         {% include carrousel.html %}
         </section>
         </div>
       </div>       
</div>