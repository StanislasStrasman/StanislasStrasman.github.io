---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
redirect_from:
  - /talks.html
---

{% include base_path %}



<style>
.talk-card {
  border: 1px solid #e6e6e6;
  border-radius: 12px;
  padding: 18px 22px;
  margin: 18px 0 26px;
  background: #fff;
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.talk-card:hover {
  box-shadow: 0 3px 12px rgba(0,0,0,0.08);
  transform: translateY(-2px);
}
.talk-title {
  font-weight: 600;
  font-size: 1.05rem;
  margin-bottom: 4px;
}
.talk-meta {
  color: #555;
  font-size: 0.95rem;
  margin-top: 4px;
}
.talk-venue {
  color: #333;
  font-weight: 500;
}
.talk-summary {
  font-size: 0.94rem;
  color: #444;
  margin-top: 8px;
  line-height: 1.55;
}
.talk-summary strong {
  color: #222;
}
.talk-links {
  margin-top: 10px;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 10px;
}
.talk-links a {
  text-decoration: none;
  border: 1px solid #ddd;
  padding: 6px 10px;
  border-radius: 8px;
  font-size: 0.9rem;
  color: #333;
}
.talk-links a:hover {
  background: #f7f7f7;
}
.talk-summary {
  font-size: 0.94rem;
  color: #444;
  margin-top: 8px;
  line-height: 1.55;
  text-align: justify;
  text-justify: inter-word;
}

.note-inline {
  font-size: 0.85rem;
  color: #777;
  font-style: italic;
  margin-left: 4px;
}
@media (max-width: 560px) {
  .talk-card { padding: 14px; }
}
</style>

## Upcoming and Past Talks

<div class="talk-card">
  <p class="talk-title"><a href="https://jds2025.sciencesconf.org/" target="_blank">Journées de Statistique (JdS) 2025</a></p>
  <p class="talk-meta"> Université de Marseille — May 2025</p>
  <p class="talk-summary">
    <strong>Summary:</strong> We present ongoing work on conditional sampling in score-based generative models (SGMs). The talk discusses two approaches: modifying the training procedure or keeping a score trained on the joint distribution while adapting the sampling process. In particular, we show how Sequential Monte Carlo (SMC) methods can be integrated within the SGM framework to achieve conditional sampling. We conclude by outlining a promising directions toward deriving theoretical upper bounds for conditional sampling with SMC methods.  </p>
  <div class="talk-links">
    <a href="/files/slides_jds2025.pdf">Slides</a>
  </div>
</div>

<div class="talk-card">
  <p class="talk-title"><a href="https://imaging-in-paris.github.io/" target="_blank">Imaging in Paris Seminar</a></p>
  <p class="talk-meta">Institut Henri Poincaré, Paris — December 2024</p>
  <p class="talk-summary">
    <strong>Summary:</strong> Starting from an introduction to the DDPM algorithm, we derive its equivalent SDE formulation as a continuous-time limit. We then discuss several theoretical results related to this SDE framework. Building on this framework, we analyze the role of noise schedules in score-based generative models. The analysis combines theoretical insights with numerical illustrations on both synthetic data and real image datasets.
      </p>
  <div class="talk-links">
    <a href="/files/slides_imaging.pdf">Slides</a>
    <span class="note-inline">⚠️ Contains animations — use Adobe Acrobat Reader or equivalent.</span>
  </div>
</div>

<div class="talk-card">
  <p class="talk-title"><a href="https://sites.google.com/view/all-about-that-bayes/" target="_blank">All About That Bayes</a></p>
  <p class="talk-meta">Sorbonne Center for Artificial Intelligence (SCAI), Paris — November 2024</p>
  <p class="talk-summary">
    <strong>Summary:</strong> Starting from an introduction to the DDPM algorithm, we derive its equivalent SDE formulation as a continuous-time limit. We then discuss several theoretical results related to this SDE framework. Building on this framework, we analyze the role of noise schedules in score-based generative models. The analysis combines theoretical insights with numerical illustrations on both synthetic data and real image datasets.
  </p>
  <div class="talk-links">
    <a href="/files/slides_bayes.pdf">Slides</a>
    <span class="note-inline">⚠️ Contains animations — use Adobe Acrobat Reader or equivalent.</span>
  </div>
</div>


<div class="talk-card">
  <p class="talk-title"><a href="https://jds2024.sciencesconf.org/?lang=fr" target="_blank">Journées de Statistique (JdS) 2024</a></p>
  <p class="talk-meta">Université de Bordeaux— May 2024</p>
  <p class="talk-summary">
    <strong>Summary:</strong> We present score-based generative models (SGMs) and identify their three main sources of error: mixing, approximation, and discretization. We then derive upper bounds on the sampling error under various metrics and illustrate, through numerical experiments, the impact of the noise schedule on generation quality.
  </p>
  <div class="talk-links">
    <a href="/files/slides_jds2024.pdf">Slides</a>
  </div>
</div>

<!-- Template for future talks -->
<!--
<div class="talk-card">
  <p class="talk-title"><a href="https://example.com" target="_blank">Conference Name</a></p>
  <p class="talk-meta">City, Country — YEAR</p>
  <p class="talk-summary"><strong>Summary:</strong> Short description (1–2 sentences).</p>
  <div class="talk-links">
    <a href="/files/slides_example.pdf">Slides</a>
    <span class="note-inline">⚠️ Optional note</span>
  </div>
</div>
-->
