---
layout: default
title: "Destinos en Europa"
permalink: /destinos/
---

{% for destino in site.data.destinos %}
## {{ destino.titulo }}
**Fecha:** {{ destino.fecha }}  
**Categorías:** {{ destino.categoria | join: ", " }}
{{ destino.descripcion }}

---

{% endfor %}
