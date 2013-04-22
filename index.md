---
layout:   page
title:    /var/log/obfusk
tagline:  "hacking &rArr; &not;sleeping"
---
{% include JB/setup %}

/var/log/obfusk is where I write about the things I'm working on and
playing with: (functional) programming; bash, clojure, haskell, ruby;
coffeescript, css, html; debian, ubuntu; gnu, linux; vim; free
software; ...

Most of my code is on GitHub:
[obfusk](https://github.com/obfusk) (private),
[noxqsgit](https://github.com/noxqsgit) (work).

\- Felix

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo;
      <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
