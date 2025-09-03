# Biagio Rosso

---
layout: default
title: Home
---

# Welcome to My Website

![Hero Image](assets/images/hero-banner.jpg){: .hero-image}

## About Me

Hi, I'm **Your Name**, a passionate [your profession/field]. I love creating amazing things and sharing my knowledge with the world.

## Research Work and Interests

## Publications and Public Working Papers

<div class="project-grid">
  {% for project in site.projects limit:3 %}
    <div class="project-card">
      <img src="{{ project.image }}" alt="{{ project.title }}">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.excerpt }}</p>
    </div>
  {% endfor %}
</div>

[View All Projects](projects){: .btn .btn-secondary}

## Work in Progress


## Connect With Me

- 📧 [Email me](mailto:{{br421@cam.ac.uk}})
- 💼 [LinkedIn](https://linkedin.com/in/{{ site.social.linkedin }})
- 🐙 [GitHub](https://github.com/{{ site.social.github }})
- 🐦 [Twitter](https://twitter.com/{{ site.social.twitter }})

![Footer Image](assets/images/footer-graphic.svg){: .footer-image}
