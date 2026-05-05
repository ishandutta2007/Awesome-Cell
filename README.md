# Awesome-Cell
## Multi-Scale Simulation Platforms for Molecular & Cellular Behavior Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Modeling Molecular and Cellular Behavior in Biological Systems*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **multi-scale simulation** of biological cells — tools that model processes across molecular (reaction-diffusion, stochastic), subcellular, cellular, and tissue scales. These simulators support deterministic/stochastic methods, agent-based modeling, particle-based approaches, and hybrid simulations for applications in cell biology, cancer research, electrophysiology, and systems biology.

**Examples** include VCell (Virtual Cell), MCell4, PhysiCell, Chaste, SpringSaLaD, Smoldyn, and Cytosim (the category leaders). Tools listed here emphasize **multi-scale capabilities** (molecular interactions to tissue-level behavior), spatial modeling, and integration of different simulation methods.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, customization, local execution, and full transparency — ideal for researchers building or extending simulations.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS / Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

### Core Multi-Scale Simulation Platforms

- **[VCell (Virtual Cell)](https://vcell.org/)**  
  Comprehensive platform for modeling cell biological systems. Supports deterministic (ODE/PDE), stochastic (SSA), spatial stochastic (Smoldyn integration), hybrid, and network-free agent-based simulations. Features biology-based interface, image-derived geometries, and remote server execution.

- **[MCell4](http://mcell.org/)** (Monte Carlo Cell)  
  High-performance Monte Carlo simulator for rule-based modeling of cellular microphysiology. Excels at stochastic spatial simulations of molecular interactions with complex geometries.

### Advanced & Specialized Platforms

- **[PhysiCell](https://physicell.org/)**  
  Open-source physics-based cell simulator for 3D multicellular systems. Agent-based modeling of large cell populations with microenvironment interactions.

- **[Chaste](https://chaste.github.io/)** (Cancer, Heart and Soft Tissue Environment)  
  General-purpose multi-scale simulation package for computationally demanding problems in biology and physiology, with strong focus on cardiac electrophysiology and cell-based tissue modeling.

- **[SpringSaLaD](https://vcell.org/ssalad-2)**  
  Particle-based stochastic biochemical simulator for mesoscopic systems. Models proteins as collections of sites connected by springs; ideal for multi-domain protein interactions.

- **[Smoldyn](https://www.smoldyn.org/)**  
  Spatial stochastic simulator treating molecules as individual particles. Supports 1D/2D/3D, rule-based modeling, and detailed molecular interactions.

- **[Cytosim](https://gitlab.com/f-nedelec/cytosim)**  
  Cytoskeleton simulation engine for modeling actin, microtubules, motors, and associated proteins with mechanical and stochastic elements.

**Other notable mentions**: Morpheus (multi-scale multicellular), ReaDDy, and integrated platforms combining multiple solvers.

## Open-Source GitHub Projects

### Dedicated Multi-Scale Cellular Simulation Projects

- **[VCell](https://github.com/virtualcell/vcell)**  
  Full open-source framework (MIT license) for comprehensive cell biology modeling. Supports ODE, PDE, stochastic, spatial, hybrid, and agent-based methods with image-based geometries and extensive solver options.

- **[PhysiCell](https://github.com/MathCancer/PhysiCell)**  
  Leading open-source physics-based multicellular simulator. Enables large-scale 2D/3D agent-based simulations of thousands to millions of cells with microenvironment interactions, designed for scalability on desktops to clusters.

- **[Chaste](https://github.com/Chaste)**  
  Mature C++ library for multi-scale computational biology and physiology. Strong modules for cardiac electrophysiology, cell-based tissue modeling, and soft tissue mechanics.

- **[MCell Tools](https://github.com/mcellteam)**  
  Collection of open-source tools and simulators for Monte Carlo cell simulations, including MCell4 with BioNetGen integration for rule-based modeling.

- **[Smoldyn](https://www.smoldyn.org/)** (source available via project site and community repositories)  
  Spatial particle-based biochemical simulator. Highly accurate stochastic modeling of molecular diffusion and reactions in complex cellular geometries.

- **[Cytosim](https://gitlab.com/f-nedelec/cytosim)**  
  Open-source simulation engine specialized in cytoskeletal dynamics, molecular motors, and mechanical modeling of cellular structures.

- **[SpringSaLaD](https://github.com/search?q=SpringSaLaD)** (integrated in VCell ecosystem with standalone releases)  
  Mesoscopic particle-based simulator using spring-connected sites for modeling multi-domain proteins and biochemical networks.

### Additional Strong Open-Source Options

- **[Morpheus](https://gitlab.com/morpheus.lab/morpheus)** — User-friendly environment for multi-scale multicellular systems coupling ODEs, PDEs, and Cellular Potts models.
- **[PhysiBoSS](https://github.com/PhysiBoSS/PhysiBoSSv1)** — Multiscale integration of PhysiCell with MaBoSS for intracellular signaling networks.
- **[ReaDDy](https://github.com/readdy/readdy)** — Particle-based reaction-diffusion simulator for mesoscale biological systems.
- **BioFVM** — Open-source library for biological diffusion often used with PhysiCell.
- **Vivarium** — Framework for integrative multi-scale whole-cell and colony modeling.
- Additional tools: SPARCED (large-scale signaling models), FitMultiCell, and various SBML-compatible simulators.

**Frameworks for building custom simulations**: Combine core engines (PhysiCell, VCell, Chaste) with SBML/BNGL standards, Python/C++ extensions, and visualization tools (e.g., PhysiCell Studio) for tailored multi-scale models.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Simulation results depend heavily on model assumptions, parameters, and validation against experimental data. Always verify numerical accuracy and biological relevance.
- For research use, cite original publications and ensure compliance with licensing terms.

---

**Made for computational biologists, systems biologists, and biomedical researchers.**  
Let's make multi-scale cellular modeling more accessible, reproducible, and extensible.
