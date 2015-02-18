---
layout: default
page-class: page-top

coffees:
- when: Saturday, Jan 24th 2015, 10-11:30a 
  where: Seattle, Greenwood Chocolati
  rsvp: https://www.eventbrite.com/e/montessori-coffee-conversations-tickets-14838395039
- when: Saturday, Feb 21st 2015, 10-11:30am
  where: Portland, Coava Coffee, 1300 SE Grand Ave
- rsvp: https://www.eventbrite.com/e/montessori-coffee-conversations-tickets-15807045298
- when: Saturday, Feb 28th 2015, 10-11:30am
  where: Lighthouse Montessori, Ballard, Seattle
- rsvp: https://www.eventbrite.com/e/montessori-coffee-conversations-seattle-february-tickets-15807073382
- when: Saturday, March 28th 2015, 10-11:30a
  where: Tacoma, Community Montessori, 10-11:30sm
- rsvp: https://www.eventbrite.com/e/montessori-coffee-conversations-seattle-march-tickets-15807105478
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
