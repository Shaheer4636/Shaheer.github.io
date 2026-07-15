---
layout: single
permalink: /goals/
title: "Goals"
author_profile: false
---

<style>
.goalsPage {
  max-width: 1200px;
  margin: 120px auto 48px;
  padding: 0 24px;
}
.goalsGrid {
  display: grid;
  grid-template-columns: 280px 1fr;
  gap: 56px;
}
.goalsSidebar {
  position: sticky;
  top: 100px;
  align-self: start;
}
.sidebarCard {
  padding: 24px;
  border-radius: 20px;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
}
.sidebarName {
  margin: 0;
  font-size: 1.35rem;
  font-weight: 700;
}
.sidebarRole,
.sidebarLocation {
  margin: 10px 0 0;
  color: rgba(255,255,255,0.78);
  font-size: 0.95rem;
  line-height: 1.65;
}
.goalsMain {
  overflow: hidden;
}
.goalsHeader {
  margin: 0 0 32px;
}
.goalsTitle {
  margin: 0 0 24px;
  font-size: 3rem;
  line-height: 1.05;
}
.goalsIntro {
  margin: 0;
  color: rgba(255,255,255,0.86);
  font-size: 1rem;
  line-height: 1.65;
  max-width: 740px;
}
.goalCards {
  display: grid;
  gap: 20px;
}
.goalCard {
  padding: 24px;
  border-radius: 16px;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
}
.goalSectionTitle {
  margin: 0 0 14px;
  font-size: 1.25rem;
  font-weight: 700;
}
.goalList {
  margin: 0;
  padding: 0 0 0 20px;
  color: rgba(255,255,255,0.88);
  line-height: 1.75;
}
.goalItem {
  margin: 0 0 10px 0;
}
.goalItem:last-child {
  margin-bottom: 0;
}
@media screen and (max-width: 1024px) {
  .goalsGrid {
    grid-template-columns: 1fr;
  }
  .goalsSidebar {
    position: relative;
    top: 0;
  }
}
@media screen and (max-width: 768px) {
  .goalsPage {
    margin: 100px auto 32px;
  }
}
</style>

{% include base_path %}

<div class="goalsPage">
  <div class="goalsGrid">
    <aside class="goalsSidebar" aria-label="Profile information">
      <section class="sidebarCard">
        <p class="sidebarName">Muhammad Shaheer</p>
        <p class="sidebarRole">Cloud and DevOps Engineer at AppLab Qatar</p>
        <p class="sidebarLocation">Islamabad, Pakistan</p>
      </section>
    </aside>

    <main class="goalsMain">
      <header class="goalsHeader">
        <h1 class="goalsTitle">Goals</h1>
        <p class="goalsIntro">A clear, structured plan for what I want to build, how I want to work, and the outcomes I am moving toward.</p>
      </header>

      <div class="goalCards">
        <section class="goalCard">
          <h2 class="goalSectionTitle">Short term</h2>
          <ul class="goalList">
            <li class="goalItem">Finish a clean personal blog page with search and year filters that work together.</li>
            <li class="goalItem">Keep infrastructure stable by improving deployment automation and monitoring coverage.</li>
            <li class="goalItem">Write a short technical note every month on systems, operations, or team process.</li>
          </ul>
        </section>

        <section class="goalCard">
          <h2 class="goalSectionTitle">Medium term</h2>
          <ul class="goalList">
            <li class="goalItem">Build reusable patterns for distributed orchestration, security, and observability.</li>
            <li class="goalItem">Share useful work through writing and public notes rather than keeping it private.</li>
            <li class="goalItem">Grow the practice around hybrid cloud operations and platform reliability.</li>
          </ul>
        </section>

        <section class="goalCard">
          <h2 class="goalSectionTitle">Long term</h2>
          <ul class="goalList">
            <li class="goalItem">Design systems that are easier to secure, easier to run, and simpler to maintain.</li>
            <li class="goalItem">Move from quick fixes to architecture that feels predictable and intentional.</li>
            <li class="goalItem">Build work that supports research, teams, and production without adding friction.</li>
          </ul>
        </section>
      </div>
    </main>
  </div>
</div>
