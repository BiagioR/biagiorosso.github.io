---
layout: default
title: Home
projects:
  - title: "Rosso, B. & Gatto, M. (2024). Dynamics and Optimal Monetary-Fiscal Policy in Fiscally Dominant
    Economies with Occasionally Inflexible Monetary Authorities. MPRA Paper, University Li-
    brary of Munich, Germany. 2025"
    description: "Included in NEP reports: NEP-CBA,
    NEP-DGE, NEP-MON, NEP-MAC."
    link: https :/ / mpra .ub . uni- muenchen. de / 125094/ 1 /
    MPRA_paper_125094.pdf
    
  - title: "Weather App"
    description: "Real-time weather dashboard with forecasts"
    image: "assets/images/projects/weather.jpg"
    github: "https://github.com/yourusername/weather"
    demo: "https://weather-demo.com"
    technologies:
      - JavaScript
      - OpenWeatherMap API
      - CSS3
    featured: true
    
  - title: "Blog Website"
    description: "Personal blog built with Jekyll and GitHub Pages"
    image: "assets/images/projects/blog.jpg"
    github: "https://github.com/yourusername/blog"
    demo: "https://yourusername.github.io/blog"
    technologies:
      - Jekyll
      - Markdown
      - Sass
    featured: false
---

# Biagio Rosso


# Welcome to My Website

<img src="assets/images/IMG_3345.jpg" alt="Description" style="width: 300px; height: auto;">

## About Me

Hi, I'm Biagio Rosso, a passionate [your profession/field]. I love creating amazing things and sharing my knowledge with the world.

## Research Work and Interests

## Publications and Public Working Papers

<div class="project-grid">
  {% for project in site.projects limit:3 %}
    <div class="project-card">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.excerpt }}</p>
    </div>
  {% endfor %}
</div>

[View All Projects](projects){: .btn .btn-secondary}

## Work in Progress


## Connect With Me

- 📧 [Email me](mailto:br421@cam.ac.uk)
- 💼 [LinkedIn](https://uk.linkedin.com/in/biagio-rosso)
- 🐙 [GitHub](https://github.com/{{BiagioR}})
- 🐦 [Bluesky](https://bsky.app/profile/biagiorosso.bsky.social)


