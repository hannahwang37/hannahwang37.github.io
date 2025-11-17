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

@media (max-width: 1024px) {
  .publication-list {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 640px) {
  .publication-list {
    grid-template-columns: 1fr;
  }
}

.publication-item {
  padding: 10px;
  border: 1px solid #e5e5e5;
  border-radius: 8px;
  background-color: #fafafa;
  position: relative;
  display: flex;
  flex-direction: column;
  gap: 0px;
}

.publication-teaser {
  order: 2;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  object-fit: cover;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.publication-teaser:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
}

.publication-content {
  order: 1;
  flex: 1;
  min-width: 0;
}

.publication-title {
  font-size: 14px;
  font-weight: bold;
  margin-bottom: 6px;
  line-height: 1.2;
  color: #2c3e50;
  padding-right: 80px; /* Add right padding to avoid overlap with year */
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
  font-size: 12px;
  color: #666;
  margin-bottom: 4px;
  font-style: italic;
}

.publication-meta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  align-items: center;
  margin-bottom: 12px;
}

.publication-venue {
  display: inline-flex;
  align-items: center;
  font-size: 12px;
  color: #2980b9;
  font-weight: 500;
}

.publication-tags {
  display: inline-flex;
  flex-wrap: wrap;
  gap: 4px;
}

.publication-type-tag {
  display: inline-block;
  padding: 3px 10px;
  border-radius: 18px;
  font-size: 11px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  margin-right: 6px;
  margin-bottom: 4px;
}

.type-conference {
  background-color: #e74c3c;
  color: white;
}

.type-journal {
  background-color: #27ae60;
  color: white;
}

.type-preprint {
  background-color: #f39c12;
  color: white;
}

.publication-year {
  font-size: 12px;
  color: #7f8c8d;
  margin-bottom: 12px;
  font-weight: 600;
}

.research-domain-tag {
  display: inline-block;
  padding: 2px 6px;
  border-radius: 10px;
  font-size: 10px;
  font-weight: 500;
  margin-right: 5px;
  margin-bottom: 4px;
  background-color: #ecf0f1;
  color: #2c3e50;
  border: 1px solid #bdc3c7;
}

.publication-links {
  font-size: 12px;
}

.publication-links a {
  color: #3498db;
  text-decoration: none;
  margin-right: 15px;
  padding: 6px 12px;
  border: 1px solid #3498db;
  border-radius: 4px;
  transition: all 0.3s ease;
  display: inline-block;
  margin-bottom: 5px;
}

.publication-links a:hover {
  background-color: #3498db;
  color: white;
}

.timeline-year {
  position: absolute;
  top: 20px;
  right: 20px;
  font-size: 20px;
  font-weight: bold;
  color: #95a5a6;
}
</style>

  <div class="publications-container">
    <ul class="publication-list">
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <img src="/images/seeing-the-many.png" alt="Seeing the Many Teaser" class="publication-teaser">
        <div class="publication-content">
          <div class="publication-title">
            Seeing the Many: Exploring Parameter Distributions Conditioned on Features in Surrogates
            <span class="tag">🏅Best Paper Award</span>
          </div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong>, Zhimin Li, Joshua A. Levine, and Matthew Berger</div>
          <div class="publication-meta-row">
            <div class="publication-venue">IEEE Workshop on Uncertainty Visualization</div>
            <div class="publication-tags">
              <span class="research-domain-tag">DL</span>
              <span class="research-domain-tag">VIS</span>
              <span class="research-domain-tag">GenAI</span>
            </div>
          </div>
        </div>
      </li>    
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <img src="/images/topology-guidance-teaser.png" alt="Topology Guidance Teaser" class="publication-teaser">
        <div class="publication-content">
          <div class="publication-title">Topology Guidance: Controlling the Outputs of Generative Models via Vector Field Topology</div>
          <div class="publication-authors"><strong>Xiaohan Wang</strong> and Matthew Berger</div>
          <div class="publication-meta-row">
            <div class="publication-venue">arXiv preprint</div>
            <div class="publication-tags">
              <span class="research-domain-tag">DL</span>
              <span class="research-domain-tag">VIS</span>
              <span class="research-domain-tag">GenAI</span>
            </div>
          </div>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <img src="/images/github-impersonation-teaser.png" alt="GitHub Impersonation Teaser" class="publication-teaser">
        <div class="publication-content">
          <div class="publication-title">Who's Pushing the Code? An Exploration of GitHub Impersonation</div>
          <div class="publication-authors">Yueke Zhang, Anda Liang, <strong>Xiaohan Wang</strong>, ..., Kevin Leach, and Yu Huang.</div>
          <div class="publication-meta-row">
            <div class="publication-venue">IEEE/ACM International Conference on Software Engineering (ICSE)</div>
            <div class="publication-tags">
              <span class="research-domain-tag">SE</span>
              <span class="research-domain-tag">HCI</span>        
            </div>
          </div>
        </div>
      </li>
      <li class="publication-item">
        <div class="timeline-year">2025</div>
        <img src="/images/emotionlens-teaser.png" alt="EmotionLens Teaser" class="publication-teaser">
        <div class="publication-content">
          <div class="publication-title">EmotionLens: Interactive visual exploration of the circumplex emotion space in literary works via affective word clouds</div>
          <div class="publication-authors">Bingyuan Wang, Qing Shi, <strong>Xiaohan Wang</strong>, You Zhou, ..., and Zeyu Wang.</div>
          <div class="publication-meta-row">
            <div class="publication-venue">Visual Informatics</div>
            <div class="publication-tags">
              <span class="research-domain-tag">VIS</span>
              <span class="research-domain-tag">NLP</span>
              <span class="research-domain-tag">HCI</span>
            </div>
          </div>
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