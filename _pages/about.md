---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="about-intro">
<p>
  I am <strong>Xiaohan Wang</strong>, a Ph.D. student in Computer Science at <strong>Vanderbilt University</strong>. 
  My research aims to design representations for different data modalities and leverage AI/machine learning methods to make data exploration and understanding more efficient and accessible.
  <!-- My research spans <strong>AI for Software Engineering (AI4SE)</strong>, where I study , 
  and <strong>machine learning for scientific visual analytics (ML4SciVIS)</strong>, where I have developed visualization methods for exploring large-scale scientific simulation data. -->
</p>
</div>

<div class="about-columns">
  <section class="about-column">
    <h2 class="about-column__title">🎓 Education</h2>
    <ul class="about-education">
      <li class="about-education__item">
        <span class="about-education__icon" aria-hidden="true"></span>
        <div>
          <div class="about-education__degree"><strong>Ph.D. in Computer Science</strong></div>
          <div class="about-education__school">Vanderbilt University</div>
          <div class="about-education__time">Aug. 2023 – Expected May 2028</div>
        </div>
      </li>
      <li class="about-education__item">
        <span class="about-education__icon" aria-hidden="true"></span>
        <div>
          <div class="about-education__degree"><strong>B.Eng. in Software Engineering</strong></div>
          <div class="about-education__school">Nanjing Normal University, Yingcai Honors College</div>
          <div class="about-education__time">Sep. 2019 – Jun. 2023</div>
        </div>
      </li>
    </ul>
  </section>

  <section class="about-column">
    <h2 class="about-column__title">🌱 Interests</h2>
    <ul class="about-interests">
      <li>Code and program understanding with large language models</li>
      <li>Large-scale scientific simulation data exploration using machine learning techniques</li>
    </ul>
  </section>  
</div>

---

<section class="about-section about-section--publications">
  <h2>📚 Selected Publications</h2>

  <style>
.publication-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 10px;
}



.publication-item {
  min-width: 0;
  aspect-ratio: 1 / 1;
  box-sizing: border-box;
  padding: 24px 10px 10px;
  border: 1px solid #e5e5e5;
  border-radius: 8px;
  background-color: #fafafa;
  position: relative;
  display: grid;
  grid-template-rows: minmax(0, 1fr);
  gap: 6px;
}

.publication-overview {
  display: block;
  width: 100%;
  min-width: 0;
  margin: 6px 0 8px;
}

.publication-teaser {
  order: 2;
  display: block;
  max-width: 100%;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  object-fit: contain;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.page__content .publication-overview .publication-teaser {
  width: 100%;
  height: auto;
  object-fit: contain;
}

.publication-overview:focus-visible {
  outline: 2px solid #2980b9;
  outline-offset: 3px;
}

.publication-teaser:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
}

.publication-content {
  order: 1;
  flex: 1;
  min-width: 0;
  min-height: 0;
  overflow-y: auto;
  overflow-x: hidden;
  overflow-wrap: anywhere;
  scrollbar-width: thin;
}

.publication-title {
  font-size: 12px;
  font-weight: bold;
  margin-bottom: 6px;
  line-height: 1.2;
  color: #2c3e50;
  padding-right: 0;
}
.publication-title .tag {
  display: inline-block;
  margin-left: 6px;
  padding: 2px 6px;
  font-size: 0.75em;
  font-weight: 600;
  color: white;
  background-color: #e67e22;
  border-radius: 6px;
  vertical-align: middle;
}

.publication-authors {
  font-size: 10px;
  color: #666;
  margin-bottom: 4px;
  font-style: italic;
}

.publication-meta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  align-items: center;
  margin-bottom: 4px;
}

.publication-venue {
  display: inline-flex;
  align-items: center;
  font-size: 10px;
  color: #2980b9;
  font-weight: 500;
}

.publication-year {
  font-size: 12px;
  color: #7f8c8d;
  margin-bottom: 12px;
  font-weight: 600;
}

.publication-links {
  font-size: 10px;
  line-height: 1.2;
}

.publication-links a {
  color: #3498db;
  text-decoration: none;
  margin-right: 15px;
  padding: 4px 6px;
  border: 1px solid #3498db;
  border-radius: 4px;
  transition: all 0.3s ease;
  display: inline-block;
  margin-bottom: 0;
}

.publication-links a:hover {
  background-color: #3498db;
  color: white;
}

.timeline-year {
  position: absolute;
  top: 5px;
  right: 10px;
  font-size: 11px;
  font-weight: bold;
  color: #95a5a6;
}
@media (max-width: 640px) {
  .publication-list { gap: 6px; }
  .publication-item { padding: 20px 6px 6px; }
  .publication-title { font-size: 9px; }
  .publication-authors, .publication-venue, .publication-links { font-size: 8px; }
  .timeline-year { font-size: 8px; right: 6px; }
}
</style>

  <div class="publications-container">
    <ul class="publication-list">
      <li class="publication-item">
        <div class="timeline-year">2026</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">STILL: Recovering Lowered STL Semantics for LLM-assisted C++ Decompilation</div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong>, Kevin Leach</div>
          <div class="publication-meta-row">
            <div class="publication-venue">EMNLP 2026 Main Conference</div>
          </div>
          <a class="publication-overview image-popup" href="/images/publications/still-overview.png" title="Open overview figure at full resolution">
          <img src="/images/publications/still-overview.png" alt="STILL overview: binary residues feed semantic extraction and STL hints for LLM refinement" class="publication-teaser" width="1750" height="746" loading="lazy" decoding="async">
        </a>
          <div class="publication-links"><a href="https://arxiv.org/abs/2608.26408">arXiv</a></div>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2026</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">ICL4Decomp: Towards Re-executable Reverse Engineering</div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong>, Yuxin Hu, Kevin Leach</div>
          <div class="publication-meta-row">
            <div class="publication-venue">Findings of EMNLP 2026</div>
          </div>
          <a class="publication-overview image-popup" href="/images/publications/icl4decomp-overview.png" title="Open overview figure at full resolution">
          <img src="/images/publications/icl4decomp-overview.png" alt="ICL4Decomp overview: retrieved examples and optimization-aware context guide end-to-end decompilation" class="publication-teaser" width="850" height="600" loading="lazy" decoding="async">
        </a>
          <div class="publication-links"><a href="https://arxiv.org/abs/2511.01763">arXiv</a></div>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2026</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">Constraint-Guided Multi-Agent Decompilation for Executable Binary Recovery</div>
          <div class="publication-authors">Yifan Zhang*, <strong>Xiaohan Wang*</strong>, Yueke Zhang, Yu Huang, Kevin Leach</div>
          <div class="publication-authors">*Equal contribution.</div>
          <div class="publication-meta-row">
            <div class="publication-venue">NeurIPS 2026 Workshop on Evaluation of Interactive Agents</div>
          </div>
          <a class="publication-overview image-popup" href="/images/publications/constraint-guided-overview.png" title="Open overview figure at full resolution">
          <img src="/images/publications/constraint-guided-overview.png" alt="Agent4Decompile overview: syntax, compilation, and execution constraints guide specialized repair agents" class="publication-teaser" width="1016" height="540" loading="lazy" decoding="async">
        </a>
          <div class="publication-links"><a href="https://arxiv.org/abs/2604.23940v2">arXiv</a></div>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">
            Seeing the Many: Exploring Parameter Distributions Conditioned on Features in Surrogates
            <span class="tag">🏅Best Paper Award</span>
          </div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong>, Zhimin Li, Joshua A. Levine, and Matthew Berger</div>
          <div class="publication-meta-row">
            <div class="publication-venue">IEEE Workshop on Uncertainty Visualization</div>
          </div>
          <a class="publication-overview image-popup" href="/images/seeing-the-many.png" title="Open overview figure at full resolution">
          <img src="/images/seeing-the-many.png" alt="Seeing the Many Teaser" class="publication-teaser">
        </a>
        </div>
      </li>    
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">Topology Guidance: Controlling the Outputs of Generative Models via Vector Field Topology</div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong> and Matthew Berger</div>
          <div class="publication-meta-row">
            <div class="publication-venue">arXiv preprint</div>
          </div>
          <a class="publication-overview image-popup" href="/images/topology-guidance-teaser.png" title="Open overview figure at full resolution">
          <img src="/images/topology-guidance-teaser.png" alt="Topology Guidance Teaser" class="publication-teaser">
        </a>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">Who's Pushing the Code? An Exploration of GitHub Impersonation</div>
          <div class="publication-authors">Yueke Zhang, Anda Liang, <strong>Xiaohan Wang</strong>, ..., Kevin Leach, and Yu Huang.</div>
          <div class="publication-meta-row">
            <div class="publication-venue">IEEE/ACM International Conference on Software Engineering (ICSE)</div>
          </div>
          <a class="publication-overview image-popup" href="/images/github-impersonation-teaser.png" title="Open overview figure at full resolution">
          <img src="/images/github-impersonation-teaser.png" alt="GitHub Impersonation Teaser" class="publication-teaser">
        </a>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <div class="publication-content" tabindex="0" aria-label="Publication details">
          <div class="publication-title">EmotionLens: Interactive visual exploration of the circumplex emotion space in literary works via affective word clouds</div>
          <div class="publication-authors">Bingyuan Wang, Qing Shi, <strong>Xiaohan Wang</strong>, You Zhou, ..., and Zeyu Wang.</div>
          <div class="publication-meta-row">
            <div class="publication-venue">Visual Informatics</div>
          </div>
          <a class="publication-overview image-popup" href="/images/emotionlens-teaser.png" title="Open overview figure at full resolution">
          <img src="/images/emotionlens-teaser.png" alt="EmotionLens Teaser" class="publication-teaser">
        </a>
        </div>
      </li>      
    </ul>
  </div>
</section>

---

<section class="about-section">
  <h2>📰 News</h2>

  <ul class="about-timeline">
  <li class="about-timeline__item">
    <span class="about-timeline__year">8/2026</span>
    <div class="about-timeline__content">
      Our paper <em>“STILL: Recovering Lowered STL Semantics for LLM-assisted C++ Decompilation”</em> has been accepted to EMNLP 2026 Main Conference.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">8/2026</span>
    <div class="about-timeline__content">
      Our paper <em>“ICL4Decomp: Towards Re-executable Reverse Engineering”</em> has been accepted to Findings of EMNLP 2026.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">9/2026</span>
    <div class="about-timeline__content">
      Our paper <em>“Constraint-Guided Multi-Agent Decompilation for Executable Binary Recovery”</em> has been accepted to NeurIPS 2026 Workshop on Evaluation of Interactive Agents.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">🏆 11/2025</span>
    <div class="about-timeline__content">
      Our paper <em>“Seeing the Many: Exploring Parameter Distributions Conditioned on Features in Surrogates”</em> is accepted and received the Best Paper Award at the IEEE Workshop on Uncertainty Visualization.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">📄 5/2025</span>
    <div class="about-timeline__content">
      Our work <em>“Topology Guidance: Controlling the Outputs of Generative Models via Vector Field Topology”</em> is released as an arXiv preprint.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">📄 3/2025</span>
    <div class="about-timeline__content">
      Our collaborative project <em>“EmotionLens: Interactive visual exploration of the circumplex emotion space in literary works via affective word clouds”</em> is published in <em>Visual Informatics</em>.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">📄 3/2025</span>
    <div class="about-timeline__content">
      Our paper <em>“Who's Pushing the Code? An Exploration of GitHub Impersonation”</em> is accepted by ICSE.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">🎓 2025</span>
    <div class="about-timeline__content">
      I began a new research direction under the guidance of Prof. Leach.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">🎓 11/2024</span>
    <div class="about-timeline__content">
      I passed my PhD preliminary examination.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">🎓 8/2023</span>
    <div class="about-timeline__content">
      I started my PhD in Computer Science at Vanderbilt University under the supervision of Prof. Berger.
    </div>
  </li>

  <li class="about-timeline__item">
    <span class="about-timeline__year">🎓 2020</span>
    <div class="about-timeline__content">
      I was selected for Yingcai Honors College.
    </div>
  </li>  

</ul>

</section>

---

<section class="about-section">
  <h3>🏅 Awards</h3>

  <ul class="about-timeline">
    <!-- <li class="about-timeline__item">
      <span class="about-timeline__year">2025</span>
      <div class="about-timeline__content">
        Best Long Paper Award of IEEE Workshop on Uncertainty Visualization
      </div>
    </li>   -->
    <li class="about-timeline__item">
      <span class="about-timeline__year">2020 - 2022</span>
      <div class="about-timeline__content">
        Outstanding Student Scholarship - First Prize
        <small>Top 5% of cohort</small>
      </div>
    </li>
  </ul>
</section>