---
layout: single
permalink: /goals/
title: "Goals"
author_profile: false
---

<style>
.goalsPage {
  max-width: 1120px;
  margin: 120px auto 48px;
  padding: 0 24px;
}
.goalsGrid {
  display: grid;
  grid-template-columns: 300px 1fr;
  gap: 48px;
}
.goalsSidebar {
  position: sticky;
  top: 90px;
  align-self: start;
}
.sidebarCard {
  padding: 24px;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
  border-radius: 20px;
}
.goalHeader {
  margin: 0 0 24px;
}
.goalTitle {
  margin: 0 0 16px;
  font-size: 2.6rem;
  line-height: 1.05;
}
.goalIntro {
  margin: 0;
  color: rgba(255,255,255,0.86);
  font-size: 1rem;
  line-height: 1.7;
  max-width: 760px;
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
        <p class="profileName">Muhammad Shaheer</p>
        <p class="profileRole">Cloud and DevOps Engineer at AppLab Qatar</p>
        <p class="profileLocation">Islamabad, Pakistan</p>
      </section>
    </aside>

    <main>
      <header class="goalHeader">
        <h1 class="goalTitle">Goals</h1>
        <p class="goalIntro">A concise plan for what I want to build next, how I want to work, and the areas where I am investing the most time.</p>
      </header>

      <div class="goalCards">
        <section class="goalCard">
          <h2 class="goalSectionTitle">Short term</h2>
          <ul class="goalList">
            <li class="goalItem">Ship a clean personal blog page with live search and year filters.</li>
            <li class="goalItem">Keep infrastructure work reliable by improving deployment automation and monitoring.</li>
            <li class="goalItem">Write three pieces each quarter that clarify how I approach systems design and operations.</li>
          </ul>
        </section>

        <section class="goalCard">
          <h2 class="goalSectionTitle">Medium term</h2>
          <ul class="goalList">
            <li class="goalItem">Build more reusable components for cluster orchestration, security, and observability.</li>
            <li class="goalItem">Share work openly through blog posts, talks, and concise technical notes.</li>
            <li class="goalItem">Grow the engineering practice around operational resilience and hybrid cloud design.</li>
          </ul>
        </section>

        <section class="goalCard">
          <h2 class="goalSectionTitle">Long term</h2>
          <ul class="goalList">
            <li class="goalItem">Help shape systems that are easier to secure, easier to scale, and easier to maintain.</li>
            <li class="goalItem">Move from ad hoc solutions to architecture that feels intentional and predictable.</li>
            <li class="goalItem">Build work that supports teams, research, and production services without adding friction.</li>
          </ul>
        </section>
      </div>
    </main>
  </div>
</div>
