---
layout: default
title: Home
---
<style>
  .profile-container {
    display: flex;
    align-items: stretch;
    margin-bottom: 2rem;
    min-height: 250px;
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
    justify-content: flex-end;
  }
  .contact-info {
    margin-bottom: 2.8rem; /* Add space between contact info and quote */
  }
  .quote-container {
    font-style: italic;
    color: #555;
  }
  .quote-text {
    display: inline;
    position: relative;
  }
  .quote-text:before {
    content: '"';
    font-size: 1.5em;
    line-height: 0;
    vertical-align: -0.25em;
  }
  .quote-text:after {
    content: '"';
    font-size: 1.5em;
    line-height: 0;
    vertical-align: -0.25em;
  }
  .quote-author {
    display: inline-block;
    margin-left: 0.5rem;
    font-weight: bold;
  }

  /* Media query for mobile devices */
  @media (max-width: 767px) {
    .profile-container {
      flex-direction: column;
      align-items: center;
    }
    .profile-image {
      width: 200px;
      height: 200px;
      margin-right: 0;
      margin-bottom: 1rem;
    }
    .info-quote-container {
      text-align: center;
    }
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