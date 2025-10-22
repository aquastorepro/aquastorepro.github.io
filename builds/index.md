<div class="viewlets">
  {% for bld in site.builds %}
    <div class="product">
      <div class="product_image"><a href="{{ bld.url }}"><img src="/assets/img/{{bld.image}}" /></a></div>
      <div class="product_status"><span>{{ bld.title }}</span></div>
    </div>
  {% endfor %}
</div>
