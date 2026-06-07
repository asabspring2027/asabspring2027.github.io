---
layout: page
title: Programme
permalink: /programme/
featured-img: lion.jpg
---

## Plenary speakers 

<div class="committee-grid">

  <div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/katie-slocombe.jpg"
        alt="Katie Slocombe"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Katie Slocombe</h2>
      </div>
      <p>Short blurb about Katie Slocombe goes here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/alex-thornton.jpg"
        alt="Alex Thornton"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Alex Thornton</h2>
      </div>
      <p>Blurb about Alex Thornton here.</p>
    </div>
  </div>

<div class="post-card committee-card">
    <figure class="post-card__thumb">
      <img
        src="/assets/img/profile-pics/aurore-avargues-weber.jpg"
        alt="Aurore Avargues-Weber"
      />
    </figure>

    <div class="post-card__inner committee-card__inner">
      <div class="post-card__header">
        <h2>Aurore Avargues-Weber</h2>
      </div>
      <p>Short blurb about Aurore Avargues-Weber here.</p>
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



## Workshop Details 


<div class="workshop-card">
  <div class="workshop-card__image">
    <img
      src="/assets/img/profile-pics/christian-nawroth.jpg"
      alt="Christian Nawroth"
    />
  </div>

  <div class="workshop-card__content">
    <h2>Christian Nawroth</h2>
    <h3>Workshop details / title goes here</h3>

    <p>
      Write the blurb about the person and their workshop here. This can include
      a short bio, what the workshop covers, and who it is suitable for.
    </p>
  </div>
</div> 

<style>
.workshop-card {
  width: 65vw;
  max-width: 1000px;
  min-width: 0;
  margin: 2.5rem auto;
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  padding: 1.8rem;
  background: #fff;
  box-shadow: 0 2px 14px rgba(0, 0, 0, 0.08);
  border-radius: 4px;
}

.workshop-card__image {
  flex: 0 0 260px;
  height: 190px;
  overflow: hidden;
  border-radius: 4px;
}

.workshop-card__image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 20%;
  display: block;
}

.workshop-card__content {
  flex: 1;
  min-width: 0;
}

.workshop-card__content h2 {
  margin: 0 0 0.4rem 0;
  font-size: 2rem;
}

.workshop-card__content h3 {
  margin: 0 0 1rem 0;
  font-size: 1.05rem;
  font-weight: 500;
  color: #777;
}

.workshop-card__content p {
  margin: 0;
}

@media (max-width: 700px) {
  .workshop-card {
    width: 90vw;
    flex-direction: column;
  }

  .workshop-card__image {
    width: 100%;
    height: auto;
    aspect-ratio: 1.5 / 1;
    flex: none;
  }
}
</style>

## Full programme

| Day           | Time    | Topic   |
| --------------| ------- |---------|
| 07/04/2027    |         |         |
| 08/04/2027    |         |         |
| 09/04/2027    |         |         |

Include link to pdf
