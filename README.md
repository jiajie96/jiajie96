<h1 align="center">Hey, I'm Jiajie Fan — I teach machines to dream in 3D <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"></h1>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Founding+Engineer+%40+Kyrall;PhD+in+AI+for+3D+CAD+%7C+Leiden+University;Deep+Generative+Models+for+Engineering+Design;Spectral+Diffusion+%E2%80%A2+NURBS+Learning+%E2%80%A2+Shape+Generation" alt="Typing SVG" /></a>
</p>

<p align="center">
  <a href="https://jiajie96.github.io/jiajiefan.github.io/"><img src="https://img.shields.io/badge/Website-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="Website"/></a>&nbsp;
  <a href="https://scholar.google.com/citations?user=wph9BlIAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" alt="Google Scholar"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/jiajiefan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="mailto:jiajie.jf@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### About Me

- Founding Engineer at **Kyrall** — building AI-driven 3D CAD generation systems
- **PhD in Advanced Computer Science** from Leiden University (supervised by Prof. Thomas Bäck & Dr. Hao Wang)
  - Dissertation: *Deep Generative Models for Engineering Design*
- **MSc in Mechanical Engineering** from TU Darmstadt
- Research focus: bridging **machine learning** and **real-world product design** — spectral-domain diffusion, NURBS surface learning, plausibility evaluation of generated designs
- Published **6 peer-reviewed papers** at **ECCV**, **ICCV**, **IEEE CAI**, and arXiv

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jiajie96/neuronurbs">NeuroNURBS</a></h3>
      <img src="https://raw.githubusercontent.com/jiajie96/jiajiefan.github.io/main/assets/images/nurbs.png" width="100%" alt="NeuroNURBS"/>
      <p>Direct NURBS parameter encoding for 3D solid generation. <strong>86.7%</strong> less GPU, <strong>79.9%</strong> less memory vs UV-grid.</p>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenCASCADE-005F9E?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jiajie96/SpoDify_pytorch">SpoDify</a></h3>
      <img src="https://raw.githubusercontent.com/jiajie96/jiajiefan.github.io/main/assets/images/spodify.png" width="100%" alt="SpoDify"/>
      <p>Spectral-domain diffusion for 3D shape generation. Compress shapes to 512-D latents via wavelets + SVD.</p>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/IEEE%20CAI%202026-00629B?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jiajie96/DrivAerSDFNet">DrivAerSDFNet</a> <sup>(private)</sup></h3>
      <img src="https://raw.githubusercontent.com/jiajie96/jiajie96/main/drivaersdfnet_diagram.png" width="100%" alt="DrivAerSDFNet"/>
      <p>3D CNN surrogate for automotive aero coefficients. R²&nbsp;=&nbsp;0.972 on drag with only <strong>3.24M</strong> params.</p>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/SDF-grey?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jiajie96/PoDM-python">PoDM</a></h3>
      <img src="https://raw.githubusercontent.com/jiajie96/jiajiefan.github.io/main/assets/images/podm.png" width="100%" alt="PoDM"/>
      <p>Noise scheduling for plausible design synthesis. EDM-style diffusion + DragFDM interactive editing.</p>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/Diffusion-blueviolet?style=flat-square"/>
    </td>
  </tr>
</table>

---

<details>
<summary><h3>Publications (6 papers)</h3></summary>

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **SpoDify**: A Shape Is Worth 512 Numbers — Spectral-domain Diffusion Modeling for 3D Shape Generation | IEEE CAI | 2026 | [![arXiv](https://img.shields.io/badge/arXiv-2503.06485-b31b1b.svg)](https://arxiv.org/abs/2503.06485) [![Code](https://img.shields.io/badge/Code-GitHub-181717.svg)](https://github.com/jiajie96/SpoDify_pytorch) |
| **GeoDiffusion**: A Training-Free Framework for Accurate 3D Geometric Conditioning in Image Generation | ICCV | 2025 | [![Paper](https://img.shields.io/badge/Paper-ICCV-blue.svg)](https://openaccess.thecvf.com/content/ICCV2025/papers/Mueller_GeoDiffusion_A_Training-Free_Framework_for_Accurate_3D_Geometric_Conditioning_in_ICCV_2025_paper.pdf) |
| **FDD**: Enhancing Plausibility Evaluation for Generated Designs with Denoising Autoencoder | ECCV | 2024 | [![arXiv](https://img.shields.io/badge/arXiv-2403.05352-b31b1b.svg)](https://arxiv.org/abs/2403.05352) |
| **SA-ALAE**: Adversarial Latent Autoencoder with Self-Attention for Structural Image Synthesis | IEEE CAI | 2024 | [![IEEE](https://img.shields.io/badge/IEEE-10605375-00629B.svg)](https://ieeexplore.ieee.org/abstract/document/10605375/) [![Code](https://img.shields.io/badge/Code-GitHub-181717.svg)](https://github.com/jiajie96/SA_ALAE-python) |
| **NeuroNURBS**: Learning Efficient Surface Representations for 3D Solids | Under Review | 2024 | [![arXiv](https://img.shields.io/badge/arXiv-2411.10848-b31b1b.svg)](https://arxiv.org/abs/2411.10848) [![Code](https://img.shields.io/badge/Code-GitHub-181717.svg)](https://github.com/jiajie96/neuronurbs) |
| **PoDM**: On the Noise Scheduling for Generating Plausible Designs with Diffusion Models | arXiv | 2023 | [![arXiv](https://img.shields.io/badge/arXiv-2311.11207-b31b1b.svg)](https://arxiv.org/abs/2311.11207) [![Code](https://img.shields.io/badge/Code-GitHub-181717.svg)](https://github.com/jiajie96/PoDM-python) |

</details>

---

<p align="center">
  <img src="https://github.com/jiajie96/jiajie96/blob/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>
</p>
