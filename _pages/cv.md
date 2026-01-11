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
/* CV 전용 스타일 */
.cv-container {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  color: #2d3748;
}

/* 섹션 헤더 */
.cv-section-title {
  font-size: 1.4rem;
  font-weight: 700;
  color: #1a202c;
  margin-top: 40px;
  margin-bottom: 15px;
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

/* 카드 스타일 */
.cv-card {
  background: #fff;
  margin-bottom: 15px;
  padding: 15px;
  border-left: 3px solid transparent;
  transition: all 0.2s ease-in-out;
  border: 1px solid #e2e8f0;
  border-radius: 6px;
}

/* 호버 효과 */
.cv-card:hover {
  border-left: 3px solid #3182ce;
  background-color: #f7fafc;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

/* 타이틀과 서브타이틀 */
.cv-item-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #2d3748;
  margin-bottom: 4px;
  display: block;
}

.cv-item-subtitle {
  font-size: 0.9rem;
  color: #4a5568;
  margin-bottom: 4px;
  line-height: 1.4;
}

/* 날짜 뱃지 */
.cv-date {
  font-size: 0.8rem;
  color: #718096;
  font-weight: 500;
  display: inline-block;
  background: #edf2f7;
  padding: 2px 6px;
  border-radius: 4px;
  margin-top: 4px;
}

/* 스킬 태그 스타일 */
.skill-tag {
  display: inline-block;
  background-color: #ebf8ff;
  color: #2c5282;
  padding: 3px 8px;
  border-radius: 6px;
  font-size: 0.8rem;
  font-weight: 600;
  margin-right: 5px;
  margin-bottom: 5px;
  border: 1px solid #bee3f8;
}
.skill-category {
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 6px;
  display: block;
  margin-top: 8px;
  font-size: 0.9rem;
}

/* 리스트 스타일 */
ul.cv-list { list-style: none; padding: 0; margin: 0; }
ul.cv-list li { margin-bottom: 4px; padding-left: 15px; position: relative; font-size: 0.9rem; color: #4a5568; line-height: 1.5; }
ul.cv-list li::before { content: "•"; position: absolute; left: 0; color: #3182ce; font-weight: bold; }

/* 버튼 스타일 */
.btn-download {
  background-color: #2c3e50; color: white !important; padding: 8px 16px;
  border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 0.9em;
  transition: background 0.2s; display: inline-block;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
.btn-download:hover { background-color: #1a202c; transform: translateY(-1px); }
</style>

<div class="cv-container">

  <div style="margin-bottom: 20px; text-align: right;">
    <a href="#" class="btn-download">📥 Download CV (PDF)</a>
  </div>

  <div class="cv-card" style="border-left: 3px solid #2c3e50; background-color: #f7fafc;">
    <h3 style="margin-top:0; color:#2c3e50; font-size: 1.2rem; margin-bottom: 10px;">🔬 Research Interests</h3>
    
    <div>
      <strong style="color:#2c5282;">Thesis Interest (Ph.D.)</strong>
      <p style="margin: 5px 0 0 0; color:#4a5568; font-size: 0.95rem; line-height: 1.6;">
        Utilizing <strong>physics-based simulations (FEP/MD)</strong> and developing <strong>bioinformatics platforms</strong> for precise structure-based drug design, specifically targeting GPCRs and metabolic enzymes.
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
    <strong style="font-size:1.05em; color:#e53e3e; display:block; margin-bottom:8px;">In Preparation / Under Review</strong>
    <ul class="cv-list">
      <li>
        <strong>CYP-MAP: Comprehensive Database and Multi-Level GNN Model for Site of Metabolism (SoM) Prediction</strong><br>
        <span style="font-size:0.9em; color:#718096;">(In preparation)</span>
      </li>
      <li style="margin-top:8px;">
        <strong>Promising Clue for a Functional Antagonism of FTY720-P by New Heterocyclic Analogues and Molecular Docking Analysis</strong><br>
        <span style="font-size:0.9em; color:#718096;">(In preparation)</span>
      </li>
    </ul>
  </div>

  <div class="cv-card">
    <strong style="font-size:1.05em; color:#2c5282; display:block; margin-bottom:8px;">Published (Selected)</strong>
    <ul class="cv-list">
      <li>
        <strong>MetaboGNN: predicting liver metabolic stability with graph neural networks...</strong><br>
        <span style="font-size:0.9em;">Park JH†, <strong>Han R†</strong>, et al. <i>Journal of Cheminformatics</i> (2025)</span>
      </li>
      <li style="margin-top:8px;">
        <strong>Unique molecular architecture of N-glycosylated TM4SF5 dimer...</strong><br>
        <span style="font-size:0.9em;">Lee Y, ..., <strong>Han R</strong>, ..., Lee JW* <i>Journal of Advanced Research</i> (2025)</span>
      </li>
      <li style="margin-top:8px;">
        <strong>Revolutionizing Medicinal Chemistry: The Application of AI...</strong><br>
        <span style="font-size:0.9em;"><strong>Han R†</strong>, et al. <i>Pharmaceuticals</i> (2023)</span>
      </li>
    </ul>
    <div style="text-align:right; margin-top:10px;">
      <a href="/publications/" style="color:#3182ce; font-weight:bold; text-decoration:none; font-size:0.85rem;">View All Publications →</a>
    </div>
  </div>

  <div class="cv-section-title">💻 Key Research & Development Projects</div>

  <div class="cv-card">
    <div class="cv-item-title">ProtHub: Integrated Platform for Protein-Ligand Interactions</div>
    <div class="cv-item-subtitle">Designed to consolidate scattered biological data and facilitate efficient analysis.</div>
    <ul class="cv-list" style="margin-top:10px;">
      <li><strong>Data Integration:</strong> Integrated heterogeneous data from UniProt, PDB, ChEMBL, and InterPro.</li>
      <li><strong>Visualization:</strong> Implemented 2D Chemical Space visualization (t-SNE/PCA) and sequence-identity heatmaps.</li>
      <li><strong>Web Stack:</strong> Built a comprehensive web platform for searching and analyzing ligand-binding proteins.</li>
    </ul>
    <div class="cv-date">Bioinformatics Web Platform</div>
  </div>

  <div class="cv-card">
    <div class="cv-item-title">GROMACS-based FEP Protocol for Membrane Proteins</div>
    <div class="cv-item-subtitle">Established a robust Free Energy Perturbation (FEP) workflow for GPCR-ligand systems in lipid bilayers.</div>
    <ul class="cv-list" style="margin-top:10px;">
      <li><strong>System Setup:</strong> Automated embedding of GPCRs into POPC lipid bilayers and equilibration protocols using GROMACS.</li>
      <li><strong>FEP Optimization:</strong> Optimized &lambda;-stratification and soft-core potentials to handle sampling difficulties in dense membrane environments.</li>
      <li><strong>Validation:</strong> Validated the protocol by reproducing experimental binding affinities for P2Y/P1 receptors with high accuracy.</li>
    </ul>
    <div class="cv-date">Simulation Methodology & Pipeline</div>
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

    <span class="skill-category">Data Science & Chemoinformatics</span>
    <div>
      <span class="skill-tag">RDKit</span>
      <span class="skill-tag">Morgan Fingerprints</span>
      <span class="skill-tag">Tanimoto Similarity</span>
      <span class="skill-tag">Clustering (t-SNE/PCA)</span>
    </div>

    <span class="skill-category">Web & Environment</span>
    <div>
      <span class="skill-tag">Linux (Ubuntu/CentOS)</span>
      <span class="skill-tag">HPC Cluster (Slurm)</span>
      <span class="skill-tag">Git/GitHub</span>
      <span class="skill-tag">Python Scripting</span>
      <span class="skill-tag">HTML/CSS/JS</span>
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
