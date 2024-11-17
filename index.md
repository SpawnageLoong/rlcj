---
layout: default

pagination:
  enabled: true
---

{% for post in paginator.posts %}
  {% include blog.html %}
{% endfor %}

{% if paginator.total_pages > 1 %}
<nav class="pagination" role="navigation">
  <hr/>
    <ul>
      <li class="pagination-item-prev" >
            {% if paginator.previous_page %}
        {% if paginator.page == 2 %}
              <a rel="prev" href="{{ site.baseurl }}/">&laquo; Previous</a>
          {% else %}
          <a rel="prev" href="{{ site.baseurl }}/page/{{paginator.previous_page}}/">&laquo; Previous</a>
          {% endif %}
        {% else %}
        <span>&laquo; Previous</span>
            {% endif %}
      </li>
  
  
      <li class="pagination-item-next" >
            {% if paginator.next_page %}
        <a rel="next" href="{{ site.baseurl }}/{{paginator.next_page}}/">Next &raquo;</a>
        {% else %}
        <span>Next &raquo;</span>
            {% endif %}
      </li>
  
    </ul>
  <hr/>
</nav>
{% endif %}