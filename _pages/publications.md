---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
mathjax: true
---


{% include base_path %}

<style>
.pub-card {
  display: flex;
  flex-direction: column;
  overflow: hidden;
  border: 1px solid #e6e6e6;
  border-radius: 14px;
  margin: 32px 0;
  background: #fff;
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.pub-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 14px rgba(0, 0, 0, 0.08);
}
.pub-card img {
  width: 95%;
  height: auto;
  object-position: center center; /* centers image crop */
   display: block;
  margin: 0 auto;
  object-fit: cover;       /* crops intelligently while keeping proportions */
  border-bottom: 1px solid #ddd;
}
.pub-content {
  padding: 20px 24px;
}
.pub-title {
  font-weight: 700;
  font-size: 1.2rem;
  margin-bottom: 8px;
  color: #222;
}
.pub-meta {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 8px;
}
.pub-venue {
  font-style: italic;
  color: #777;
}
.pub-summary {
  font-size: 0.95rem;
  line-height: 1.6;
  margin: 12px 0;
  color: #333;
}
.pub-actions a {
  text-decoration: none;
  border: 1px solid #ccc;
  padding: 6px 10px;
  border-radius: 6px;
  margin-right: 8px;
  font-size: 0.9rem;
  color: #333;
}
.pub-actions a:hover {
  background: #f4f4f4;
}
</style>

<div class="pub-card">
  <img src="/images/cdl_position_velocity_banner.png" alt="Illustration of cld" loading="lazy">
  <div class="pub-content">
    <p class="pub-title">Wasserstein Convergence of Critically Damped Langevin Diffusions</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Sobihan Surendran, Claire Boyer, Sylvain Le Corff, Vincent Lemaire, Antonio Ocello (2025)
      <br><span class="pub-venue">The Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)</span>
    </p>
    <p class="pub-summary">
We establish convergence gaurantee for CLD diffusion models.
    </p>
    <p class="pub-actions">
      <a href="https://openreview.net/forum?id=BlYIPa0Fx1">Paper</a>
      <a href="https://github.com/StanislasStrasman/Noise_Schedule_for_Score-based_Generative_Models">Code</a>
    </p>
  </div>
</div>

<div class="pub-card">
  <img src="/images/ou_noise_schedule_hoelig.png" alt="Illustration of noise schedule analysis" loading="lazy">
  <div class="pub-content">
    <p class="pub-title">An Analysis of the Noise Schedule for Score-based Generative Models</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Antonio Ocello, Claire Boyer, Sylvain Le Corff, Vincent Lemaire (2025)
      <br><span class="pub-venue">Transactions on Machine Learning Research (TMLR)</span>
    </p>
    <p class="pub-summary">
We study how the choice of the noise schedule impacts the generation error in Score-based Generative Models (SGMs). We derive explicit upper bounds for both the Kullback–Leibler divergence and the Wasserstein-2 distance between the generated and target distributions, highlighting their dependence on model hyperparameters and regularity of the data distribution. Theoretical findings are supported by numerical experiments on synthetic and real datasets
          </p>
    <p class="pub-actions">
      <a href="https://openreview.net/forum?id=BlYIPa0Fx1">Paper</a>
      <a href="https://github.com/StanislasStrasman/Noise_Schedule_for_Score-based_Generative_Models">Code</a>
    </p>
  </div>
</div>

{% if site.author.googlescholar %}
You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- Duplicate the block above for more publications; just change image, title, authors, venue, links, and summary. -->


