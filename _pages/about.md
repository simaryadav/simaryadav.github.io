---
layout: page
title: 
description: 
permalink: /Contact-us/
---

<style>
/* Base (Desktop) Styles */
.container {
  max-width: 1200px; /* Maintain desktop width */
  width: 100%;
  margin: 0 auto;
}

.page-section-head {
  margin-top: 40px;
  margin-bottom: 60px;
  padding-bottom: 60px;
  border-bottom: 1px solid var(--border-color);
}

.page-title {
  font-size: 80px; /* Large size for desktop */
  margin-bottom: 16px;
  width: 100%; /* Ensure the title stretches fully */
  text-align: left; /* Left align for desktop */
}

.page-description {
  font-size: 18px;
  text-align: left; /* Keep left alignment for desktop */
}

.contact-info {
  display: flex;
  flex-wrap: nowrap; /* No wrapping for desktop */
  flex-direction: row; /* Horizontal layout */
  justify-content: space-between;
  align-items: flex-start;
}

.contact-info-item {
  width: 30%; /* Allocate width for each item */
  text-align: left;
}

.contact-info-item h2 {
  margin-bottom: 10px;
  font-size: 24px; /* Desktop-specific font size */
}

.gallery {
  margin-top: 40px;
  display: flex;
  justify-content: space-around; /* Spread items evenly */
  gap: 20px;
}

.gallery img {
  max-width: 300px; /* Set fixed width for desktop */
  height: auto;
  object-fit: cover;
}

.page__info {
  display: none;
}

.iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

.nine {
  width: 100%;
  height: auto;
  margin-top: 20px;
  max-width: 100%;
}

/* Tablet Styles */
@media (max-width: 1024px) {
  .page-title {
    font-size: 64px; /* Slightly smaller for tablets */
    text-align: center; /* Center-align title */
  }

  .page-section-head {
    margin-bottom: 40px;
    padding-bottom: 20px;
  }

  .contact-info {
    flex-wrap: wrap; /* Allow items to wrap */
    justify-content: center; /* Center-align items */
  }

  .contact-info-item {
    width: 45%; /* Allocate more space per item */
    text-align: center;
    margin-bottom: 20px;
  }

  .contact-info-item h2 {
    font-size: 20px; /* Adjust heading size */
  }

  .gallery {
    gap: 16px; /* Reduce space between items */
  }

  .gallery img {
    max-width: 100%; /* Use full width */
  }
}

/* Mobile Styles */
@media (max-width: 768px) {
  .page-title {
    font-size: 36px; /* Smaller size for mobile */
    text-align: center;
    margin-bottom: 20px;
  }

  .page-description {
    font-size: 16px;
    text-align: center; /* Center-align for mobile */
  }

  .contact-info {
    flex-direction: column; /* Stack items vertically */
    align-items: center;
  }

  .contact-info-item {
    width: 100%; /* Full width for mobile */
    text-align: center;
    margin-bottom: 16px;
  }

  .contact-info-item h2 {
    font-size: 18px;
  }

  .gallery {
    flex-direction: column; /* Stack images vertically */
    align-items: center;
    gap: 12px;
  }

  .gallery img {
    width: 100%; /* Full width on mobile */
    height: auto;
  }
}
</style>


<div class="container">
  <div class="page-section-head">
    <h1 class="page-title">Contact Us</h1>
  </div>

  <div class="contact-info">
    <div class="contact-info-item">
      <h2>Address and Contact Info</h2>
      <p>Room 4012 and 4011 <br>
      The Assembly<br>
      5051 Centre Avenue,<br>
      Pittsburgh, PA 15213</p>
      <p>Email: jishnu@pitt.edu<br>
      Phone: 412-624-5530</p>
    </div>
  </div>

  <div class="button-container">
    <a class="tag-button" href="https://scholar.google.com/citations?user=61wI3HMAAAAJ&hl=en" target="_blank">Google Scholar</a>
    <a class="tag-button" href="https://github.com/jishnu-lab" target="_blank">GitHub</a>
    <a class="tag-button" href="https://twitter.com/jishnu1729" target="_blank">Twitter</a>
  </div>

  <iframe class = "nine" style="width: 95%; height: 600px;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3035.9222785433276!2d-79.94718492394952!3d40.454857153317924!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8834f34f6212ade3%3A0x18f7f9a7b1d0f338!2sThe%20Assembly!5e0!3m2!1sen!2sus!4v1714092409211!5m2!1sen!2sus" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>


