---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* CV 전용 스타일 - 다른 페이지와 톤앤매너 통일 */
.cv-container { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; color: #2d3748; }

/* 섹션 헤더 */
.cv-section-title {
  font-size: 1.5rem; font-weight: 700; color: #1a202c;
  margin-top: 50px; margin-bottom: 20px; border-bottom: 2px solid #e2e8f0; padding-bottom: 10px;
  display: flex; align-items: center;
}

/* 카드 스타일 */
.cv-card {
  background: #fff; border: 1px solid #e2e8f0; border-radius: 8px;
  padding: 20px; margin-bottom: 20px;
  border-left: 4px solid transparent; /* 호버 효과용 */
  transition: all 0.2s ease-in-out;
}
.cv-card:hover {
  border-left: 4px solid #3182ce; /* 마우스 올리면 파란색 포인트 */
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
}

/* 타이틀과 날짜 */
.cv-item-title { font-size: 1.15rem; font-weight: 600; color: #2d3748; margin-bottom: 5px; }
.cv-item-subtitle { font-size: 1rem; color: #4a5568; margin-bottom: 5px; }
.cv-date { font-size: 0.9rem; color: #718096; font-weight: 500; display: inline-block; background: #edf2f7; padding: 2px 8px; border-radius: 4px; margin-top:5px;}

/* 스킬 태그 스타일 */
.skill-tag {
  display: inline-block; background-color: #ebf8ff; color: #2c5282;
  padding: 4px 10px; border-radius: 15px; font-size: 0.85rem; font-weight: 600;
  margin-right: 5px; margin-bottom: 5px; border: 1px solid #bee3f8;
}
.skill-category { font-weight: 700; color: #2c3e50; margin-bottom: 8px; display: block; margin-top: 10px; }

/* 리스트 스타일 제거 */
ul.cv-list { list-style: none; padding: 0; margin: 0; }
ul.cv-list li { margin-bottom: 5px; padding-left: 15px; position: relative; }
ul.cv-list li::before { content: "•"; position: absolute; left: 0; color: #3182ce; }

/* 버튼 스타일 */
.btn-download {
  background-color: #2c3e50; color: white !important; padding: 10px 20px;
  border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 0.95em;
  transition: background 0.2s; display: inline-block;
}
.btn-download:hover { background-color: #1a202c; }
</style>

<div class="cv-container">

  <div style="margin-bottom: 30px; text-align: right;">
    <a href="#" class="btn-download">
      📥 Download CV (PDF)
    </a>
  </div>

  <div class="cv-card" style="background-color: #f7fafc; border-left: 4px solid #2c3e50;">
    <h3 style="margin-top:0; color:#2c3e50;">🔬 Research Interests</h3>
    <p style="margin-bottom: 10px;">
      My research focuses on <strong>Computer-Aided Drug Design (CADD)</strong>, bridging the gap between physics-based simulations and data-driven AI.
    </p>
    <ul class="cv-list">
      <li><strong>Core Topics:</strong> Virtual Screening, Structure-Based Drug Design (SBDD), GPCR</li>
      <li><strong>Methodologies:</strong> Protein-Ligand Docking, Molecular Dynamics (MD), Free Energy Perturbation (FEP)</li>
    </ul>
  </div>

  <div class="cv-section-title">🎓 Education</div>

  <div class="cv-card">
    <div class="cv-item-title">Ph.D. Candidate in Global Innovative Drugs</div>
    <div class="cv-item-subtitle">Chung-Ang University, Seoul, South Korea</div>
    <div class="cv-item-subtitle">Division of Chem/Bioinformatics (Advisor: Prof. Yoonji Lee)</div>
    <div class="cv-date">Mar 2023 - Present</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">M.S. in Pharmacy</div>
    <div class="cv-item-subtitle">Chung-Ang University, Seoul, South Korea</div>
    <div class="cv-item-subtitle">Division of Chem/Bioinformatics (Advisor: Prof. Yoonji Lee)</div>
    <div class="cv-date">Mar 2021 - Feb 2023</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">B.S. in Life Sciences</div>
    <div class="cv-item-subtitle">Daejin University, Pocheon, South Korea</div>
    <div class="cv-date">Mar 2009 - Feb 2013</div>
  </div>

  <div class="cv-section-title">🏆 Honors & Awards</div>

  <div class="cv-card">
    <div class="cv-item-title">Best Poster Award (2nd Class)</div>
    <div class="cv-item-subtitle">Asia Hub for e-Drug Discovery Symposium</div>
    <div class="cv-date">Feb 2025</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Travel Award</div>
    <div class="cv-item-subtitle">The Pharmaceutical Society of Korea (PSK), Fall International Convention</div>
    <div class="cv-date">Oct 2024</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Grand Prize (Minister Award)</div>
    <div class="cv-item-subtitle">New Drug Development AI Competition, hosted by MSIT</div>
    <div class="cv-date">Aug 2023</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Best Poster Presentation Award</div>
    <div class="cv-item-subtitle">14th AFMC International Medicinal Chemistry Symposium (AIMECS)</div>
    <div class="cv-date">Jun 2023</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">CAU Graduate Research Scholarship (GRS)</div>
    <div class="cv-item-subtitle">Chung-Ang University</div>
    <div class="cv-date">2023 - 2024</div>
  </div>

  <div class="cv-section-title">📜 Publications (Selected)</div>

  <div class="cv-card">
    <div class="cv-item-title">MetaboGNN: predicting liver metabolic stability with graph neural networks and cross-species data</div>
    <div class="cv-item-subtitle">Park JH†, <strong>Han R†</strong>, Jang J†, Kim J†, Paik J*, Heo J*, Lee Y*</div>
    <div class="cv-item-subtitle" style="font-style:italic;">Journal of Cheminformatics (2025)</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Unique molecular architecture of N-glycosylated TM4SF5 dimer highlights evolutionary and structural divergence</div>
    <div class="cv-item-subtitle">Lee Y, ..., <strong>Han R</strong>, ..., Lee JW*</div>
    <div class="cv-item-subtitle" style="font-style:italic;">Journal of Advanced Research (2025)</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Revolutionizing Medicinal Chemistry: The Application of AI in Early Drug Discovery</div>
    <div class="cv-item-subtitle"><strong>Han R†</strong>, Yoon H†, Kim G, Lee H, Lee Y*</div>
    <div class="cv-item-subtitle" style="font-style:italic;">Pharmaceuticals (2023)</div>
  </div>
  
  <div style="text-align:right;">
    <a href="/publications/" style="color:#3182ce; text-decoration:none; font-weight:bold;">View All Publications →</a>
  </div>

  <div class="cv-section-title">🗣 Presentations (Selected)</div>

  <div class="cv-card">
    <div class="cv-item-title">Improving SAR Prediction Accuracy during Lead Optimization through Free Energy Perturbation</div>
    <div class="cv-item-subtitle">136th General Meeting of the Korean Chemical Society (KCS)</div>
    <span class="skill-tag" style="background:#f3e5f5; color:#7b1fa2; border-color:#e1bee7;">Oral</span> <span class="cv-date">Oct 2025</span>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Improving Structure-Activity Relationship Predictions in Lead Optimization Using FEP</div>
    <div class="cv-item-subtitle">2025 Graduate Research Symposium, Chung-Ang University</div>
    <span class="skill-tag" style="background:#f3e5f5; color:#7b1fa2; border-color:#e1bee7;">Oral</span> <span class="cv-date">Jan 2025</span>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">Prediction of Drug-Target Interaction using Deep Learning (Final Pitch)</div>
    <div class="cv-item-subtitle">New Drug Development AI Competition</div>
    <span class="skill-tag" style="background:#f3e5f5; color:#7b1fa2; border-color:#e1bee7;">Oral</span> <span class="cv-date">Aug 2023</span>
  </div>

  <div style="text-align:right;">
    <a href="/talks/" style="color:#3182ce; text-decoration:none; font-weight:bold;">View All Presentations →</a>
  </div>

  <div class="cv-section-title">🛠 Technical Skills</div>

  <div class="cv-card">
    <span class="skill-category">Computational Chemistry & Simulation</span>
    <div>
      <span class="skill-tag">GROMACS (FEP/MD)</span>
      <span class="skill-tag">Cresset Flare</span>
      <span class="skill-tag">Schrödinger Glide</span>
      <span class="skill-tag">AutoDock Vina</span>
      <span class="skill-tag">PyMOL</span>
      <span class="skill-tag">VMD</span>
    </div>

    <span class="skill-category">Data Science & Informatics</span>
    <div>
      <span class="skill-tag">RDKit</span>
      <span class="skill-tag">Morgan Fingerprints</span>
      <span class="skill-tag">Clustering</span>
    </div>

    <span class="skill-category">Programming & Web</span>
    <div>
      <span class="skill-tag">Python</span>
      <span class="skill-tag">R</span>
      <span class="skill-tag">Linux Shell</span>
      <span class="skill-tag">HTML/CSS/PHP</span>
      <span class="skill-tag">Git/GitHub</span>
    </div>
  </div>

  <div class="cv-section-title">🏫 Extracurricular & Training</div>

  <div class="cv-card">
    <div class="cv-item-title">LAIDD Mentoring Project: Molecular Virtual Screening</div>
    <div class="cv-item-subtitle">Korea Pharmaceutical and Bio-Pharma Manufacturers Association (KPBMA)</div>
    <div class="cv-date">2023</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">8th GSDC Schools of Data Computing</div>
    <div class="cv-item-subtitle">Hosted by Ministry of Science and ICT (MSIT), Organized by KISTI</div>
    <div class="cv-date">2023</div>
  </div>

</div>
