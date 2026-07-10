---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Electrical Engineering, Korea Advanced Institute of Science and Technology (KAIST), Aug 2022 – Present
  * Exchange program at École polytechnique fédérale de Lausanne (EPFL), 2024 – 2025

Research experience
======
* **BIG Lab, EPFL** — Undergraduate Researcher (Lausanne, Switzerland), Feb 2025 – Present
  * Developed a Python-based simulation framework mapping theoretical diffuser models onto practical optical systems, grounded in i.i.d. random matrices and probability theory to bridge abstract mathematics with experimental feasibility.
  * Improved reconstruction quality by tuning model parameters and studying the effect of parity of depth, increasing cosine similarity from 0.03 to 0.80.
  * Parameterized spectrum-based surface properties to translate mathematical models into actionable design insights, reducing the gap between random-matrix-theory predictions and real-world diffuser fabrication.

* **Optics Lab (Mooo Lab), KAIST** — Undergraduate Researcher (Daejeon, South Korea), Mar 2024 – Present
  * Lead a project adapting vision-language models to solve the scattering-media imaging problem.
  * Designed and executed physical optical imaging experiments using spatially incoherent light, spatial light modulators, and ground-glass diffusers.
  * Streamlined model training with automated hyperparameter-tuning scripts, improving PSNR from 16 to 24 and MAE from 0.153 to 0.068 while reducing experiment turnaround time.
  * Designed and executed experiments for physics-aware, deep-learning-based holographic imaging, integrating CNNs with domain-specific physical constraints to improve reconstruction fidelity (journal paper submitted).
  * Performed laser system setup, optical alignment, and ensured interferometric stability.

* **MIP Lab, EPFL** — Undergraduate Researcher (Geneva, Switzerland), Feb 2025 – Aug 2025
  * Built Python pipelines with NumPy and Pandas to query, clean, and analyze high-dimensional fMRI datasets, enabling more efficient cross-group comparisons.
  * Conducted time-resolved correlation analysis to verify co-activation pattern (CAP) peak alignment against TbCAP (CAP Toolbox) reference outputs, ensuring signal validity.

* **Laboratory of Applied Photonics Devices (LAPD), EPFL** — Undergraduate Researcher (Lausanne, Switzerland), Jul 2024 – Jan 2025
  * Applied optical neural networks to time-series prediction (ETT dataset) with custom encoding and decoding schemes.
  * Conducted model optimization in PyTorch, modifying the architecture to improve prediction efficiency while keeping it simple and scalable.

* **Quantum Light Sources Group (QLIGHT), DTU** — Undergraduate Researcher (Kongens Lyngby, Denmark), Jul 2024 – Sep 2024
  * Cut simulation runtime by 50% by streamlining sampling and meshing workflows under resource constraints.
  * Designed high-Q ring resonators at 800 nm and 1550 nm using Lumerical 3D FDTD, optimizing for peak visibility and spectral accuracy.
  * Resolved tradeoffs between coupling efficiency and fabrication constraints by tuning resonator gaps and waveguide widths.

* **MetaPhotonics Lab, KAIST** — Undergraduate Researcher (Daejeon, South Korea), Mar 2023 – Jun 2024
  * Engineered and optimized logic gates and complex sequences in Lumerical using inverse design, performing physical analysis with FDTD and applying topology optimization (resulted in first-author papers).
  * Conducted numerical analysis to identify structural behavior patterns and performance insights guiding precise optimization strategies.
  * Developed high-performance AND, OR, NOT, and XOR gates, a half-adder, a half-subtractor, and a 4×2 encoder through 2D and 3D simulations, improving efficiency and compactness.
  * Evaluated compliance with design standards by analyzing signal propagation delay, power consumption, and signal integrity.

Skills and expertise
======
* **Programming languages:** Python, Java, JavaScript, MATLAB, RISC-V Assembly
* **Data science & machine learning:** PyTorch, TensorFlow, NumPy, Pandas, Jupyter, Matplotlib, diffusion models, vision-language models (VLMs), convolutional neural networks (CNNs)
* **DevOps & version control:** Git, Linux
* **Design & optimization:** control theory, inverse design, Verilog, VHDL, Cadence, Lumerical FDTD/MODE
* **Optics & photonics:** computational imaging, laser systems, interferometry, fiber optics, holography, silicon photonics

Honors and awards
======
* **EE Academy Achievement Scholarship**, KAIST, 2025 — awarded to the top four academically outstanding students in the department.
* **Global Leadership Award (Creativity category)**, KAIST, 2025 — awarded for creative problem-solving and leadership, given to the top 0.42% of KAIST students.
* **College of Engineering Leadership Award (Research Excellence category)**, KAIST, 2024 — awarded to the top 0.35% of College of Engineering students for leadership across multiple categories.

Languages
======
* Azerbaijani (Native), Russian (Native), English (Fluent), French (Intermediate), Turkish (Intermediate)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
