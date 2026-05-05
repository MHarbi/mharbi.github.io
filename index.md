---
layout: home
title: ""
---

<style>
  .coming-soon-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 70vh;
    text-align: center;
    padding: 3rem 1.5rem;
    font-family: Georgia, "Times New Roman", serif;
  }

  .cs-label {
    font-size: 0.75rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: #888;
    margin-bottom: 1.2rem;
  }

  .cs-name {
    font-size: clamp(2rem, 5vw, 3.2rem);
    font-weight: 700;
    color: #1a1a2e;
    margin: 0 0 0.3rem;
    line-height: 1.15;
  }

  .cs-title {
    font-size: 1rem;
    font-style: italic;
    color: #555;
    margin: 0 0 2.5rem;
  }

  .cs-divider {
    width: 48px;
    height: 3px;
    background: #1a1a2e;
    border: none;
    margin: 0 auto 2.5rem;
    border-radius: 2px;
  }

  .cs-headline {
    font-size: clamp(1.6rem, 4vw, 2.4rem);
    font-weight: 700;
    color: #1a1a2e;
    margin: 0 0 1rem;
    letter-spacing: -0.02em;
  }

  .cs-sub {
    font-size: 1.05rem;
    color: #555;
    max-width: 520px;
    line-height: 1.7;
    margin: 0 auto 2.5rem;
    font-style: italic;
  }

  .cs-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    justify-content: center;
    margin-bottom: 3rem;
  }

  .cs-links a {
    display: inline-block;
    padding: 0.5rem 1.2rem;
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    text-decoration: none;
    border: 1.5px solid #1a1a2e;
    color: #1a1a2e;
    border-radius: 2px;
    transition: background 0.2s, color 0.2s;
  }

  .cs-links a:hover {
    background: #1a1a2e;
    color: #fff;
  }

  .cs-contact {
    font-size: 0.9rem;
    color: #888;
    margin-top: 0.5rem;
  }

  .cs-contact a {
    color: #555;
    text-decoration: underline;
    text-underline-offset: 3px;
  }
</style>

<div class="coming-soon-wrapper">

  <img src="{{'/assets/img/234567fghjk.png' | relative_url}}" alt="Taibah University" height="70" style="margin-bottom: .5em;"/>

  <p class="cs-label">Academic Personal Website</p>

  <h1 class="cs-name">Dr. Mohammed Alharbi</h1>
  <p class="cs-title">Assistant Professor</p>

  <hr class="cs-divider">

  <h2 class="cs-headline">Website Coming Soon</h2>

  <!--<p class="cs-sub">
    Please check back shortly — it will be worth the wait.
  </p>-->

  <div class="cs-links">
    <a href="/schedule/">Office Hours & Timetable</a>
    <a href="mailto:[mahharbi@taibahu.edu.sa]">Get in Touch</a>
    <!--<a href="https://scholar.google.com/citations?user=YOURID" target="_blank" rel="noopener">Google Scholar</a>
    <a href="https://orcid.org/0000-0000-0000-0000" target="_blank" rel="noopener">ORCID</a>-->
  </div>

</div>
