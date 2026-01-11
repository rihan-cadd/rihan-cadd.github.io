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
    <a href="#" class="btn-download">📥 Download CV (PDF)</a>
  </div>

  <div class="cv-card" style="background-color: #f7fafc; border-left: 4px solid #2c3e50;">
    <h3 style="margin-top:0; color:#2c3e50;">🔬 Research Interests</h3>
    
    <div style="margin-bottom: 15px;">
      <strong style="color:#2c5282;">Thesis Interest (Ph.D.)</strong>
      <p style="margin: 5px 0 0 0; color:#4a5568;">
        Hybridizing physics-based simulations (FEP/MD) with <strong>data-driven AI</strong> for precise structure-based drug design, specifically targeting GPCRs and metabolic enzymes.
      </p>
    </div>
    
    <div>
      <strong style="color:#2c5282;">Post-doctoral Interest (Future)</strong>
      <p style="margin: 5px 0 0 0; color:#4a5568;">
        Integration of Generative AI with Free Energy Calculations for <i>De Novo</i> Drug Design and automated multi-scale pipelines for ADMET prediction.
      </p>
    </div>
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
    <div class="cv-date">Mar 2021 - Feb 2023</div>
  </div>
  <div class="cv-card">
    <div class="cv-item-title">B.S. in Life Sciences</div>
    <div class="cv-item-subtitle">Daejin University, Pocheon, South Korea</div>
    <div class="cv-date">Mar 2009 - Feb 2013</div>
  </div>

  <div class="cv-section-title">📜 Publications</div>

  <div class="cv-card">
    <strong style="font-size:1.1em; color:#e53e3e;">In Preparation / Under Review</strong>
    <ul style="margin-top:10px; padding-left:20px; line-height:1.6;">
      <li style="margin-bottom:10px;">
        <strong>CYP-MAP: Comprehensive Database and Multi-Level GNN Model for Site of Metabolism (SoM) Prediction</strong><br>
        <span style="color:#555;">(In preparation)</span>
      </li>
      <li>
        <strong>Promising Clue for a Functional Antagonism of FTY720-P by New Heterocyclic Analogues and Molecular Docking Analysis</strong><br>
        <span style="color:#555;">(In preparation)</span>
      </li>
    </ul>
  </div>

  <div class="cv-card">
    <strong style="font-size:1.1em; color:#2c5282;">Published (Selected)</strong>
    <ul style="margin-top:10px; padding-left:20px; line-height:1.6;">
      <li style="margin-bottom:10px;">
        <strong>MetaboGNN: predicting liver metabolic stability with graph neural networks...</strong><br>
        <span style="color:#555;">Park JH†, <strong>Han R†</strong>, et al. <i>Journal of Cheminformatics</i> (2025)</span>
      </li>
      <li style="margin-bottom:10px;">
        <strong>Unique molecular architecture of N-glycosylated TM4SF5 dimer...</strong><br>
        <span style="color:#555;">Lee Y, ..., <strong>Han R</strong>, ..., Lee JW* <i>Journal of Advanced Research</i> (2025)</span>
      </li>
      <li>
        <strong>Revolutionizing Medicinal Chemistry: The Application of AI...</strong><br>
        <span style="color:#555;"><strong>Han R†</strong>, et al. <i>Pharmaceuticals</i> (2023)</span>
      </li>
    </ul>
    <div style="text-align:right; margin-top:10px;">
      <a href="/publications/" style="color:#3182ce; font-weight:bold; text-decoration:none;">View All Publications →</a>
    </div>
  </div>

  <div class="cv-section-title">🏆 Honors & Awards</div>
  <div class="cv-card">
    <div class="cv-item-title">Best Poster Award (2nd Class)</div>
    <div class="cv-item-subtitle">Asia Hub for e-Drug Discovery Symposium (Feb 2025)</div>
  </div>
  <div class="cv-card">
    <div class="cv-item-title">Travel Award</div>
    <div class="cv-item-subtitle">The Pharmaceutical Society of Korea (PSK) (Oct 2024)</div>
  </div>
  <div class="cv-card">
    <div class="cv-item-title">Grand Prize (Minister Award)</div>
    <div class="cv-item-subtitle">New Drug Development AI Competition (MSIT) (Aug 2023)</div>
  </div>
  <div class="cv-card">
    <div class="cv-item-title">Best Poster Presentation Award</div>
    <div class="cv-item-subtitle">AIMECS 2023 (Jun 2023)</div>
  </div>

  <div class="cv-section-title">🛠 Technical Skills</div>
  <div class="cv-card">
    <span class="skill-category">Computational Chemistry & Simulation</span>
    <div>
      <span class="skill-tag">GROMACS</span>
      <span class="skill-tag">Cresset Flare</span>
      <span class="skill-tag">Schrödinger Glide</span>
      <span class="skill-tag">AutoDock Vina</span>
      <span class="skill-tag">PyMOL / VMD</span>
    </div>

    <span class="skill-category">Data Science & Informatics</span>
    <div>
      <span class="skill-tag">RDKit</span>
      <span class="skill-tag">Morgan Fingerprints</span>
      <span class="skill-tag">Clustering</span>
    </div>

    <span class="skill-category">Environment & Tools (Detailed)</span>
    <div>
      <span class="skill-tag">Linux (Ubuntu/CentOS)</span>
      <span class="skill-tag">HPC Cluster (Slurm)</span>
      <span class="skill-tag">Git/GitHub</span>
      <span class="skill-tag">Python Scripting</span>
      <span class="skill-tag">HTML/CSS/PHP/JS</span>
    </div>
  </div>

  <div class="cv-section-title">🏫 Extracurricular & Training</div>
  <div class="cv-card">
    <div class="cv-item-title">LAIDD Mentoring Project</div>
    <div class="cv-item-subtitle">KPBMA (2023)</div>
  </div>
  <div class="cv-card">
    <div class="cv-item-title">8th GSDC Schools of Data Computing</div>
    <div class="cv-item-subtitle">KISTI (2023)</div>
  </div>

</div>
