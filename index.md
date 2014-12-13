---
layout: default
page-class: page-top

coffees:
- when: Jan 2015
  where: Seattle, Greenwood Chocolati, ...
  rsvp: https://www.eventbrite.com/e/montessori-coffee-conversations-tickets-14838395039
- when: Feb 2015
  where: Portland, TBA
- when: March 2015
  where: Seattle, TBA
- when: April 2015
  where: Seattle,  TBA
- when: April 2015
  where: Portland, TBA

sponsors:
- url: http://lighthousemontessori.com/
  img: lighthousemontessori.png
- url: http://transparentclassroom.com/
  img: transparentclassroom.png
---
{% include header.html %}

{::options parse_block_html="true" /}

<div class="sponsor-strip">
{% include sponsor_strip.html %}
</div>

<div class="section" id="about">
<div class="container">
{% include about.md %}
</div>
</div>

<div class="section" id="conference">
<div class="container ">
{% include conference.md %}
</div>
</div>

<div class="section" id="coffee">
<div class="container">
{% include coffee.md %}
</div>
</div>

<div class="section" id="online">
<div class="container ">
{% include online.md %}
</div>
</div>
