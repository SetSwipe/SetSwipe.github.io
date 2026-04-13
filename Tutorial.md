---
layout: default
title: Tutorial
permalink: /tutorial/
---

<section class="hero hero-compact">
  <div class="hero-copy">
    <p class="eyebrow">Quick Tutorial</p>
    <h1>How to use SetSwipe</h1>
    <p>
      Our app incorporates familiar UI patterns for quick and intuitive use.
      Choose the swimmer profile that best matches your experience level, then
      follow the matching walkthrough below.
    </p>
  </div>
</section>

<section class="tutorial-tabs-shell" aria-label="Tutorial profiles">
  <nav class="tutorial-tabs" aria-label="Tutorial profile navigation" role="tablist">
    <button class="tutorial-tab is-active" type="button" role="tab" aria-selected="true" aria-controls="beginner-swimmer-panel" id="beginner-swimmer-tab" data-target="beginner-swimmer-panel">
      Beginner Swimmer
    </button>
    <button class="tutorial-tab" type="button" role="tab" aria-selected="false" aria-controls="experienced-swimmer-panel" id="experienced-swimmer-tab" data-target="experienced-swimmer-panel">
      Experienced Swimmer
    </button>
    <button class="tutorial-tab" type="button" role="tab" aria-selected="false" aria-controls="social-swimmer-panel" id="social-swimmer-tab" data-target="social-swimmer-panel">
      Social Swimmer
    </button>
    <button class="tutorial-tab tutorial-tab-watch" type="button" role="tab" aria-selected="false" aria-controls="watch-tutorial-panel" id="watch-tutorial-tab" data-target="watch-tutorial-panel">
      <span class="tutorial-tab-icon" aria-hidden="true">⌚</span>
      <span class="tutorial-tab-label">Watch Tutorial</span>
    </button>
  </nav>

  <section class="tutorial-track is-active" id="beginner-swimmer-panel" role="tabpanel" aria-labelledby="beginner-swimmer-tab">
    <div class="tutorial-track-header">
      <p class="eyebrow">Profile 1</p>
      <h2>Beginner Swimmer</h2>
      <p>
        This path focuses on the simplest way to get moving: learn the app
        layout, build a first workout, and understand what each set means before
        you start collaborating with other swimmers.
      </p>
    </div>

    <div class="tutorial-media-list">
      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/preferences.GIF' | relative_url }}" alt="Preferences">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Select your swimming preferences</p>
          <p class="tutorial-media-detail">Upon signing up, a new user will be presented with a page to select their workout preferences. The application then targets workouts toward each user’s specific goals and skill level.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/settings.GIF' | relative_url }}" alt="Settings">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Change the view and complexity of the app</p>
          <p class="tutorial-media-detail">In the settings page, the user can toggle beginner mode, distance metric, UI transitions, and the theme of the app. “Beginner mode” simplifies pages and defines more complicated terminology, without reducing the functionality of the application.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/track.GIF' | relative_url }}" alt="View and Track">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">View and track your workouts</p>
          <p class="tutorial-media-detail">From your library, you can filter workouts by attribute, search for specific ones, or click on any of the workouts to view more details. From here you can record the workout, indicating that you have completed this workout. On certain pages, select the “?” icon to learn more about swimming terminology.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/automatic.GIF' | relative_url }}" alt="Automatic workout generation">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Automatic workout creation</p>
          <p class="tutorial-media-detail">The simplest way to generate a new workout is with the “automatic” generation. This allows you to enter the maximum time and/or distance that you want to swim for and what you want to focus on. A workout will then be generated that is tailored to your preferences.
          </p>
        </figcaption>
      </figure>
    </div>

  </section>

  <section class="tutorial-track" id="experienced-swimmer-panel" role="tabpanel" aria-labelledby="experienced-swimmer-tab" hidden>
    <div class="tutorial-track-header">
      <p class="eyebrow">Profile 2</p>
      <h2>Experienced Swimmer</h2>
      <p>
        This path is for swimmers who already know their pace and want to move
        quickly. It highlights faster navigation, workout customization, and
        efficient session planning.
      </p>
    </div>

    <div class="tutorial-media-list">
      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/manual.GIF' | relative_url }}" alt="Manual workout generation">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Manual workout creation</p>
          <p class="tutorial-media-detail">Creating a manual workout allows for maximal control and customization. Select this option from the create workout page, then fill it in with sets from your library or create a new custom set.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/newSet.GIF' | relative_url }}" alt="Add set screen">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Adding a set to a workout</p>
          <p class="tutorial-media-detail">When creating a custom set, fill in the number of repetitions, distance, stroke, style, interval, and effort. You can also group “steps” together to keep them connected in the workout.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/allSets.GIF' | relative_url }}" alt="All sets screen">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">View and edit your collection of sets</p>
          <p class="tutorial-media-detail">View the all sets page to delete sets, favorite them, and create new ones. Your favorite sets will show up more frequently when generating workouts by swiping or with automatic creation.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/watch.GIF' | relative_url }}" alt="Connect to watch">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Record a workout on your Apple watch</p>
          <p class="tutorial-media-detail">At the pool, click “Record workout” then “Track with watch” to view the workout live on your Apple watch. This application tracks your distance to keep you updated in real time about your pace, then sends the completed workout back to your phone to show in your history.</p>
        </figcaption>
      </figure>
    </div>

  </section>

  <section class="tutorial-track" id="social-swimmer-panel" role="tabpanel" aria-labelledby="social-swimmer-tab" hidden>
    <div class="tutorial-track-header">
      <p class="eyebrow">Profile 3</p>
      <h2>Social Swimmer</h2>
      <p>
        This path is built around workouts with friends. It covers inviting
        people, joining a shared session, and keeping the group workflow clear
        from planning through completion.
      </p>
    </div>

    <div class="tutorial-media-list">
      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/addFriend.GIF' | relative_url }}" alt="Add friend">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Add friends</p>
          <p class="tutorial-media-detail">There are multiple ways to send a friend request to another user on our application. Enter their username when prompted, scan their QR code, or add them from a friend’s profile.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/swipe.GIF' | relative_url }}" alt="Swiping workout generation">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Swipe workout generation</p>
          <p class="tutorial-media-detail">Create a workout collaboratively by selecting friends from the dropdown. Wait for everyone to join the lobby, then click “Start Swiping.” Each swimmer will swipe yes or no on sets they do or do not want to complete. The final workout will be created by selecting the most popular sets amongst participants.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/share.GIF' | relative_url }}" alt="Share a workout">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Share an existing workout</p>
          <p class="tutorial-media-detail">From the workout page, you can text, print, or share a workout with your friends directly through the app. When sending a workout through the app, you have the option to either send them a copy, or add them as a collaborator.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <img src="{{ '/assets/media/leaderboard.GIF' | relative_url }}" alt="Leaderboard screen">
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Compete with friends</p>
          <p class="tutorial-media-detail">From your profile, you can view the leaderboard to see the stats of your friends. Compare how far you and your friends have swum this week, this month, or of all time. Also, keep an how many consecutive weeks each friend has reached their target swimming frequency.</p>
        </figcaption>
      </figure>
    </div>

  </section>

  <section class="tutorial-track" id="watch-tutorial-panel" role="tabpanel" aria-labelledby="watch-tutorial-tab" hidden>
    <div class="tutorial-track-header">
      <p class="eyebrow">Profile 4</p>
      <h2>Watch Tutorial</h2>
      <p>
        The watch companion focuses on timing and session control. It is a
        lightweight support tool for swimmers who want quick feedback while a
        workout is underway.
      </p>
    </div>

    <div class="tutorial-media-list">
      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <span class="gif-placeholder">GIF 1</span>
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Start the session timer</p>
          <p class="tutorial-media-detail">Use the watch app to begin a session and keep the timer visible without pulling out your phone.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <span class="gif-placeholder">GIF 2</span>
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Track reps and sets</p>
          <p class="tutorial-media-detail">Monitor reps, set progression, and the current interval so you can stay focused on the workout itself.</p>
        </figcaption>
      </figure>

      <figure class="tutorial-media-card">
        <div class="gif-frame gif-frame-portrait">
          <span class="gif-placeholder">GIF 3</span>
        </div>
        <figcaption>
          <p class="tutorial-media-caption">Pause or end cleanly</p>
          <p class="tutorial-media-detail">Pause, resume, or end the session from the wrist when you need a quick break or a finished workout.</p>
        </figcaption>
      </figure>
    </div>

  </section>
</section>

<script>
  (function () {
    var tabs = Array.prototype.slice.call(document.querySelectorAll(".tutorial-tab[role='tab']"));
    var panels = Array.prototype.slice.call(document.querySelectorAll(".tutorial-track[role='tabpanel']"));

    if (!tabs.length || !panels.length) {
      return;
    }

    var activateTab = function (tab) {
      var targetId = tab.getAttribute("data-target");

      tabs.forEach(function (currentTab) {
        var isSelected = currentTab === tab;
        currentTab.classList.toggle("is-active", isSelected);
        currentTab.setAttribute("aria-selected", isSelected ? "true" : "false");
        currentTab.setAttribute("tabindex", isSelected ? "0" : "-1");
      });

      panels.forEach(function (panel) {
        var isActive = panel.id === targetId;
        panel.classList.toggle("is-active", isActive);
        panel.hidden = !isActive;
      });
    };

    tabs.forEach(function (tab) {
      tab.addEventListener("click", function () {
        activateTab(tab);
      });

      tab.addEventListener("keydown", function (event) {
        var index = tabs.indexOf(tab);
        var nextIndex = null;

        if (event.key === "ArrowRight" || event.key === "ArrowDown") {
          nextIndex = (index + 1) % tabs.length;
        } else if (event.key === "ArrowLeft" || event.key === "ArrowUp") {
          nextIndex = (index - 1 + tabs.length) % tabs.length;
        } else if (event.key === "Home") {
          nextIndex = 0;
        } else if (event.key === "End") {
          nextIndex = tabs.length - 1;
        } else {
          return;
        }

        event.preventDefault();
        tabs[nextIndex].focus();
        activateTab(tabs[nextIndex]);
      });
    });

    activateTab(tabs[0]);
  })();
</script>
