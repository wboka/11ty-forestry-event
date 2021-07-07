---
layout: layouts/default.njk
title: 1st Annual Tech Fest
---

# 1st Annual Tech Fest

{%- for sponsor in sponsors -%}
	<h2>{{ sponsor.name }}</h2><a href="{{ sponsor.website }}" target="_blank" rel="noopener">Visit {{ sponsor.name }} on the web!</a>
{%- endfor -%}
