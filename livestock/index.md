<div class="viewlets">
  {% for ls in site.livestock %}
    <div class="product">
      <div class="product_image"><a href="{{ ls.url }}"><img src="/assets/img/{{ls.image}}" /></a></div>
      <div class="product_status"><span>{{ ls.title }}</span></div>
    </div>
  {% endfor %}
</div>
