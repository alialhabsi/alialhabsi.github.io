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

{% include components/carousel.html %}


### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


