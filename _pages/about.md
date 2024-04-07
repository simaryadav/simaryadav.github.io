---
layout: page
title: Contact Us
description: Thank you for your interest in our research. Get in touch with us for any questions or comments regarding our work and publications. Currently, we have open positions at all levels (e.g., post-docs, graduate students, and undergrads).
permalink: /about/
---

<style>
.container {
  max-width: fit-content;
  margin: 0 auto;
  width: -webkit-fill-available;
}

.page-section-head {
  margin-top: 40px;
  margin-bottom: 60px;
  padding-bottom: 60px;
  border-bottom: 1px solid var(--border-color);
}

.page-title {
  font-size: 32px;
  margin-bottom: 16px;
}

.page-description {
  font-size: 18px;
  margin-bottom: 0;
}

.col-md-6 {
  width: 50%;
}

.gallery-box {
  width: 50%;
  margin-top: 40px;
}

.gallery {
  display: flex;
  justify-content: center;
}

.gallery img {
  max-width: 100%;
  height: auto;
}

</style>

<div class="container__contact__head">
  <div class="contact-head">
    {% if site.data.settings.about.description %}
    <p class="contact-description">{{ site.data.settings.about.description }}</p>
    {% endif %}
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col-md-6">
      <h2>Address and Contact Info</h2>
      <p>4011 The Assembly<br>
      5051 Centre Avenue,<br>
      Pittsburgh, PA 15213</p>
      <p>Email: jishnu@pitt.edu<br>
      Phone: 412-624-5530</p>
    </div>
    <div class="gallery-box">
        <div class="gallery">
          <img src="/images/Pitt.webp" loading="lazy" alt="Author">
      </div>
    </div>
  </div>
</div>
