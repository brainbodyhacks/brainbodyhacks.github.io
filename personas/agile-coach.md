# Agile Coach

Agile Coach Florian
Alter: 30 Jahre
Beruf: Agile Coach: Begleitet agile Transformationen
Familienstand: verheiratet, 2 Kinder

## Scenarios

### Scenario 1
Florian berät ein großes Unternehmen und erkennt folgende Muster:
- Muster 1
- Muster 2

Ziel: Muster benennen und brechen

Welche Hacks kann Florian nutzen?

{% for post in site.posts %}
  {% if post.tags contains "brainhack" %}
    {{ post.content }}
  {% else %}
    {{ post.title }}
  {% endif %}
{% endfor %}


### Scenario 2

### Scenario 3