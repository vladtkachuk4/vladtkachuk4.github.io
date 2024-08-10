---
layout: default
title: Home
---
<style>
  .profile-container {
    display: flex;
    align-items: stretch;
    margin-bottom: 2rem;
  }
  .profile-image {
    width: 250px;
    height: 250px;
    object-fit: cover;
    border-radius: 50%;
    margin-right: 2rem;
  }
  .info-quote-container {
    flex: 1;
    display: flex;
    flex-direction: column;
  }
  .contact-info-wrapper {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .contact-info {
    /* Add any specific styles for contact info here */
  }
  .quote-container {
    margin-top: auto;
    padding-top: 1rem;
  }
  .quote {
    font-style: italic;
    color: #555;
    display: inline;
    position: relative;
  }
  .quote:before, .quote:after {
    font-size: 2rem;
    vertical-align: middle;
  }
  .quote:before {
    content: '"';
    margin-right: 0.25rem;
  }
  .quote:after {
    content: '"';
    margin-left: 0.25rem;
  }
  .quote-author {
    display: inline-block;
    vertical-align: middle;
    margin-left: 1rem;
    font-weight: bold;
    color: #555;
  }
</style>

<div class="profile-container">
  <img src="/assets/images/headshot.jpg" alt="Vlad Tkachuk" class="profile-image">
  <div class="info-quote-container">
    <div class="contact-info-wrapper">
      <div class="contact-info">
        <p>PhD Student<br>
          Department of Computing Science <br>
          University of Alberta</p>
        <p>Email: vtkachuk at ualberta dot ca<br>
          <a href="https://scholar.google.com/citations?user=9sSwAAsAAAAJ&hl=en">Scholar</a> |
          <a href="https://scholar.google.com/citations?user=9sSwAAsAAAAJ&hl=en">CV</a> |
          <a href="https://www.linkedin.com/in/vtkachuk4/">LinkedIn</a> |
          <a href="https://x.com/VladTkachuk5">Twitter</a> |
          <a href="https://www.youtube.com/@VladTkachukAcademic">Youtube</a>
        </p>
      </div>
    </div>
    <div class="quote-container">
      <span class="quote">There is no substitute for hard work</span>
      <span class="quote-author">- Thomas Edison</span>
    </div>
  </div>
</div>
<p>I am a first-year PhD student in Computing Science at the University of Alberta, working under the supervision of <a href="https://sites.ualberta.ca/~szepesva/">Csaba Szepesvári</a> and <a href="https://xiaoqitan.org/">Xiaoqi Tan</a>. I completed my master's degree at the University of Alberta, also under the supervision of Csaba Szepesvári. Before that, I obtained my bachelor's in Electrical Engineering from the University of Waterloo.</p> 
<p>My research interests lie primarily in reinforcement learning theory (for now).</p>