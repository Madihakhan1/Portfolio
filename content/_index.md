---
title: ""
---

<div class="homepage-hero">
  <span class="home-kicker">Madiha's Portfolio</span>
  <h1>Course Portfolio</h1>

  <p class="home-intro">
    A collection of assignments, reflections, and project notes from my course in AI-driven applications.
    The site brings my work together in one place and shows how my understanding develops from week to week.
  </p>

  <div class="home-actions">
    {{< button href="/Portfolio/posts/" >}}Browse all posts{{< /button >}}
    {{< button href="posts/03-RAG-demo-reflection.md" >}}Latest project{{< /button >}}
  </div>

  <div class="home-chip-row">
    <span class="home-chip">AI-driven applications</span>
    <span class="home-chip">RAG</span>
    <span class="home-chip">Reflections and coursework</span>
  </div>
</div>

## Featured work

<div class="portfolio-grid">
  <a class="portfolio-card" href='{{< ref "posts/01-intro-aida-portfolio.md" >}}'>
    <span class="portfolio-card-title">AIDA Portfolio</span>
    <p>An introduction to the portfolio and my expectations for the course.</p>
  </a>
  <a class="portfolio-card" href='{{< ref "posts/02-intro-RAG-reflection.md" >}}'>
    <span class="portfolio-card-title">RAG Reflection</span>
    <p>A short reflection on retrieval-augmented generation and why it matters.</p>
  </a>
  <a class="portfolio-card" href='{{< ref "posts/03-RAG-demo-reflection.md" >}}'>
    <span class="portfolio-card-title">RAG Demo</span>
    <p>A summary of my Dify chatbot project and what I learned from building it.</p>
  </a>
</div>
