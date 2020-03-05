---
layout: default
---
<section>
<h2>The current admins are:</h2>
<ul>
  {% for admin in site.data.admins %}
      {% if admin.website %}
      <li>
        <a href="{{ admin.website }}">{{ admin.name }}</a>
      </li>
      {% elsif admin.twitter %}
      <li>
        <a href="https://twitter.com/{{ admin.twitter }}">{{ admin.name }}</a>
      </li>
      {% endif %}
  {% endfor %}
</ul>
</section>
