---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

  <style>
    .intro-section {
      display: flex;
      border: 2px solid #e8e8e8;
      padding: 20px;    
      max-width: 800px;
      margin-top: 20px;
      align-items: center;
      gap: 20px;
    }
    .intro-section img {
      max-width: 350px;
    }
    .intro-section p {
      margin: 0;
      font-size: 20px;
    }
    .intro-section .enjoy {
      margin: 0;
      padding-top: 15px;
      font-size: 20px;
    }

/* Timeline CSS */
.timeline-wrapper {
  padding: 20px;
  margin-top: 20px;
}

.timeline {
  position: relative;
  max-width: 800px; /* Set a max width for the timeline */
  margin: 0 auto;
}

.timeline::after {
  content: '';
  position: absolute;
  width: 2px; /* Thinner line */
  background-color: #e8e8e8;
  top: 0;
  bottom: 0;
  left: 20px; /* Position line closer to the left */
  margin-left: -2px;
}

.timeline-item {
  padding: 5px 20px;
  position: relative;
  background-color: inherit;
  width: 100%; /* Full width */
  margin-left: 10px; /* Indent content from the line */
}

.timeline-item::after {
  content: '';
  position: absolute;
  width: 10px; /* Smaller circle */
  height: 10px; /* Smaller circle */
  background-color:  #e8e8e8;
  border: 4px solid #e8e8e8;
  top: 15px;
  left: -1px; /* Position circle closer to the line */
  border-radius: 50%;
  z-index: 1;
}

.timeline-content {
  display: flex; /* Add this line */
  align-items: left; /* Add this line */
  padding: 5px 30px;
  background-color: rgb(255, 255, 255);
  position: relative;
  border-radius: 6px;
}

.timeline-content h2 {
  margin-top: 0;
  font-size: 20px;
}

.timeline-content p {
  margin: 0;
  font-size: 16px;
}

.timeline-content time {
  display: block;
  font-size: 15px;
  color: #888;
}
.timeline-logo {
  width: 70px; /* Set width of logo */
  height: 50px; /* Set height of logo */
  margin-right: 10px; /* Space between logo and text */
  margin-left: 10px; /* Space between logo and text */
  vertical-align: middle; /* Align vertically with text */
}
.timeline-ridge {
  width: 50px; /* Set width of logo */
  height: 50px; /* Set height of logo */
  margin-right: 10px; /* Space between logo and text */
  margin-left: 10px; /* Space between logo and text */
  vertical-align: middle; /* Align vertically with text */
}
</style>

<!--Body-->
  <main class="page-content" aria-label="Content">
    <div class="wrapper">
      <div class="intro-section">
        <img src="/assets/images/profile.jpg" alt="Neha Balamurugan">
        <div class="wrapper">
            <h1> Hi, I'm Neha👋🏾 </h1> 
            <p>I'm a computer science researcher interested in VR/AR, ML and entreprenuership. Welcome to my personal website where I share my projects, career, and more!</p>
            <p class="enjoy">I like: 🎾 👩🏾‍💻 🧄 🏋🏾‍♀️ 🦦 🌵</p>
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="timeline-wrapper">
        <div class="timeline">
        <div class="timeline-item">
            <div class="timeline-content">
              <time> 2024-2026</time>
              <img src="/assets/images/stanford-logo.webp" alt="Stanford" class="timeline-logo">
              <p> Pursuing a MSc in Computer Science at Stanford Univeristy with a concentration in AI. </p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-content">
              <time> 2021-2024</time>
              <img src="/assets/images/asu-logo.png" alt="ASU" class="timeline-logo">
              <p> Graduated Summa Cum Laude from Arizona State University with BSc in Computer Science as an Outstanding Graduate. Researched Virtual Reality at the <a href="https://meteor.ame.asu.edu/" target="_blank">Meteor Studio</a>, and Augmented Reality at <a href="https://hcistudio.org/" target="_blank">HCIstudio</a>. Won a few hackathons and won even fewer club tennis tournaments. 
             </p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-content">
              <time> 2017-2021</time>
              <img src="/assets/images/mtn-logo.jpeg" alt="ASU" class="timeline-logo">
              <p> Finished as the Valedictorian of Mountain Ridge High School in 2021 where I played better tennis, took too many APs, and founded <a href="https://www.yourvalley.net/stories/mountain-ridge-students-help-break-digital-divide,181284" target="_blank">Break Digital Divide</a>. 
             </p>
            </div>
          </div>
          <!-- Add more timeline items as needed -->
        </div>
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

