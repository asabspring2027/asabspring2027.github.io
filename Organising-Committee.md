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
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Marine Joly"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Marine Joly</h2>
      </div>
      <p>Short blurb about Marine Joly goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/people/lucy-bates.jpg"
        alt="Lucy Bates"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Lucy Bates</h2>
      </div>
      <p>Short blurb about Lucy Bates goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/people/lucy-bates.jpg"
        alt="Teresa Romero"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Teresa Romero</h2>
      </div>
      <p>Short blurb about Teresa Romero goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
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

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Sarah Salphati"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Sarah Salphati</h2>
      </div>
      <p>Short blurb about Sarah Salphati goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Vasco Honigford-Martins"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Vasco Honigford-Martins</h2>
      </div>
      <p>Short blurb about Vasco Honigford-Martins goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Leanne Proops"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Leanne Proops</h2>
      </div>
      <p>Short blurb about Leanne Proops goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Jerome Micheletta"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Jerome Micheletta</h2>
      </div>
      <p>Short blurb about Jerome Micheletta goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Juliane Kaminski"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Juliane Kaminski</h2>
      </div>
      <p>Short blurb about Juliane Kaminski goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/rachel-thomson.jpg"
        alt="Ester Herrmann"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Ester Herrmann</h2>
      </div>
      <p>Short blurb about Ester Herrmann goes here.</p>
    </div>
  </div>

</div>

</style>

<style>
/* Keep the page wide enough, but not huge */
.site__content .container {
  max-width: none !important;
}

/* Main committee card grid */
.committee-grid {
  display: grid !important;
  grid-template-columns: repeat(3, minmax(280px, 1fr)) !important;
  gap: 2.2rem !important;
  margin-top: 3rem !important;

  /* similar width to the homepage card area */
  width: 84vw !important;
  max-width: 1320px !important;

  /* centre evenly */
  margin-left: 50% !important;
  transform: translateX(-50%) !important;
}

/* Make each card fill its grid column */
.committee-grid .post-card {
  width: 100% !important;
  max-width: none !important;
  min-width: 0 !important;
  margin: 0 !important;
  display: block !important;
  cursor: default !important;
}

/* Image area: less tall than before, closer to homepage */
.committee-grid .post-card__thumb {
  width: 100% !important;
  aspect-ratio: 1.55 / 1 !important;
  height: auto !important;
  margin: 0 !important;
  overflow: hidden !important;
  display: block !important;
}

/* Images crop neatly but favour the face/top area */
.committee-grid .post-card__thumb img,
.committee-grid .post-card__thumb .dark-bg {
  width: 100% !important;
  height: 100% !important;
  object-fit: cover !important;
  object-position: center 25% !important;
  display: block !important;
}

/* Text section */
.committee-grid .post-card__inner {
  display: block !important;
  padding: 1.8rem !important;
  text-decoration: none !important;
  cursor: default !important;
}

/* Name */
.committee-grid .post-card__header h2 {
  margin: 0 0 0.9rem 0 !important;
}

/* Blurb */
.committee-grid .post-card__inner p {
  margin: 0 !important;
}

/* Tablet: two cards per row */
@media (max-width: 1000px) {
  .committee-grid {
    grid-template-columns: repeat(2, minmax(260px, 1fr)) !important;
    width: 90vw !important;
  }
}

/* Phone: one card per row */
@media (max-width: 700px) {
  .committee-grid {
    grid-template-columns: 1fr !important;
    width: 90vw !important;
  }
}
</style>
