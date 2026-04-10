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
      SetSwipe is a collaborative swim workout platform for planning practices
      faster. Swimmers can browse workouts, swipe through sets, build solo or
      group sessions, and track workout history.
    </p>
    <p>
      The system includes a mobile app, a Django backend, and a watchOS
      companion. Key features include profiles, friends, collaborative workout
      sessions, library filtering, and history tracking.
    </p>
    <p>
      SetSwipe was developed at the University of Utah as a 2025-2026 capstone
      project.
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
        <strong>SQLite</strong>
        <span>Local storage and sync-friendly mobile data access</span>
      </div>
    </div>

    <div class="diagram">
      <h2>System Snapshot</h2>
      <div class="diagram-flow">
        <div class="diagram-box">
          <strong>Mobile Client</strong><br>
          Login, library, swiping, group creation, profiles, workout history
        </div>
        <div class="diagram-arrow">&darr;</div>
        <div class="diagram-box">
          <strong>Django Services</strong><br>
          Accounts, friends, workouts, synchronization, collaborative session state
        </div>
        <div class="diagram-arrow">&darr;</div>
        <div class="diagram-box">
          <strong>Watch Companion</strong><br>
          Starts workouts, tracks reps and sets, and supports future live phone sync
        </div>
      </div>
    </div>
  </div>
</section>

<section class="card-grid">
  <article class="panel">
    <h2>The Problem</h2>
    <p>
      Swim workouts must balance time, distance, stroke, and effort, and that
      planning is repetitive when multiple swimmers are involved.
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
      The project uses React Native + Expo, Django, local storage, REST-style
      APIs, and a watchOS SwiftUI prototype.
    </p>
  </article>
</section>

<section class="photo-panel">
  <div class="photo-frame">
    <img src="{{ '/assets/images/setswipe-logo.png' | relative_url }}" alt="SetSwipe logo">
  </div>
  <div>
    <h2>Feature Highlights</h2>
    <ul class="list">
      <li>Workout library with recent items, filtering, search, and deletion support.</li>
      <li>Manual, automatic, and swipe-driven workout creation flows.</li>
      <li>Group workout setup with participant selection and collaborative lobby management.</li>
      <li>Profiles, friend requests, QR-based sharing, leaderboard hooks, and workout history.</li>
      <li>Watch companion scaffolding for set tracking and future phone-to-watch transfers.</li>
    </ul>
    <p class="caption">
      Current repo media includes the logo and team image. App screenshots and
      demo captures are not available yet.
    </p>
  </div>
</section>

<section class="panel">
  <h2>Development Context</h2>
  <p>
    The frontend README covers Expo setup on Windows and macOS, while the
    backend README covers Python setup, local configuration, migrations, and
    testing. Together they show SetSwipe is a real multi-surface system.
  </p>
  <p>
    This work was produced by a University of Utah capstone team during the
    2025-2026 academic year.
  </p>
</section>
