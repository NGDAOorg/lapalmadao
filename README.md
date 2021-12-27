# ngDAO
DAOs sin ánimo de lucro
{% for ngDAO in site.ngdaos %}
  <div class="ngdao">
    <h2><a href="{{ ngDAO.web }}">{{ ngDAO.nombre }}</a></h2>
  </div>
{% endfor %}
