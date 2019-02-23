---
layout: default
name: Tweetmeter
position: Developer
date: 2012-10-01
header:
  teaser: /assets/images/twitter-logo.jpg
gallery:
  - image_path: /assets/screens/iOS/tweetmeter/map.png
  - image_path: /assets/screens/iOS/tweetmeter/mapuno.png
  - image_path: /assets/screens/iOS/tweetmeter/maptwo.png
  - image_path: /assets/screens/iOS/tweetmeter/mapcenter.png
---

<div id="main" role="main">    
      <meta itemprop="headline" content="{{ page.name }}"/>
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
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
            <p>Application that measures the impact of a tweet. Each tweet obtains points depending on the retweets within a range and the followers of the user who wrote the tweet.</p>
            <p>Screens display depending on the tweet position. In the first screens, we can see the tweets put together according to the zoom level of the map. The last screen is to change the localization of searching tweets. Depending on the position of the map, the app will look for tweets nearby.</p>
	          <p>Application develop in xCode for iOS 5 and further versions. I have developed maps, in which I have used the native component: MapKit.</p>
        </section>         
         </div>
       </div>       
</div>