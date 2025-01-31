---
layout: default
title: "Bienvenido a Mi Sitio"
description: "Este es un sitio creado con Jekyll y GitHub Pages. Aquí encontrarás mi blog y más información sobre mis proyectos."
permalink: /
---

# Bienvenido a Mi Sitio Web

¡Hola! Soy **[Tu Nombre]**, un apasionado de la tecnología y el desarrollo web. Este es mi sitio personal donde comparto mis pensamientos, proyectos y recursos útiles.

---

## Acerca de

Soy un desarrollador web con experiencia en Ruby, Jekyll, y otras tecnologías. Mi pasión por la programación comenzó hace varios años, y desde entonces he estado trabajando en diferentes proyectos, tanto personales como profesionales. Mi objetivo es siempre aprender y mejorar en cada paso.

- **Habilidades**: Ruby, Jekyll, HTML, CSS, JavaScript
- **Proyectos favoritos**: [Proyecto 1](#), [Proyecto 2](#), [Proyecto 3](#)

---

## Últimos Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}

---

## Contacto

Si deseas ponerte en contacto conmigo, puedes enviarme un correo a: **[tucorreo@dominio.com](mailto:tucorreo@dominio.com)** o seguirme en mis redes sociales:

- [Twitter](https://twitter.com/)
- [GitHub](https://github.com/)
- [LinkedIn](https://linkedin.com/)

---

Gracias por visitar mi sitio. ¡Espero que disfrutes el contenido!

