---
layout: page
title: Organising Committee
permalink: /Organising-Committee/
featured-img: shane-rounce-205187
---

<div class="committee-grid">

  <div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/marine-joly.jpg"
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
        src="/assets/img/profile-pics/lucy-bates.jpg"
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
        src="/assets/img/profile-pics/teresa-romero.jpg"
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
        src="/assets/img/profile-pics/rachel-thomson2.jpg"
        alt="Rachel Thomson"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Rachel Thomson</h2>
      </div>
      <p>Rachel is a second year PhD student researching elephant cognition, personality and human-elephant conflict. She is studying wild elephant curiosity - with the aim of exploring if specific traits are associated with the age-sex cohorts that engage in crop-raiding. She is also investigating zoo elephant problem-solving behaviour using puzzle boxes, and working to validate a captive elephant personality questionnaire for the Elephant Welfare Group.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/sarah-salphati.jpg"
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
        src="/assets/img/profile-pics/vasco-honigford-martins2.jpg"
        alt="Vasco Honigford-Martins"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Vasco Honigford-Martins</h2>
      </div>
      <p>Vasco is a second year PhD student exploring the intersection of wildlife behaviour, plastic pollution, and human perspectives. His interdisciplinary research examines moor macaque interactions with plastic waste, human perceptions of wildlife–waste interactions, and arts-based approaches to raise awareness.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/leanne-proops.jpg"
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
        src="/assets/img/profile-pics/jerome-micheletta.jpg"
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
        src="/assets/img/profile-pics/juliane-kaminski.jpg"
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
        src="/assets/img/profile-pics/ester-herrmann.jpg"
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
  width: 78vw !important;
  max-width: 1200px !important;

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

/* Image area: same width, but a bit taller for profile photos */
.committee-grid .post-card__thumb {
  width: 100% !important;
  aspect-ratio: 1.25 / 1 !important;
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
  object-position: center 20% !important;
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

