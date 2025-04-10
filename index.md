---
layout: home
title: Eilinis Andrius
---

<p align="center">
  <img src="/eilinis-andrius/assets/eilinis-andrius.png" alt="Eilinis Andrius" width="200em" style="border-radius: 8px; margin-bottom: 1.5em;" />
</p>

---

Sveiki atvykę!

Tai mano asmeninis rašinių kampelis. Čia rašysiu apie dirbtinį intelektą, lietuvių kalbą, istoriją, atmintį ir dar šį tą.

Pirmasis įrašas – netrukus.

---

## Naujausi įrašai

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url | absolute_url }})
  {% endfor %}

---

## Licencija

Šiame tinklaraštyje esantys tekstai paskelbti pagal **Creative Commons Zero (CC0)** licenciją.  
[Peržiūrėti licenciją](https://creativecommons.org/publicdomain/zero/1.0/)
