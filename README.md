# Listado de DAOs sin ánimo de lucro

{% for ngDAO2 in site.ngdaos %}
  <div class="ngdao">
    <h2>DAO: <a href="{{ ngDAO2.web }}">{{ ngDAO2.nombre }}</a></h2>
    ## {{ ngDAO2.nombre }}
  </div>
{% endfor %}

<ul>
  {% for ngdao in site.ngdaos %}
    <li>
      <h2>{{ ngdao.name }}</h2>
      <h3>{{ ngdao.descripcion }}</h3>
      <p>{{ ngdao.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

