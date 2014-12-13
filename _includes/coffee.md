Coffee Conversations
--------------------

We want to create a more cohesive Montessori community here in the Northwest. To that end, we'll be holding "coffee conversations" in both Seattle and Portland, leadingn up to our conference.

### Upcoming coffees


<table class="table table-striped">
{% for coffee in page.coffees %}
<tr>
<td>{{ coffee.when }}</td>
<td>{{ coffee.where }}</td>
<td>{% if coffee.rsvp %}<a href="{{ coffee.rsvp }}" class="btn btn-primary">RSVP</a>{% endif %}</td>
</tr>
{% endfor %}
</table>

### How will it work?

We'll be using a discussion format called [Lean Coffee](http://leancoffee.org). It's an easy way to have a structured conversation. We think it will give you an idea of what will be possible in the conference and help us all to get to know each other better.

<ol>
  <li>
    <h4>Write your idea on a post-it</h4>
    Everyone writes Montessori topics + questions on post-its. You might ask "How do you manage transitions?" or "How do you handle conflict in the classroom?".</li>
  <li>
    <h4>Vote for your favorite ideas</h4>
    Quickly, everyone will put a dot on the post-its that they would like to talk about. Ideas then get sorted by how many dots they have.
  </li>
  <li>
    <h4>Learn and share!</h4>
    Talk about what's important. Each idea gets 8 minutes, and then a quick check to see if we should spend more time or move to the next idea.
  </li>
</ol>
