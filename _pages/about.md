---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.spacing {
  line-height: 1.5;
}

#main {
  max-width: 1200px;
}

@media (min-width: 57.8125em) {
  #main .sidebar {
    overflow-x: hidden;
    padding-right: 1rem;
  }

  #main .author__urls li,
  #main .author__urls a {
    white-space: normal;
    overflow-wrap: anywhere;
  }

  #main .author__name,
  #main .author__bio {
    overflow-wrap: anywhere;
  }

  #main .page {
    padding-left: 6%;
    padding-right: 0;
  }
}

.selected-projects {
  margin-top: 1rem;
}

.selected-project {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-bottom: 24px;
}

.selected-project__image {
  flex: 0 0 280px;
  width: 280px;
  max-width: 280px;
  height: auto;
}

.selected-project__body {
  flex: 1 1 auto;
  min-width: 0;
}

.selected-project__title {
  color: #2f7f93;
}

@media (max-width: 700px) {
  .selected-project {
    align-items: flex-start;
    flex-direction: column;
  }

  .selected-project__image {
    flex-basis: auto;
    width: 100%;
    max-width: 420px;
  }
}
</style>


I am currently a fourth-year Ph.D. candidate at Nanyang Technological University (NTU), supervised by [Prof. Lihua Xie](https://scholar.google.com.sg/citations?user=Fmrv3J8AAAAJ&hl=en) from NTU and co-supervised by [Dr. Yau Wei-Yun](https://scholar.google.com.sg/citations?user=B_VchHYAAAAJ&hl=en) from Agency for Science, Technology and Research (A*STAR), Singapore. Before that, I received both my M. Eng. degree (2022) and B. Eng. degree (2019) from Zhejiang University (ZJU), under the supervision of [Assoc. Prof. Ronghao Zheng](https://scholar.google.com/citations?user=LxgdmqYAAAAJ&hl=en).

My past research primarily focuses on **planning and optimization problems** in multi-robot systems, including autonomous exploration, active SLAM, and planning under practical communication and temporal constraints. I am passionate about **uncovering the mathematical foundations underlying practical challenges** in autonomous robotic systems for real-world deployment, utilizing tools from optimization, graph theory, etc. I am also actively seeking the combination of robotics and learning-based foundation models. Feel free to reach out if you're interested in my work!
<p class="spacing"></p>

Selected News
======
* [06/2026] Three paper got accepted by IEEE/RSJ IROS 2026! The acceptance rate drops to 36% this year. Congrats to Junhe Sheng, Jie Chen, and Yuteng Sun!
* [05/2025] My first-authored paper about line-of-sight maintenance was selected as the ICRA 2025 Best Conference Paper Award Finalist.
* [05/2025] I presented two papers about SLAM-aware exploration and line-of-sight maintenance at IEEE ICRA 2025 at Atlanta, USA.
* [01/2025] Three papers got accepted by IEEE ICRA 2025!
* [07/2024] One paper got accepted by IEEE/RSJ IROS 2024!
* [06/2024] One paper got accepted by IEEE RA-L!
<p class="spacing"></p>

Selected Projects
======
<div class="selected-projects">
<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2026-bai-roken.gif" alt="Robots as Tokens project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Robots as Tokens: Unified Diffusion Transformer for Coordinated Multi-Robot Trajectory Generation</strong>
        <br>
        <em><b>Ruofei Bai</b>, J Chen, Y Cai, J Li, WY Yau, L Xie</em>
        <br>
        Submitted to CoRL 2026. [<a href="https://arxiv.org/abs/2606.15550">Paper</a>] [<a href="https://bairuofei.github.io/roken-project-page/">Project</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2026-bai-los-mapless.gif" alt="Line-of-Sight-Constrained Multi-Robot Mapless Navigation project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Line-of-Sight-Constrained Multi-Robot Mapless Navigation via Polygonal Visible Regions</strong>
        <br>
        <em><b>Ruofei Bai</b>, S Yuan, X Xu, X Ji, X Li, H Guo, WY Yau, L Xie</em>
        <br>
        Submitted to RA-L. [<a href="https://arxiv.org/abs/2603.26314">Paper</a>] [<a href="https://github.com/bairuofei/LoS_constrained_navigation">Code</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2026-sheng-beyond-imitation.gif" alt="Beyond Imitation project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Beyond Imitation: Reinforcement Learning Fine-Tuning for Adaptive Diffusion Navigation Policies</strong>
        <br>
        <em>J Sheng*, <b>Ruofei Bai*</b>, K Xu, R Liu, J Chen, S Yuan, WY Yau, L Xie</em>
        <br>
        2026 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). [<a href="https://arxiv.org/abs/2603.12868">Paper</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2026-sun-tidal.gif" alt="TIDAL project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">TIDAL: Temporally Interleaved Diffusion and Action Loop for High-Frequency VLA Control</strong>
        <br>
        <em>Y Sun, H Wang, <b>Ruofei Bai</b>, Z Li, J Li, M Yee, WY Yau</em>
        <br>
        2026 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). [<a href="https://arxiv.org/abs/2601.14945">Paper</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2026-chen-imaginav.gif" alt="ImagiNav project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">ImagiNav: Scalable Embodied Navigation via Generative Visual Prediction and Inverse Dynamics</strong>
        <br>
        <em>J Chen, Y Cai, Y Wang, <b>Ruofei Bai</b>, Y Cao, J Li, YW Yun, G Sartoretti</em>
        <br>
        2026 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). [<a href="https://arxiv.org/abs/2603.13833">Paper</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2025-bai-realm.gif" alt="Realm project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Realm: Real-Time Line-of-Sight Maintenance in Multi-Robot Navigation with Unknown Obstacles</strong>
        <br>
        <em><b>Ruofei Bai</b>, S Yuan, K Li, H Guo, WY Yau, L Xie</em>
        <br>
        2025 IEEE International Conference on Robotics and Automation (ICRA). [<a href="https://arxiv.org/abs/2502.15162">Paper</a>] [<a href="https://github.com/bairuofei/LoS_constrained_navigation">Code</a>]
        <br>
        <span style="color: red; font-weight: bold;">Best Paper Award Finalist</span>
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2024-bai-SAE.gif" alt="Graph-based Slam-Aware Exploration project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Graph-based Slam-Aware Exploration with Prior Topo-Metric Information</strong>
        <br>
        <em><b>Ruofei Bai</b>, H Guo, WY Yau, L Xie</em>
        <br>
        IEEE Robotics and Automation Letters (RA-L), 2024. [<a href="https://arxiv.org/abs/2308.16522">Paper</a>] [<a href="https://github.com/bairuofei/Graph-Based_SLAM-Aware_Exploration">Code</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2024-bai-CGE.gif" alt="Multi-Robot Active Graph Exploration project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Multi-Robot Active Graph Exploration with Reduced Pose-SLAM Uncertainty via Submodular Optimization</strong>
        <br>
        <em><b>Ruofei Bai</b>, S Yuan, H Guo, P Yin, WY Yau, L Xie</em>
        <br>
        2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). [<a href="https://arxiv.org/abs/2407.01013">Paper</a>] [<a href="https://github.com/bairuofei/CGE">Code</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2022-RAS-ltl2.png" alt="Hierarchical Multi-Robot Strategies project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Hierarchical Multi-Robot Strategies Synthesis and Optimization under Individual and Collaborative Temporal Logic Specifications</strong>
        <br>
        <em><b>Ruofei Bai</b>, R Zheng, M Liu, S Zhang</em>
        <br>
        Robotics and Autonomous Systems (RAS), 2022. [<a href="https://arxiv.org/abs/2110.11162">Paper</a>]
    </div>
</div>

<div class="selected-project">
    <img class="selected-project__image" src="../images/publications/2021-bai-ltl.gif" alt="Multi-Robot Task Planning project preview">
    <div class="selected-project__body">
        <strong class="selected-project__title">Multi-Robot Task Planning under Individual and Collaborative Temporal Logic Specifications</strong>
        <br>
        <em><b>Ruofei Bai</b>, R Zheng, M Liu, S Zhang</em>
        <br>
        2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). [<a href="https://arxiv.org/abs/2108.11597">Paper</a>] [<a href="https://github.com/bairuofei/sampling_ltl_planning">Code</a>]
    </div>
</div>
</div>

