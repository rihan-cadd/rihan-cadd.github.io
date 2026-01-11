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
/* 다크모드 버튼 숨기기 (필요 시 class 확인 필요) */
.theme-toggle, button[title="Toggle theme"] { display: none !important; }

/* Publications 페이지와 동일한 디자인 시스템 적용 */
.cv-container {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  color: #2d3748;
}

/* 섹션 헤더 (Publications의 연도 헤더와 동일 스타일) */
.cv-section-title {
  font-size: 1.5rem;
  font-weight: 700;
  color: #1a202c;
  margin-top: 50px;
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.cv-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: #e2e8f0;
  margin-left: 15px;
}

/* 카드 스타일 (Publications의 .pub-item 스타일 복사) */
.cv-card {
  background: #fff; /* 기본 흰색 배경 */
  margin-bottom: 30px;
  padding: 15px; /* 내부 여백 */
  border-left: 3px solid transparent; /* 호버 효과를 위한 투명 테두리 */
  transition: all 0.2s ease-in-out;
}

/* 호버 효과 (Publications와 동일) */
.cv-card:hover {
  border-left: 3px solid #3182ce;
  background-color: #f7fafc;
}

/* 타이틀과 서브타이틀 */
.cv-item-title {
  font-size: 1.15rem;
  font-weight: 600;
  color: #2d3748;
  margin-bottom: 6px;
  display: block;
}

.cv-item-subtitle {
  font-size: 0.95rem;
  color: #4a5568;
  margin-bottom: 5px;
  line-height: 1.5;
}

/* 날짜 뱃지 */
.cv-date {
  font-size: 0.85rem;
  color: #718096;
  font-weight: 500;
  display: inline-block;
  background: #edf2f7;
  padding: 2px 8px;
  border-radius: 6px;
  margin-top: 5px;
}

/* 스킬 태그 스타일 (뱃지 형태) */
.skill-tag {
  display: inline-block;
  background-color: #ebf8ff;
  color: #2c5282;
  padding: 3px 8px;
  border-radius: 6px;
  font-size: 0.85rem;
  font-weight: 600;
  margin-right: 5px;
  margin-bottom: 5px;
  border: 1px solid #bee3f8;
}
.skill-category {
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 8px;
  display: block;
  margin-top: 10px;
  font-size: 0.95rem;
}

/* 리스트 스타일 */
ul.cv-list { list-style: none; padding: 0; margin: 0; }
ul.cv-list li { margin-bottom: 5px; padding-left: 15px; position: relative; font-size: 0.95rem; color: #4a5568; }
ul.cv-list li::before { content: "•"; position: absolute; left: 0; color: #3182ce; font-weight: bold; }

/* 버튼 스타일 */
.btn-download {
  background-color: #2c3e50; color: white !important; padding: 10px 20px;
  border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 0.95em;
  transition: background 0.2s; display: inline-block;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
.btn-download:hover { background-color: #1a202c; transform: translateY(-1px); }
</style>

<div class="cv-container">

  <div style="margin-bottom: 30px; text-align: right;">
    <a href="#" class="btn-download">📥 Download CV (PDF)</a>
  </div>

  <div class="cv-card" style="border-left: 3px solid #2c3e50; background-color: #f7fafc;">
    <h3 style="margin-top:0; color:#2c3e50; font-size: 1.2rem;">🔬 Research Interests</h3>
    
    <div style="margin-bottom: 15px;">
      <strong style="color:#2c5282;">Thesis Interest (Ph.D.)</strong>
      <p style="margin: 5px 0 0 0; color:#4a5568; font-size: 0.95rem; line-height: 1.6;">
        Hybridizing physics-based simulations (FEP/MD) with <strong>data-driven AI</strong> for precise structure-based drug design, specifically targeting GPCRs and metabolic enzymes.
      </p>
    </div>
    
    <div>
      <strong style="color:#2c5282;">Post-doctoral Interest (Future)</strong>
      <p style="margin: 5px 0 0 0; color:#4a5568; font-size: 0.95rem; line-height: 1.6;">
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
    <strong style="font-size:1.1em; color:#e53e3e; display:block; margin-bottom:10px;">In Preparation / Under Review</strong>
    <ul class="cv-list">
      <li>
        <strong>CYP-MAP: Comprehensive Database and Multi-Level GNN Model for Site of Metabolism (SoM) Prediction</strong><br>
        <span style="font-size:0.9em; color:#718096;">(In preparation)</span>
      </li>
      <li style="margin-top:10px;">
        <strong>Promising Clue for a Functional Antagonism of FTY720-P by New Heterocyclic Analogues and Molecular Docking Analysis</strong><br>
        <span style="font-size:0.9em; color:#718096;">(In preparation)</span>
      </li>
    </ul>
  </div>

  <div class="cv-card">
    <strong style="font-size:1.1em; color:#2c5282; display:block; margin-bottom:10px;">Published (Selected)</strong>
    <ul class="cv-list">
      <li>
        <strong>MetaboGNN: predicting liver metabolic stability with graph neural networks...</strong><br>
        <span style="font-size:0.9em;">Park JH†, <strong>Han R†</strong>, et al. <i>Journal of Cheminformatics</i> (2025)</span>
      </li>
      <li style="margin-top:10px;">
        <strong>Unique molecular architecture of N-glycosylated TM4SF5 dimer...</strong><br>
        <span style="font-size:0.9em;">Lee Y, ..., <strong>Han R</strong>, ..., Lee JW* <i>Journal of Advanced Research</i> (2025)</span>
      </li>
      <li style="margin-top:10px;">
        <strong>Revolutionizing Medicinal Chemistry: The Application of AI...</strong><br>
        <span style="font-size:0.9em;"><strong>Han R†</strong>, et al. <i>Pharmaceuticals</i> (2023)</span>
      </li>
    </ul>
    <div style="text-align:right; margin-top:15px;">
      <a href="/publications/" style="color:#3182ce; font-weight:bold; text-decoration:none; font-size:0.9rem;">View All Publications →</a>
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
