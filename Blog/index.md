All blog posts are stored here:

<ul>
  {% for post in site.categories.blog %}
    <li>
      <a href="https://jojomoore2007.github.io/thecodersite{{ post.url }}">{{ post.title }} - {{ post.date }}</a>
    </li>
  {% endfor %}
</ul>
