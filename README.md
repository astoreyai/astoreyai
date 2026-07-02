# Aaron W. Storey

**PhD Candidate | Lunar Surface Autonomy & SLAM | Computer Vision & World Models | ML Transparency Testing | Founder @ Kymera Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/astoreyai/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-5560-0015)
[![IEEE](https://img.shields.io/badge/IEEE-Member-00629B?style=flat&logo=ieee&logoColor=white)](https://ieee.org)

---

## Research Focus

Autonomous navigation for robots that have to find their way where GPS does not exist and the lighting is brutal. And the evaluation rigor to prove the systems actually work.

| Pillar | Focus |
|--------|-------|
| **Autonomous Navigation** | Lunar surface autonomy, illumination-aware navigation, GNSS-denied localization, SLAM, pose-graph estimation with loop closure and DEM-anchored drift correction, active perception, motion & mission planning |
| **Geospatial Intelligence** | Image geolocation, terrain-referenced navigation (real LOLA lunar terrain), geospatial knowledge graphs & map systems |
| **AI Vision** | Stereo & multi-camera perception, photometric modeling (BRDF, cast-shadow geometry), Vision Transformers, 3D reconstruction, image quality |
| **Transparency & Evaluation** | Perturbation/ablation explainability testing, pre-registered leave-one-cue-out validation, counterfactual falsification of model explanations, data-leakage audits, PRISMA-ScR systematic reviews |

**Dissertation (ARGUS)**: Active, illumination-aware, multi-positional navigation for a reconfigurable lunar excavation rover (NASA IPEx lineage). The Sun, the shadows it casts, and the rover's own articulated posture become navigation instruments, fused into one fiducial-free pose-graph estimator with loop closure and DEM-anchored drift correction. On the real DLR S3LI Mt Etna analog (a 1.03 km crater loop) the estimator ladder reaches **7.99 m absolute trajectory error**, independently reproduced at 7.95 m and below a 21.4 m published baseline on the same data; preliminary batch-smoother evidence, with the criterion-scored online estimator as the proposed core contribution. Built and tested in a conserved-physics lunar simulator with pre-registered, leave-one-cue-out ablations. In development at proposal stage.

**Proposal**: lunar navigation topic in proposal stage @ Clarkson University | **Target completion**: May 2027

---

## Featured Projects

| Project | Description | Status |
|---------|-------------|--------|
| **ARGUS** (private repo) | Active, illumination-aware navigation for the NASA IPEx lunar excavation rover: SuperPoint visual odometry, visual loop closure, SE(3) pose-graph optimization, DEM height and attitude anchoring, solar-heading and cast-shadow factors | Dissertation, in dev |
| [dustgym](https://github.com/dustgym/dustgym) | Open-source conserved-physics lunar surface simulator: Godot photometric render on real LOLA terrain, IPEx energy and terramechanics, Gymnasium RL suite, mission planner | Contributor (McCardle leads) |
| Lunar Navigation Scoping Review | PRISMA-ScR review of SLAM and autonomous navigation for lunar surface operations: 1,161 eligible across five strands, 89 content-verified references | IEEE Access, in prep |
| GeoForge | Image geolocation framework (CLIP/embedding retrieval + OSINT cues, OSV-5M benchmark) | Geospatial (private) |
| [medicaid-kg](https://github.com/astoreyai/medicaid-kg) | Interactive geospatial knowledge graph + map viewer over a 227M-row national provider-spending dataset | Geospatial, public |
| [SIFTER](https://github.com/Bespoke-Robot-Society/SIFTER) | NASA Space Apps 2024: ML seismic detection for moon/marsquakes | NASA Hackathon |
| [Teleprompt](https://github.com/astoreyai/teleprompt) | Transparent always-on-top teleprompter for Linux: voice pacing, cue points, multi-format ingest | Linux release |
| [100 Days of ML](https://100daysofml.github.io/) | Complete 35-lesson curriculum: Python basics to XGBoost | ![Stars](https://img.shields.io/github/stars/100daysofml/100daysofml.github.io?style=flat) |

---

## Current Work

- **Dissertation (ARGUS)**: active, illumination-aware, multi-positional navigation for a reconfigurable lunar excavation rover (in development, proposal stage)
- **IEEE Access** (in preparation): SLAM and autonomous navigation for lunar surface operations, a PRISMA-ScR scoping review
- **RA-L / IROS / JFR** (in preparation): ARGUS system and method paper
- **dustgym** (in preparation, McCardle leads): conserved-physics lunar simulator papers, co-author
- **Founder & AI Engineer @ Kymera Systems**: multi-agent AI orchestration with explicit safety surfaces and evaluation harnesses
- **LLM safety & evaluation**: behavioral control surfaces and prompt-injection defense (NSPL framework, manuscript in preparation)
- Prior research (biometrics / XAI), now led by collaborators at CITeR: counterfactual falsification of attribution methods, face image quality (ISO/IEC 29794-5), longitudinal evaluation statistics

---

## Talks & Seminars

- **Behavioral Control Surfaces in Large Language Models** — Clarkson ECE invited seminar, January 2026 (delivered)
- **Navigating Worlds Without GPS** — three-part public summer seminar series on GNSS-denied and lunar surface navigation, Clarkson Dept. of Computer Science, Summer 2026 (sessions 1 and 2 delivered; session 3 on July 2; materials posted after each session)

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

**SLAM · Robotics · Sensor Fusion · Motion Planning · Geospatial · Gymnasium · Computer Vision · Evaluation Rigor**

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=astoreyai&show_icons=true&theme=nord&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=astoreyai&theme=nord&hide_border=true" alt="GitHub Streak" />
</p>

---

## Connect

- **Portfolio**: [astoreyai.github.io](https://astoreyai.github.io)
- **LinkedIn**: [linkedin.com/in/astoreyai](https://www.linkedin.com/in/astoreyai/)
- **ORCID**: [0009-0009-5560-0015](https://orcid.org/0009-0009-5560-0015)
- **Email**: storeyaw@clarkson.edu

---

*"Treat the Sun, the shadows it casts, and a rover's own posture as navigation instruments."*
