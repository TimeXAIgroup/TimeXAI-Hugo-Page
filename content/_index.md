---
# Home-Page
title: Home
type: landing

sections:

# ======================
# TITEL IMAGE SMALLER WIDTH
# ======================
#- block: markdown
#  content:
#    text: |
#      <div class="hero-home-small">
#          <img src="https://timexaigroup.github.io/TimeXAI-Hugo-Page/uploads/teaser_homepage_aaiLab_small.png" alt="Hero Image"/>
#      </div>
#  design:
#    columns: '1'
#    spacing:
#      padding: ['0','0','0','0']
#    css_class: hero-centered
  
# ======================
# TITEL IMAGE FULL WIDTH
# ======================
- block: markdown
  content:
    text: |
      <div class="hero-home">
          <img src="uploads/teaser_homepage_aaiLab_small.png" alt="Applied AI Lab at Technische Hochschule Mittelhessen"/>
      </div>
  design:
    columns: '1'
    spacing:
      padding: ['0','0','0','0']
    css_class: hero-fullwidth

# ======================
# INTRO + ANIMATION ICONS
# ======================
- block: markdown
  content:
    text: |
      <div class="home-intro-icons text-center">
        <div class="home-intro">        
          <h1 class="text-center">Applied AI Lab</h1>
          <p class="text-center">
            The Applied Artificial Intelligence Lab, at <a href="https://www.thm.de/site/" target="_blank">Technische Hochschule Mittelhessen</a> - University of Applied Sciences is headed by Prof. Dr. Jennifer Hannig, Professor of Artificial Intelligence at THM and  <a href="https://hessian.ai/" target="_blank">hessian.AI</a> (Hessian Center for Artificial Intelligence).</p>
            <p class="text-center">
            The lab is affiliated with the Department of Mathematics, Natural Sciences and Data Processing (<a href="https://www.thm.de/mnd/" target="_blank">MND</a>) and the Centre of Competence for Information Technology (<a href="[https://www.thm.de/kite/](https://www.thm.de/kompetenzzentren/en/kite)" target="_blank">KITE</a>). Its research focuses on trustworthy and explainable artificial intelligence, developing methods that make AI systems transparent and understandable for complex and multimodal data, including time series, images, and video, and applying these approaches in real-world systems.</p>
        </div>
        <div class="home-about-icons">
          <div class="care-item">
            <a href="aai/" class="care-inner">
              <img src="uploads/aai_icon2.png" alt=""/>
              <span class="care-label">About Us</span>
            </a>
          </div>
          <div class="care-item">
            <a href="research" class="care-inner">
               <img src="uploads/project_icon2.png" alt=""/>
               <span class="care-label">Projects</span>
            </a>
          </div>
          <div class="care-item">
            <a href="students" class="care-inner">
              <img src="uploads/teaching_icon2.png" alt=""/>
              <span class="care-label">Teaching</span>
            </a>
          </div>
          <div class="care-item">
            <a href="publication" class="care-inner">
              <img src="uploads/paper_icon2.png" alt=""/>
              <span class="care-label">Publications</span>
            </a>
          </div>
        </div>
      </div>
  design:
    columns: '1'
    spacing:
      padding: ['80px','30px','80px','30px']

# ======================
# PARTNER LOGOS
# ======================
- block: markdown
  content:
    text: |
      <div class="hero-partner-logos text-center">
        <a href="aai/" target="_blank">
          <img src="uploads/aai_lab.png" alt="Applied AI Lab"/>
        </a>
        <a href="https://www.thm.de/kompetenzzentren/kite/profil.html" target="_blank">
         <img src="uploads/kite_logo.png" alt="KITE"/>
        </a>
        <a href="https://www.thm.de" target="_blank">
          <img src="uploads/THM_logo.png" alt="THM"/>
        </a>
        <a href="https://hessian.ai" target="_blank">
          <img src="uploads/HessenAi_logo.png" alt="HessenAI"/>
        </a>
      </div>
  design:
    columns: '1'
    spacing:
      padding: ['20px','0','70px','0']

# ======================
# FEATURED VIDEO
# ======================
- block: markdown
  content:
    text: |
      <section class="featured-video">
      <div class="featured-video__text">
      <p class="featured-video__eyebrow">Video Podcast</p>
      <h2>Making AI Understandable</h2>
      <p>A video podcast featuring Prof. Dr. Jennifer Hannig on explainable AI, transparent model decisions, and the importance of trustworthy AI in high-stakes applications.</p>
      <a href="https://www.youtube.com/watch?v=OqfVpfbw1-4" target="_blank" rel="noopener noreferrer">Watch the video podcast →</a>
      </div>
      <div class="featured-video__player">
      <iframe src="https://www.youtube-nocookie.com/embed/OqfVpfbw1-4" title="Making AI Understandable with Prof. Dr. Jennifer Hannig" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>
      </section>
  design:
    columns: '1'
    spacing:
      padding: ['30px', '20px', '40px', '20px']


# ======================
# LATEST NEWS
# ======================
#- block: collection
#  content:
#    text: |
#      <div class="latest-news-section">
#        <h1 class="text-center">Latest News</h1>
#        <p class="text-center">
#          Check out the latest activities!
#        </p>
#      </div>
#  filters:
#    folders:
#      - news
#    order: desc
#    limit: 3
#  design:
#    view: card
#    columns: '3'
#    css_id: news
#    show_image: true
#    show_date: true
#    show_summary: true
#    spacing:
#      padding: ['60px','30px','60px','30px']

# ======================
# OPEN POSITIONS
# ======================
- block: markdown
  content:
    text: |
      <div class="open-positions-section">
        <h1 class="text-center">Open Positions</h1>
        <p class="text-center">
          Discover the opportunities we offer!<br>
          We are always interested in connecting with motivated and talented individuals. 
          Whether you are a student, researcher, or industry expert, we welcome opportunities to collaborate on projects and exchange expertise.       
          Work with us and contribute to advancing applied artificial intelligence.
        </p>

        <div class="home-open-positions">
          <div class="position-item">
            <a href="https://www.thm.de/site/hochschule/profil/job-und-karriere/aktuelle-stellenangebote.html" target="_blank">
              <img src="uploads/thm_job_icon.png" alt=""/>
              <span class="position-label">Job Openings</span>
            </a>         
          </div>
          <div class="position-item">
            <a href="students">
              <img src="uploads/hiwi_job_icon.png" alt=""/>
              <span class="position-label">Student Opportunities</span>
            </a>
          </div>
          <div class="position-item">
            <a href="students/theses/">
              <img src="uploads/thesis_icon.png" alt=""/>
              <span class="position-label">Thesis Topics</span>
            </a>
          </div>
        </div>
      </div>
  design:
    columns: '1'
    spacing:
      padding: ['60px','30px','60px','30px']
---
