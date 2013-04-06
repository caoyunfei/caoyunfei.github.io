layout: page
{% for post in site.categories.blog %}
{{ post.title }}
{{ post.description }}
{% endfor %}
{% for post in site.categories.opinion%}
{{ post.title }}
{{ post.description }}
{% endfor %}
$(function(){ var height = $('.index-artical').height(); $('.index-mid').height(height-90); });
