---
layout: default
title: AfriLang AI 2026
permalink: /beta/
last_modified_date: August 17th, 2026
---

<style>
  :root {
    --brand-primary: #3F2B56;    /* Deep Eggplant Purple from banner title */
    --brand-accent: #F2A900;     /* Sunbird Warm Gold */
    --brand-orange: #E65100;     /* Vibrant Sun Orange */
    --brand-dark: #1E1B26;
    --brand-bg: #FDFBF7;         /* Warm clean paper tone */
    --card-bg: #FFFFFF;
    --border-color: #EADFD7;
  }

  body {
    background-color: var(--brand-bg);
    color: var(--brand-dark);
  }

  /* Hero Section */
  .hero-banner {
    background: linear-gradient(135deg, #3F2B56 0%, #251736 100%);
    color: #FFFFFF;
    padding: 50px 35px;
    border-radius: 16px;
    margin-bottom: 40px;
    position: relative;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(63, 43, 86, 0.15);
  }

  .hero-banner::after {
    content: "";
    position: absolute;
    top: -50px;
    right: -50px;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(242, 169, 0, 0.25) 0%, rgba(242, 169, 0, 0) 70%);
  }

  .hero-title {
    font-size: 2.6rem;
    font-weight: 800;
    color: #FFFFFF !important;
    margin-bottom: 8px;
    letter-spacing: -0.5px;
  }

  .hero-subtitle {
    font-size: 1.35rem;
    color: var(--brand-accent);
    font-weight: 500;
    margin-bottom: 18px;
  }

  .hero-tagline {
    font-size: 1.05rem;
    line-height: 1.6;
    max-width: 800px;
    color: #E0D7E8;
    margin-bottom: 0;
  }

  /* Section Headings */
  h2, h3 {
    color: var(--brand-primary);
    font-weight: 700;
    position: relative;
    padding-bottom: 8px;
  }

  h2::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;
    width: 45px;
    height: 3px;
    background: var(--brand-orange);
    border-radius: 2px;
  }

  /* Key Dates & Timeline Grid */
  .dates-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 16px;
    margin: 25px 0 35px 0;
  }

  .date-card {
    background: var(--card-bg);
    border: 1px solid var(--border-color);
    border-top: 4px solid var(--brand-accent);
    border-radius: 10px;
    padding: 18px 20px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.04);
  }

  .date-card.highlight {
    border-top-color: var(--brand-orange);
    background: #FFF9F5;
  }

  .date-label {
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    color: #776E65;
    font-weight: 600;
  }

  .date-val {
    font-size: 1.15rem;
    font-weight: 700;
    color: var(--brand-primary);
    margin-top: 4px;
  }

  /* Callout box */
  .notice-card {
    background: #F4EFF8;
    border-left: 5px solid var(--brand-primary);
    padding: 18px 22px;
    border-radius: 0 10px 10px 0;
    margin: 25px 0;
  }

  /* Profiles & Cards */
  .profile-grid {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin: 25px 0;
  }

  .chair-card {
    display: flex;
    align-items: flex-start;
    gap: 22px;
    background: var(--card-bg);
    border: 1px solid var(--border-color);
    border-radius: 12px;
    padding: 22px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
  }

  .chair-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid var(--brand-accent);
    flex-shrink: 0;
  }

  .chair-info strong {
    font-size: 1.2rem;
    color: var(--brand-primary);
  }

  .chair-info em {
    color: var(--brand-orange);
    font-style: normal;
    font-weight: 600;
    font-size: 0.95rem;
  }

  .chair-info p {
    margin-top: 10px;
    line-height: 1.6;
    color: #443E38;
  }

  /* Committee Pills */
  .committee {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 14px;
    margin-top: 20px;
  }

  .committee-member {
    background: var(--card-bg);
    padding: 14px 18px;
    border-radius: 8px;
    border: 1px solid var(--border-color);
    font-size: 0.95rem;
  }

  .committee-member strong {
    color: var(--brand-primary);
  }

  /* CTA Buttons */
  .btn-submit {
    display: inline-block;
    background: var(--brand-primary);
    color: #FFFFFF !important;
    padding: 12px 26px;
    font-weight: 600;
    border-radius: 8px;
    text-decoration: none;
    transition: background 0.2s;
    margin-top: 10px;
  }

  .btn-submit:hover {
    background: var(--brand-orange);
    color: #FFFFFF !important;
  }

  @media (max-width: 700px) {
    .chair-card {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  }
</style>

<div class="hero-banner">
  <div class="hero-title">AfriLang AI 2026</div>
  <div class="hero-subtitle">AI for African Languages Conference</div>
  <p class="hero-tagline">
    Unlock the power of East African languages: Innovate, connect, and build inclusive language technology for tomorrow.
  </p>
</div>

The field of Natural Language Processing (NLP) has made remarkable strides, yet a significant disparity persists in the resources available for different languages. African languages, in particular, are largely underrepresented in NLP research and development, leading to a critical "low-resource" challenge. 

This workshop brings together NLP researchers, practitioners, and industry teams from across Africa—with a focus on the East African region—to foster collaboration, share cutting-edge research, and accelerate inclusive language technologies.

---

## Important Dates

<div class="dates-grid">
  <div class="date-card highlight">
    <div class="date-label">Submission Deadline</div>
    <div class="date-val">Oct 2, 2026 (AoE)</div>
  </div>
  <div class="date-card">
    <div class="date-label">Acceptance Notice</div>
    <div class="date-val">Nov 10, 2026</div>
  </div>
  <div class="date-card">
    <div class="date-label">Workshop Date</div>
    <div class="date-val">Dec 10, 2026</div>
  </div>
  <div class="date-card">
    <div class="date-label">Location</div>
    <div class="date-val">Makerere University</div>
  </div>
</div>

---

## Call for Submissions

We invite original research, deployment case studies, and innovative ideas addressing low-resource language technologies in African contexts. 

**Submission Tracks:**
* **Research Track:** Papers presenting theoretical, methodological, or empirical work relevant to the themes. (Presented as lightning talks + interactive paper panels).
* **Industry Track:** Papers detailing real-world implementations, deployed NLP systems, and lessons learned in production environments.

Both tracks require submissions of **at least 5 pages** (excluding references/appendices) strictly formatted using the **[JMLR / PMLR LaTeX Template](https://www.overleaf.com/latex/templates/jmlr-template/zqvxjzpbgxvb)**.

<a href="https://openreview.net/group?id=AfriLang_AI/2026/Conference" class="btn-submit">Submit on OpenReview &rarr;</a>

<div class="notice-card">
  <strong>OpenReview Moderation Note:</strong><br/>
  New profiles created <em>without an institutional email</em> take up to <strong>two weeks</strong> for verification. Profiles using an institutional email are activated automatically. Please create your account well ahead of the October 2nd deadline.
</div>

---

## Workshop Topics

* **Data Collection & Annotation:** Novel curation, augmentation, and crowdsourcing pipelines for low-resource African languages.
* **Transfer Learning & Multilingual Models:** Cross-lingual techniques, adaptation from high-resource languages, and code-switching handling.
* **Speech Technologies:** ASR, speech synthesis (TTS), speaker recognition, and accent adaptation across diverse dialects.
* **Machine Translation (NMT):** Bridging African languages with regional and global languages.
* **Ethics, Fairness & Bias:** Mitigating cultural, linguistic, and societal bias in African NLP systems.
* **Real-World Societal Impact:** Deployments in healthcare, agriculture, education, and civic tech.
* **Computational Linguistics:** Structural, phonological, syntactic, and morphological analysis.
* **LLMs & Foundation Models:** In-context learning, fine-tuning, and domain adaptation for regional languages.

---

## Publication

Accepted papers will appear in the official conference proceedings published via **[PMLR](https://proceedings.mlr.press/)** and hosted on the conference website. 

*(Review the previous edition via **[PMLR Volume 314](https://proceedings.mlr.press/v314/)**).*

---

## Organizing Committee

### General Chair

<div class="profile-grid">
  <div class="chair-card">
    <img src="assets/images/em.jpg" alt="Dr. Ernest Mwebaze" />
    <div class="chair-info">
      <strong>Dr. Ernest Mwebaze</strong><br/>
      <em>Executive Director, Sunbird AI</em>
      <p>Dr. Ernest Mwebaze is the Executive Director of Sunbird AI. He previously worked as a research scientist at Google AI in Ghana and UN Global Pulse, and co-founded the Makerere AI Lab. He holds a PhD from the University of Groningen.</p>
    </div>
  </div>
</div>

### Program Committee Chairs

<div class="profile-grid">
  <div class="chair-card">
    <img src="assets/images/johnqunin.jpg" alt="Dr. John Quinn" />
    <div class="chair-info">
      <strong>Dr. John Quinn</strong><br/>
      <em>Director of Research, Sunbird AI</em>
      <p>Dr. John Quinn is the Director of Research at Sunbird AI. He was previously a Staff Research Software Engineer at Google (leading the Open Buildings project) and Technical Lead at UN Global Pulse. He holds a PhD from the University of Edinburgh.</p>
    </div>
  </div>

  <div class="chair-card">
    <img src="assets/images/eb.jpeg" alt="Prof. Engineer Bainomugisha" />
    <div class="chair-info">
      <strong>Prof. Engineer Bainomugisha</strong><br/>
      <em>Professor & Chair of Computer Science, Makerere University</em>
      <p>Prof. Engineer Bainomugisha is Chair of Computer Science at Makerere University and founder of AirQo. He serves on the board of Sunbird AI and holds a PhD from Vrije Universiteit Brussel.</p>
    </div>
  </div>
</div>

### Program Committee Members

<div class="committee">
  <div class="committee-member"><strong>Prof. Engineer Bainomugisha</strong><br><small>Makerere University</small></div>
  <div class="committee-member"><strong>Dr. Ernest Mwebaze</strong><br><small>Sunbird AI</small></div>
  <div class="committee-member"><strong>Dr. John Quinn</strong><br><small>Sunbird AI</small></div>
  <div class="committee-member"><strong>Joel Tibabwetiza Muhanguzi</strong><br><small>Sunbird AI</small></div>
  <div class="committee-member"><strong>Janat Namara</strong><br><small>Sunbird AI</small></div>
</div>
