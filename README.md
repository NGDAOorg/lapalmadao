# ngDAO
DAOs sin ánimo de lucro
{% for ngDAO in site.ngdaos %}
  <div class="ngdao">
    <h2>DAO: <a href="{{ ngDAO.web }}">{{ ngDAO.nombre }}</a></h2>
    ##{{ ngDAO.nombre }}
  </div>
{% endfor %}
