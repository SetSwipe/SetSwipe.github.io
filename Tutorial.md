---
layout: default
title: Tutorial
permalink: /tutorial/
---

<section class="hero hero-compact">
  <div class="hero-copy">
    <p class="eyebrow">Quick Tutorial</p>
    <h1>How a user would work with SetSwipe.</h1>
    <p>
      This page uses the project READMEs and current app structure to summarize
      how SetSwipe is installed, launched, and used. Videos and screen
      recordings are not available yet.
    </p>
  </div>
</section>

<section class="steps-grid">
  <article class="tutorial-step">
    <h2>1. Prepare the environment</h2>
    <p>
      Install Git and Node.js first. The frontend README also requires Expo CLI,
      plus Android Studio on Windows or Xcode on macOS.
    </p>
    <ul class="list">
      <li>Windows flow includes Java, Python, Expo dependencies, and Android emulator setup.</li>
      <li>macOS flow includes Xcode command line tools, Simulator setup, and Expo startup.</li>
      <li>Both flows use <code>npm install</code> and <code>npx expo start</code> to launch the mobile app.</li>
    </ul>
  </article>

  <article class="tutorial-step">
    <h2>2. Start the backend</h2>
    <p>
      The Django README covers backend setup: create a virtual environment,
      install <code>requirements.txt</code>, generate local settings, run migrations,
      and start the server.
    </p>
    <ul class="list">
      <li>Activate the Python environment.</li>
      <li>Run <code>pip install -r requirements.txt</code>.</li>
      <li>Refresh local hosts and update the frontend API base URL.</li>
      <li>Run <code>python manage.py migrate</code> and <code>python manage.py runserver 0.0.0.0:8000</code>.</li>
    </ul>
  </article>

  <article class="tutorial-step">
    <h2>3. Sign in and reach the library</h2>
    <p>
      The mobile app uses token-based login, then routes users into the workout
      library for browsing, search, and filtering.
    </p>
  </article>

  <article class="tutorial-step">
    <h2>4. Create a workout</h2>
    <p>
      The workout creation screen supports solo and group modes with swipe-based,
      automatic, or manual creation. Group mode also lets the creator select
      friends first.
    </p>
  </article>

  <article class="tutorial-step">
    <h2>5. Run a collaborative swiping session</h2>
    <p>
      In group mode, invited users join a lobby that shows workout metadata and
      participants. Once the host starts, users swipe through sets until the
      workout is finalized.
    </p>
  </article>

  <article class="tutorial-step">
    <h2>6. Review history and profile data</h2>
    <p>
      After a workout is created or completed, users can review workout details,
      history, profile data, friends, and related profile features.
    </p>
  </article>
</section>

<section class="coming-soon">
  <h2>Watch tutorial status</h2>
  <p>
    The watch README describes a basic SwiftUI companion app for timers, reps,
    set progression, pause or resume, and ending a session. A fuller watch
    tutorial is still coming soon.
  </p>
</section>
