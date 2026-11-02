---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the PDF version](/files/tameem_bakr_cv.pdf)

Education
* Ph.D. in Machine Learning, Mohamed bin Zayed University of Artificial Intelligence, Aug. 2026 - Present
* M.Sc. in Machine Learning, Mohamed bin Zayed University of Artificial Intelligence, Aug. 2024 - May 2026 (CGPA: 3.77)
* B.Sc. in Computer Engineering, Egypt-Japan University of Science and Technology, Sep. 2018 - Mar. 2024 (CGPA: 3.55)

Research Experience
* Aug. 2024 - Present: Graduate Researcher (Ph.D. and M.Sc.)
  * Mohamed bin Zayed University of Artificial Intelligence, Abu Dhabi, UAE
  * Researching trustworthy machine learning, supervised by Dr. Nils Lukas.
  * Designing threshold watermarks for federated learning, where any *t* of *n* clients can jointly prove model ownership.
  * Developing attacks, defenses, and detection methods for content and model watermarking.
  * Studying attacks and defenses for machine learning systems, e.g., prompt injection, jailbreaks, and backdoors.
  * Investigating how to attribute credit and blame among agents in LLM multi-agent systems.

* Jul. 2025 - Sep. 2025: Research Intern
  * CISPA Helmholtz Center for Information Security, Saarland, Germany
  * Conducted research at SprintML Lab, supervised by Dr. Adam Dziedzic and Dr. Franziska Boenisch.
  * Researched watermarking and post-hoc data provenance for image autoregressive models (ICLR 2026).

* Dec. 2021 - Apr. 2022: Machine Learning Research Intern
  * Egypt-Japan University of Science and Technology, Alexandria, Egypt
  * Developed resource-efficient COVID-19 detection from cough sounds with wavelet scattering (MIUCC 2022).
  * Achieved state-of-the-art performance with lower computational cost.

Industry Experience
* Feb. 2024 - May 2024: AI/ML Engineer
  * Smartera 3S Solutions and Systems, Alexandria, Egypt
  * Gathered on-site requirements at Ahli Bank Oman for an analytics program of 40 use cases and 100 dashboards.
  * Built credit-risk, loan-approval, and churn models with XGBoost, LightGBM, and Bayesian optimization.
  * Coordinated data acquisition with the data engineering team and dashboard delivery with the Power BI team.

* Jan. 2024 - Feb. 2024: Software Engineering Intern
  * GreenMEA, Cairo, Egypt
  * Integrated computer-vision models for PPE-compliance monitoring into a Flask web application.

* Aug. 2023 - Sep. 2023: Data Science Intern
  * Banque Misr, Cairo, Egypt
  * Optimized ATM cash-replenishment routes using K-means/K-medoids clustering and genetic algorithms.

Publications
<div class="pub-list">{% for post in site.publications reversed %}
  {% include publication-item.html %}
{% endfor %}</div>

Under Review and Ongoing Work
* T. Bakr and N. Lukas. "ICE: Innovation-based Contribution Estimation." *Under review at the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2027.*
* T. Bakr, Y. Ashraf, and N. Lukas. "Credit and Blame in LLM Multi-Agent Systems: A Survey of Contribution Attribution." *Under review at the ACM Conference on Fairness, Accountability, and Transparency (FAccT) 2027.*
* Y. Ashraf, T. Bakr, D. S. Chauhan, R. Astudillo, and N. Lukas. "From Traces to Recipes: Constructing and Distilling Reusable Procedural Knowledge into Language Models." *Under review at the International Conference on Learning Representations (ICLR) 2027.*
* T. Bakr and N. Lukas. "Black-Box Threshold Watermarking for Federated Learning." *In preparation.*
* T. Bakr and N. Lukas. "Threshold Watermarking for Language Models." *In preparation.*

Honors and Awards
* **Mohamed bin Zayed University of Artificial Intelligence:**
  * Department of Machine Learning Award for High-Impact Publications.
  * Awarded a merit-based, fully funded scholarship to pursue a Ph.D. in Machine Learning.
  * Awarded a merit-based, fully funded scholarship to pursue an M.Sc. in Machine Learning.
* **NeurIPS 2024:** Erasing the Invisible Challenge, first place in both the black-box and beige-box tracks.
* **GITEX 2024:** Cyber Hackathon: Battle of The Elite Capture The Flag Competition (First Place).
* **CyberTalents:** Introduction to Cybersecurity Bootcamp Capture The Flag Competition (First Place).
* **Egypt-Japan University of Science and Technology:** Awarded a merit-based, fully funded scholarship to pursue a B.Sc. in Computer Engineering.

Technical Skills
* **Watermarking**: LLMs (sampling-based, semantic, in-weights), images (post-hoc, in-processing), models (white-box, black-box).
* **Cryptography**: Secret sharing, secure multi-party computation, commitments and zero-knowledge proofs.
* **Generative Models**: LLMs, image autoregressive models, diffusion models.
* **Deep Learning**: PyTorch, torchvision, DeepSpeed, Hugging Face Transformers, Diffusers, PEFT, vLLM.
* **Scientific Computing**: Python, NumPy, SciPy, pandas, scikit-learn, Matplotlib, OpenCV.
* **Infrastructure**: Docker, Git, Linux, SLURM/HPC clusters, Weights & Biases.
