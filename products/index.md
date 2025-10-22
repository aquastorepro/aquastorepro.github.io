<div class="viewlets">
  {% for plt in site.plants %}
    <div class="product">
      <div class="product_image"><a href="{{ plt.url }}"><img src="/assets/img/{{plt.image}}" /></a></div>
      <div class="product_status"><span>{{ plt.title }}</span></div>
    </div>
  {% endfor %}
</div>
