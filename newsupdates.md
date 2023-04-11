---
layout: newdefault
---

## News and Updates

_Here you can eventually find our latest news, as well as upcoming events_

**Do this in a style where maybe you can like "add" the blog posts? See one of the minima thingies**

Find a trial for a news post here:

[Link title]({{ site.baseurl }}{% link pages/2023-04-01-secondnews.md %})
[Link title]({% link pages/2023-04-01-secondnews.md %})
[This Post]({% link _posts/2023-04-02-this-post.md %})
[Link titleeeeeee]({{ site.baseurl }}{% post_url 2023-04-02-this-post %})



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



<ul class="post-list">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      {%- for post in posts -%}
      <li>
        <span class="post-meta">{{ post.date | date: date_format }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
 </ul>
