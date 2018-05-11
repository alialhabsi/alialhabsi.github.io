---
layout: defaults/page
permalink: index.html
narrow: true
---

{% include components/intro.md %}

[More about my skills.]({{ site.baseurl}}{% link _pages/about.md %})

### What else?

Due to the ongoing war in my native country Yemen, I have only been working as a freelancing pentester where I performed a complete cycle of pentesting using manual and automated techniques. Currently, I'm in Malaysia for the purpose of finding my next big challenge in security. If you are looking for someone with diverse skills in redteaming and programming, please drop me a message.

I spend most of my time now, reading technical books, participating in CTFs and following the new trends in cyber security.
I'll be using this space to do technical write-ups, tutorials and also talking football. Stay tuned. :)


<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner" role="listbox" style=" width:100%; height: 420px !important;">
    <div class="carousel-item active">
      <img class="d-block img-fluid" src="theme/img/ny.jpg" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" src="theme/img/sec.jpg" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" src="theme/img/ball.jpg" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>



### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


