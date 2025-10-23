<div class="viewlets">
  {% for lf in site.live-food %}
    <div class="product">
      <div class="product_image"><a href="{{ lf.url }}"><img src="/assets/img/{{lf.image}}" /></a></div>
      <div class="product_status"><span>{{ lf.title }}</span></div>
    </div>
  {% endfor %}
</div>
