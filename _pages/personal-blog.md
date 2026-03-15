---
layout: archive
permalink: /personal-blog/
title: "Personal Blog"
author_profile: true
---

<style>
.personal-blog-hero {
  background: linear-gradient(135deg, var(--global-base-color) 0%, #1a5a6e 100%);
  border-radius: 12px;
  padding: 2.5rem 2rem;
  margin-bottom: 2.5rem;
  color: #fff;
  box-shadow: 0 4px 24px rgba(0,0,0,0.12);
}
.personal-blog-hero h2 {
  color: #fff;
  font-size: 1.6em;
  margin-top: 0;
  margin-bottom: 0.5rem;
  border: none;
}
.personal-blog-hero p {
  color: rgba(255,255,255,0.88);
  font-size: 1.05em;
  margin: 0;
  line-height: 1.7;
}
.personal-blog-hero .hero-icon {
  font-size: 2.2rem;
  margin-bottom: 0.75rem;
  display: block;
}
.blog-section-title {
  font-size: 1.15em;
  font-weight: 700;
  color: var(--global-base-color);
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-bottom: 1.2rem;
  padding-bottom: 0.4rem;
  border-bottom: 2px solid var(--global-base-color);
  display: inline-block;
}
.personal-blog-empty {
  background: var(--global-footer-bg-color);
  border-left: 4px solid var(--global-base-color);
  border-radius: 0 8px 8px 0;
  padding: 1.5rem 1.75rem;
  color: var(--global-text-color);
  font-size: 0.97em;
  margin-top: 1rem;
}
.personal-blog-empty strong {
  color: var(--global-base-color);
}
</style>

{% include base_path %}

<div class="personal-blog-hero">
  <span class="hero-icon">✍️</span>
  <h2>Thoughts, Stories & Reflections</h2>
  <p>
    A personal corner of the internet where I write beyond the research papers —
    about life, learning, travel, ideas that excite me, and the moments worth remembering.
  </p>
</div>

<span class="blog-section-title">Latest Posts</span>

{% if site.personal_blog.size > 0 %}
  {% capture written_year %}'None'{% endcapture %}
  {% for post in site.personal_blog reversed %}
    {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
    {% if year != written_year %}
      <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
      {% capture written_year %}{{ year }}{% endcapture %}
    {% endif %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <div class="personal-blog-empty">
    <strong>Coming soon!</strong> Posts are on their way — check back soon for stories, reflections, and personal musings.
  </div>
{% endif %}
