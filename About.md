---
layout: default
title: About
permalink: /
---

<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Capstone Project</p>
    <h1>SetSwipe helps swimmers build workouts faster and together.</h1>
    <p>
      Swimmers who are transitioning from a structured environment such as a competitive high school team to a more casual environment swimming on their own often face challenges in maintaining engagement with the sport. The loss of the team environment and daily coaching can lead to a decline in motivation and difficulty in creating effective workouts. Current fitness apps lack the tools for a swimming-focused audience, and fail to address the social aspects of swimming. This project is a mobile application designed to bridge this gap for swimmers with no coach.
    </p>
    <p>
      This application provides a platform for swimmers to build, share, and schedule workouts, whether training solo or collaborating with friends and former teammates. The main feature of this app is a swim set building interface similar to how a music app like Spotify allows users to build playlists. It will also have a scheduling tool which simplifies coordinating times to swim with friends.
    </p>
    <p>
      While providing a useful set building platform for solo swimmers, this solution also mitigates the common social obstacles swimmers often face when trying to swim individually. Merging the creation of workouts with social coordination recreates the structured dynamic of a team environment. This solution provides a novel, user centric approach to solving the problems of a niche athletic community, demonstrating the ability for technology to support swimmers in their long term health and wellness.
    </p>
    <div class="button-row">
      <a class="button button-primary" href="{{ '/tutorial/' | relative_url }}">See How It Works</a>
      <a class="button button-secondary" href="{{ '/team/' | relative_url }}">Meet the Team</a>
    </div>
  </div>

  <div class="hero-visual">
    <div class="mini-stat-grid">
      <div class="mini-stat">
        <strong>Expo</strong>
        <span>Cross-platform React Native app for core user workflows</span>
      </div>
      <div class="mini-stat">
        <strong>Django</strong>
        <span>API-driven backend for accounts, workouts, friends, and collab sessions</span>
      </div>
      <div class="mini-stat">
        <strong>watchOS</strong>
        <span>Companion interface for workout timing and set progression</span>
      </div>
      <div class="mini-stat">
        <strong>PostgreSQL</strong>
        <span>Persistent relational data layer for the app’s core records and syncing</span>
      </div>
    </div>

    <div class="photo-frame hero-library-frame">
      <img class="hero-library-image" src="{{ '/assets/media/library.PNG' | relative_url }}" alt="SetSwipe workout library">
    </div>

  </div>

</section>

<section class="card-grid">
  <article class="panel">
    <h2>The Problem</h2>
    <p>
      Swimmers practicing outside of a structured team environment suffer from
      burnout and struggle to create engaging, yet challenging workouts.
    </p>
  </article>
  <article class="panel">
    <h2>The Solution</h2>
    <p>
      SetSwipe turns planning into a guided flow with manual, automatic, and
      swipe-based workout creation.
    </p>
  </article>
  <article class="panel">
    <h2>Core Technologies</h2>
    <p>
      The project uses React Native + Expo, Django, PostgreSQL, REST-style APIs,
      and a watchOS SwiftUI prototype.
    </p>
  </article>
</section>
