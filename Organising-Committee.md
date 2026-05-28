---
layout: page
title: Organising Committee
permalink: /Organising-Committee/
featured-img: shane-rounce-205187
---

## Organising Committee

<div class="committee-grid">

  <div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/people/rachel-thomson.jpg"
        alt="Rachel Thomson"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Rachel Thomson</h2>
      </div>
      <p>Short blurb about Rachel Thomson goes here.</p>
    </div>
  </div>

</div>

<style>
.committee-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 3rem;
  margin-top: 2rem;
}

.committee-card {
  cursor: default;
}

.committee-card a {
  pointer-events: none;
}

.committee-card .post-card__thumb img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

/* This stops the card behaving like a link */
.committee-card__inner {
  cursor: default;
  text-decoration: none;
}

/* Mobile layout */
@media (max-width: 900px) {
  .committee-grid {
    grid-template-columns: 1fr;
  }
}
</style>





