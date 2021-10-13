# Welcome to our public research page

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.permalink }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

This site is still largely under construction, but please have a look around and if you see anything interesting, do contact us (hmmm...if you can figure out how to do so, not sure that feature is working yet).