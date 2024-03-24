<style;>

.product-grid-options-size {
list-style: none;
padding: 0px;
font-size: 10px;
opacity: 1;
margin: 0 auto;
text-align: center;
}

.product-grid-options-size .altli a:hover {
background: #000;
border: 1px solid #000;
color: #fff;
}
.product-grid-options-size .altli a {
text-decoration: none;
display: flex;
display: -ms-flexbox;
display: -webkit-flex;
align-items: center;
-ms-flex-align: center;
-webkit-align-items: center;
justify-content: center;
-webkit-justify-content: center;
-ms-justify-content: center;
padding: 0;
min-width: 30px;
min-height: 30px;
-webkit-border-radius: 50%;
-moz-border-radius: 50%;
border-radius: 50%;
background: #fff;
border: 1px solid #989898;
-webkit-transition: none;
-moz-transition: none;
-o-transition: none;
transition: none;
font-weight: 700;
}

.product-grid-options-size .altli {
display: inline-block;
margin: 0 1px 5px 1px;
line-height: normal;
}
.product-grid-options-size .altli a:hover {
background: #000;
border: 1px solid #000;
color: #fff;
}

</style>

{% assign variantCount = product.variants | size %}
{% if product.available and variantCount > 0 %}
<div class="product-grid-options-size">
{% for option in product.options %}
{% assign is_size = false %}
{% assign downcased_option = option | downcase %}

{% if downcased_option contains 'size' %}
{% assign option_index = forloop.index0 %}
{% assign option_count = 0 %}
{% assign values = '' %}

{% for variant in product.variants %}
{% assign value = variant.options[option_index] %}
{% unless values contains value %}

{% if option_count > 0 %}
{% assign values = values | join: '|' | append: '|' %}
{% endif %}
{% assign values = values | append: value %}
{% assign values = values | split: '|' | sort %}
{% assign option_count = values | size %}

{% if variant.available %}
{% if option_count <= 6 %}
<div class="altli {% unless variant.available %}soldout{% endunless %}">
<a title="{{value}}" href="{{ product.url}}?variant={{ variant.id }}">
{{ value }}
</a>
{% assign option_count = option_count | plus : 1 %}
</div>
{% endif %}
{% endif %}

{% endunless %}
{% endfor %}

{% if values.size >= 6 %}
<div class="altli">
<a title="More" href="{{ product.url}}">...</a>
</div>
{% endif %}

{% endif %}


{% endfor %}
</div>
{% endif %}