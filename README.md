# Biagio Rosso


# Welcome to My Website

<img src="assets/images/IMG_3345.jpg" alt="Description" style="width: 400px; height: auto;">

## About Me

Hi, I'm Biagio Rosso, a passionate [your profession/field]. I love creating amazing things and sharing my knowledge with the world.

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

- 📧 [Email me](mailto:br421@cam.ac.uk)
- 💼 [LinkedIn](https://uk.linkedin.com/in/biagio-rosso)
- 🐙 [GitHub](https://github.com/{{BiagioR}})
- 🐦 [Bluesky](https://bsky.app/profile/biagiorosso.bsky.social)


