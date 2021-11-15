{% for person in site.data.people %}
- [@{{person}}](https://github.com/{{person}})
{% endfor %}

### Remote
{% for person in site.data.people-remote %}
- [@{{person}}](https://github.com/{{person}})
{% endfor %}
