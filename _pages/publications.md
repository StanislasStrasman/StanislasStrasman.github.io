---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
mathjax: true
---

{% include base_path %}

<!-- GitHub icon definition -->
<svg xmlns="http://www.w3.org/2000/svg" style="display:none;">
  <symbol id="icon-github" viewBox="0 0 16 16" fill="black">
    <path d="M8 0C3.58 0 0 3.73 0 8.33c0 3.68 2.29 
    6.8 5.47 7.9.4.08.55-.18.55-.4 0-.2-.01-.86-.01-1.56
    -2.01.38-2.53-.52-2.69-1-.09-.23-.48-.97-.82-1.17
    -.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82
    .72 1.21 1.87.87 2.33.66.07-.53.28-.87.51-1.07
    -1.78-.2-3.64-.93-3.64-4.14 0-.92.31-1.67.82-2.26
    -.08-.2-.36-1.02.08-2.12 0 0 .67-.22 2.2.86A7.42 7.42 0 018 
    3.87c.68.003 1.37.09 2.01.26 1.53-1.09 2.2-.86 2.2-.86
    .44 1.1.16 1.92.08 2.12.51.59.82 1.34.82 2.26
    0 3.22-1.87 3.93-3.65 4.13.29.25.54.73.54 1.48
    0 1.07-.01 1.93-.01 2.19 0 .22.15.48.55.4
    A8.34 8.34 0 0016 8.33C16 3.73 12.42 0 8 0z"/>
  </symbol>
</svg>

<style>
#research-papers {
  margin-top: 1rem;
}
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
  aspect-ratio: 10 / 3;
  object-position: center;
  display: block;
  margin: 0 auto;
  object-fit: contain; /* preserve the complete illustration in a shared banner area */
  background: #fff;
  border-bottom: 1px solid #ddd;
}
.pub-banner-link {
  display: block;
}
.pub-content {
  padding: 20px 24px;
}
.pub-title {
  position: relative;
  padding-left: 0.85em;
  font-weight: 700;
  font-size: 1.2rem;
  margin-bottom: 8px;
  color: #222;
}
.pub-title::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.55em;
  width: 0.3em;
  height: 0.3em;
  border-radius: 50%;
  background: #000;
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
  text-align: justify;
  line-height: 1.6;
  margin: 12px 0;
  color: #333;
}

/* Button row */
.pub-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 10px;
}

/* Rectangular buttons, all same style */
.pub-actions a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 6px;
  text-decoration: none;
  border: 1px solid #ccc;
  padding: 6px 14px;
  border-radius: 6px;
  font-size: 0.9rem;
  color: #333;
  background: #fff;
  transition: background 0.15s ease, border-color 0.15s ease;
}
.pub-actions a:hover {
  background: #f4f4f4;
  border-color: #bfbfbf;
}

/* Icon inside Code button */
.pub-actions a svg {
  width: 16px;
  height: 16px;
}
</style>

<h2 id="research-papers">Research papers</h2>

<!-- SGD paper -->
<div class="pub-card">
  <img src="/images/sgd_network_banner.png" alt="Overparameterized ReLU network and stochastic gradient descent trajectory on loss contours" width="2400" height="720" loading="lazy">
  <div class="pub-content">
    <p class="pub-title">Non-asymptotic Convergence of Stochastic Gradient Descent in Score-based Generative Models</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Sobihan Surendran, Sylvain Le Corff (2026)
      <br><span class="pub-venue">Preprint</span>
    </p>
    <p class="pub-summary">
    We analyze stochastic gradient descent for weighted denoising score matching. We derive nonconvex optimization bounds for general score parameterizations and score-approximation guarantees along training for overparameterized two-layer ReLU networks. For this architecture, these learning guarantees are combined with a Wasserstein-2 sampling analysis that accounts for early stopping, initialization, score approximation, and discretization errors, providing a way to study how these different error terms interact in the final generation bound.
    </p>
    <p class="pub-actions">
      <a href="https://arxiv.org/abs/2607.04775">Paper</a>
    </p>
  </div>
</div>

<!-- SMC paper -->
<div class="pub-card">
  <img src="/images/smc_sampling_banner.png" alt="Conditional sampling geometry and particle error with bias plateaus" loading="lazy">
  <div class="pub-content">
    <p class="pub-title">Theoretical Guarantees for SMC-Guided Diffusion Sampling</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Gabriel Victorino Cardoso, Sylvain Le Corff, Vincent Lemaire, Antonio Ocello (2026)
      <br><span class="pub-venue">Preprint</span>
    </p>
    <p class="pub-summary">
      We derive non-asymptotic guarantees for conditioning pretrained diffusion models with Sequential Monte Carlo (SMC). Using forward-smoothing kernels, we separate finite-particle fluctuations from errors in initialization, score approximation, numerical integration, and guidance design. Applied to several SMC-guided samplers, the framework explains how these errors propagate and why bias can persist even with infinitely many particles.
    </p>
    <p class="pub-actions">
      <a href="https://arxiv.org/abs/2607.04780">Paper</a>
      <a href="https://github.com/StanislasStrasman/diffusion-guided-smc-numerics">
        Code
        <svg aria-hidden="true"><use href="#icon-github"/></svg>
      </a>
    </p>
  </div>
</div>


<div class="pub-card">
  <img src="/images/img_forgetting.png" alt="Banner: On Forgetting and Stability of Score-based Generative Models" loading="lazy">

  <div class="pub-content">
    <p class="pub-title">On Forgetting and Stability of Score-based Generative Models</p>

    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Gabriel Cardoso, Sylvain Le Corff, Vincent Lemaire, Antonio Ocello (2026)
      <br><span class="pub-venue">Preprint</span>
    </p>

    <p class="pub-summary">
We study how reverse-time dynamics in score-based generative models forget perturbations along the sampling trajectory. Using Harris-type arguments based on Lyapunov drift and localized minorization, we establish contraction in weighted total variation and quantify the propagation of initialization, score-approximation, and discretization errors. This provides a stability perspective in which errors introduced earlier in the reverse dynamics can have a reduced influence on the final generated distribution.
    </p>
    <p class="pub-actions">
      <a href="https://arxiv.org/abs/2601.21868">Paper</a>
    </p>
  </div>
</div>


<div class="pub-card">
  <img src="/images/cdl_position_velocity_banner.png" alt="Illustration of cld" loading="lazy">
  <div class="pub-content">
    <p class="pub-title">Wasserstein Convergence of Critically Damped Langevin Diffusions</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>, Sobihan Surendran, Claire Boyer, Sylvain Le Corff, Vincent Lemaire, Antonio Ocello (2025)
      <br><span class="pub-venue">The Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)</span>
    </p>
    <p class="pub-summary">
We study the convergence guarantees of Critically Damped Langevin Diffusions (CLDs) for score-based generative modeling and provide, to the best of our knowledge, the first Wasserstein-2 upper bound for kinetic SGMs by analyzing the Lipschitz regularity of a modified score function. Our study also motivates the introduction of a noise–control hyperparameter that restores ellipticity by injecting noise across the entire state space. This choice has a measurable impact on generation quality in synthetic datasets.  
  </p>
    <p class="pub-actions">
      <a href="https://arxiv.org/abs/2511.02419">Paper</a>
      <a href="https://openreview.net/forum?id=a7bisLzORM">OpenReview</a>
       <a href="https://github.com/StanislasStrasman/CLD">
        Code
        <svg aria-hidden="true"><use href="#icon-github"/></svg>
      </a>
            <a href="/files/poster_neurips.pdf">Poster</a>
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
We study how the choice of the noise schedule impacts the generation error in Score-based Generative Models (SGMs). We derive explicit upper bounds for both the Kullback–Leibler divergence and the Wasserstein-2 distance between the generated and target distributions, highlighting their dependence on model hyperparameters and regularity of the data distribution. Theoretical findings are supported by numerical experiments on synthetic and real datasets.
    </p>
    <p class="pub-actions">
      <a href="https://arxiv.org/abs/2402.04650">Paper</a>
      <a href="https://openreview.net/forum?id=BlYIPa0Fx1">OpenReview</a>
      <a href="https://github.com/StanislasStrasman/Noise_Schedule_for_Score-based_Generative_Models">
        Code
        <svg aria-hidden="true"><use href="#icon-github"/></svg>
      </a>
    </p>
  </div>
</div>

<section aria-labelledby="notes-and-expository-writing">
  <h2 id="notes-and-expository-writing">Notes and expository writing</h2>

<div class="pub-card">
  <a class="pub-banner-link" href="/files/diffusion_note_ald_vs_sde.pdf" aria-label="View the ALD and SDE comparison figure (PDF)">
    <img src="/images/diffusion_note_ald_vs_sde_banner.webp" alt="Annealed Langevin dynamics and SDE interpolation, with sample paths and marginal densities from high to low noise" width="2200" height="957" loading="lazy">
  </a>
  <div class="pub-content">
    <p class="pub-title">A Stochastic Analysis Perspective on Diffusion Models</p>
    <p class="pub-meta">
      <strong>Stanislas Strasman</strong>
      <br><span class="pub-venue">Expository note</span>
    </p>
    <p class="pub-summary">
  We trace the probabilistic ideas behind diffusion models, from Langevin sampling and score matching to Gaussian smoothing, annealed Langevin dynamics, and reverse-time SDEs. A path-space perspective clarifies what diffusion time reversal requires beyond matching one-time marginals, with a martingale-based proof sketch. We then connect this idealized construction to practical training and sampling    </p>
    <p class="pub-actions">
      <a href="https://hal.science/hal-05788636">Paper</a>
    </p>
  </div>
</div>
</section>

{% if site.author.googlescholar %}
You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- Duplicate the block above for more publications; just change image, title, authors, venue, links, and summary. -->
