---
layout: newdefault
---

## News and Updates

_Here you can eventually find our latest news, as well as current and upcoming events_

Find a trial for a news post here:

{% comment %} **These examples below all work**
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
{% endcomment %}


<ul class="post-list">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      {%- for post in site.posts -%}
      <!---<li>--->
        <span class="post-meta" style="color:gray">{{ post.date | date: date_format }}</span>
        <h5>
          <a class="post-link" style="color_black" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h5>
        <!---{%- if site.show_excerpts -%}--->
         {{ post.excerpt }}
        <!---{%- endif -%}--->
        <p>{{ post.content }}</p>
      {%- endfor -%}
 </ul>
 
 ----
 
 Otherwise, you can write a new "tweet" right in here, like this:
 
 ### New Project
 
 With new funding thanks to whoever we are now starting to take over the world step by step fusion reactor by fusion reactor.
 For further informations go visit someone.
 This is just supposed to be an example text.
