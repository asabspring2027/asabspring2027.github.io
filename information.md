---
layout: page
title: Information for Presenters & Attendees
permalink: /information/
featured-img: trb_carpintero_1920
---

<div class="committee-grid">

  <a href="/Info-presenters/" class="post-card committee-card">
    <figure class="post-card__thumb">
        <img
        src="/assets/img/posts/trb_iguana22_sm.jpg"
        alt="Information for Presenters"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Information for Presenters</h2>
      </div>
      <p>All you need to know if you are presenting a talk or a poster.</p>
    </div>
  </a>

<a href="/Info-presenters/" class="post-card committee-card">
    <figure class="post-card__thumb">
        <img
        src="/assets/img/posts/trb_martinete_sm.jpg"
        alt="Information for Attendees"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Information for Presenters</h2>
      </div>
      <p>Important information for anyone attending the conference.</p>
    </div>
  </a>

<a href="/registration/" class="post-card committee-card">
    <figure class="post-card__thumb">
        <img
        src="/assets/img/posts/trb_capuchinbb2_sm.jpg"
        alt="Registration"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Registration</h2>
      </div>
      <p>To attend the conference, please register here.</p>
    </div>
  </a>

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


