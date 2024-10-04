---
layout: default
title: Projects
permalink: /hack/
---
<main class="page-content" aria-label="Content">

<div class="work-section">
  <h2>Hackathons</h2>
  <div class="cards">
    {% for hackathon in site.hackathons %}
    <div class="card">
      <h3><a href="{{ hackathon.url }}">{{ hackathon.title }}</a></h3>
      <p><strong>Date:</strong> {{ hackathon.date | date_to_string }}</p>
      <p><strong>Project:</strong> {{ hackathon.description }}</p>
    </div>
    {% endfor %}
  </div>
</div>

<hr>

<div class="work-section">
  <h2>Projects</h2>
  <div class="cards">
    {% for project in site.projects %}
    <div class="card">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p><strong>Date:</strong> {{ project.date | date_to_string }}</p>
      <p><strong>Description:</strong> {{ project.description }}</p>
    </div>
    {% endfor %}
  </div>
</div>

</main>








  <!--Footer-->
  <footer class="site-footer h-card">
    <data class="u-url" href="/"></data>
    <div class="wrapper">
      <h2 class="footer-heading">Neha Balamurugan</h2>
      <div class="footer-col-wrapper">
        <div class="footer-col footer-col-1">
          <ul class="contact-list">
            <li class="p-name">Neha Balamurugan</li>
            <li><a class="u-email" href="mailto:nbalamuru@gmail.com">nbalamuru@gmail.com</a></li>
          </ul>
        </div>
        <div class="footer-col footer-col-2">
          <ul class="social-media-list">
            <li><a href="https://github.com/nehabalamurugan"><svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#github"></use></svg> <span class="username">nehabalamurugan</span></a></li>
            <li><a href="https://www.linkedin.com/in/neha-balamurugan"><svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#linkedin"></use></svg> <span class="username">nehabalamurugan</span></a></li>
          </ul>
        </div>
        <div class="footer-col footer-col-3">
          <p>Neha Balamurugan&#39;s personal website</p>
        </div>
      </div>
    </div>
  </footer>