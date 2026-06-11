---
permalink: /
title: "Shaoqing Lin / 林绍卿"
author_profile: false
layout: splash
redirect_from:
  - /about/
  - /about.html
---

<main class="homepage" aria-label="Shaoqing Lin personal homepage">
  <section class="homepage-hero" id="home">
    <div class="homepage-hero__content">
      <p class="homepage-eyebrow">Incoming PhD Student · Trustworthy AI · Agentic Systems</p>
      <h1>Shaoqing Lin<br><span>林绍卿</span></h1>
      <p class="homepage-hero__summary">
        I work on trustworthy large language models, agentic data synthesis, and multimodal language understanding.
        I am an incoming PhD student at City University of Hong Kong, currently completing my master's study at Wuhan University.
        I strongly welcome collaborations of any form.
      </p>
      <div class="homepage-actions" aria-label="Contact links">
        <a class="homepage-button homepage-button--primary" href="mailto:kyrielincn@gmail.com">
          <i class="fas fa-envelope" aria-hidden="true"></i>
          Email
        </a>
        <a class="homepage-button" href="https://github.com/ShaoqLin">
          <i class="fab fa-github" aria-hidden="true"></i>
          GitHub
        </a>
      </div>
    </div>
  </section>

  <section class="homepage-band homepage-intro" id="about">
    <div class="homepage-container homepage-two-column">
      <div>
        <p class="homepage-section-label">About</p>
        <h2>Research at the intersection of LLM reliability, structured generation, and tool use.</h2>
      </div>
      <div class="homepage-copy">
        <p>
          My research interests focus on uncertainty estimation for language models and improving reliability in multi-step decision-making tasks. In particular, I study how language models can recognize and manage uncertainty across tool use, agentic planning, and MoE routing, where models need to make a sequence of decisions rather than a single prediction.
        </p>
        <p>
          I am advised by <a href="https://jszy.whu.edu.cn/tengchong/zh_CN/index.htm">Prof. Chong Teng</a> during my master's study at Wuhan University, and will be advised by <a href="https://kaidixu.com/">Prof. Kaidi Xu</a> at City University of Hong Kong.
        </p>
        <p>
          I am very honored to work closely with <a href="https://zhuang-li.github.io/">Prof. Zhuang Li</a>. Together, we received an <a href="http://cips-cl.org/?p=88817"><strong>EMNLP 2025 Outstanding Paper Award</strong></a> for <a href="https://arxiv.org/abs/2506.15583"><strong>DiscoSG</strong></a>, one of seven such awards among 3,200+ accepted papers. I am the first author of this work.
        </p>
      </div>
    </div>
  </section>

  <section class="homepage-band homepage-collaboration" id="collaboration">
    <div class="homepage-container homepage-collaboration__inner">
      <div>
        <p class="homepage-section-label">Collaboration</p>
        <h2>Open to any form of collaboration.</h2>
      </div>
      <p>
        I warmly welcome research discussions, joint projects, open-source work, dataset construction, evaluation benchmarks, industry research, and long-term collaborations. Please feel free to reach out at <a href="mailto:kyrielincn@gmail.com">kyrielincn@gmail.com</a>.
      </p>
    </div>
  </section>

  <section class="homepage-band" id="news">
    <div class="homepage-container">
      <div class="homepage-section-heading">
        <p class="homepage-section-label">Highlights</p>
        <h2>Recent Updates</h2>
      </div>
      <div class="homepage-highlight-grid">
        <article class="homepage-highlight">
          <span>2026</span>
          <h3>Incoming PhD Student</h3>
          <p>City University of Hong Kong, starting September 2026.</p>
        </article>
        <article class="homepage-highlight">
          <span>2025</span>
          <h3>EMNLP Outstanding Paper</h3>
          <p><a href="https://arxiv.org/abs/2506.15583">DiscoSG</a> received one of seven <a href="http://cips-cl.org/?p=88817">EMNLP 2025 Outstanding Paper Awards</a> among 3,200+ accepted papers.</p>
        </article>
        <article class="homepage-highlight">
          <span>2025</span>
          <h3>Research Internships</h3>
          <p>Research and algorithm internships at Ant International, Microsoft, and Xiaomi.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="homepage-band homepage-band--soft" id="internships">
    <div class="homepage-container">
      <div class="homepage-section-heading">
        <p class="homepage-section-label">Internships</p>
        <h2>Industry Research Experience</h2>
      </div>
      <div class="homepage-internship-grid">
        <article class="homepage-internship">
          <div class="homepage-logo-wrap">
            <img src="{{ '/images/internships/ant-international.png' | relative_url }}" alt="Ant International logo">
          </div>
          <div>
            <h3>Ant International / 蚂蚁国际</h3>
            <p class="homepage-role">Research Intern · Dec 2025 - Present</p>
            <p>Long-term research internship focused on large language model systems and trustworthy AI.</p>
          </div>
        </article>
        <article class="homepage-internship">
          <div class="homepage-logo-wrap">
            <img src="{{ '/images/internships/microsoft.png' | relative_url }}" alt="Microsoft logo">
          </div>
          <div>
            <h3>Microsoft</h3>
            <p class="homepage-role">Research Intern · Apr 2025 - Sep 2025</p>
            <p>Worked on Excel Copilot code generation, reinforcement learning rollouts, and chart-analysis data pipelines.</p>
          </div>
        </article>
        <article class="homepage-internship">
          <div class="homepage-logo-wrap">
            <img src="{{ '/images/internships/xiaomi.png' | relative_url }}" alt="Xiaomi logo">
          </div>
          <div>
            <h3>Xiaomi / 小米科技</h3>
            <p class="homepage-role">Algorithm Engineer Intern · Jan 2025 - Apr 2025</p>
            <p>Algorithm engineering internship with practical experience in model development and production-oriented workflows.</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <section class="homepage-band" id="publications">
    <div class="homepage-container">
      <div class="homepage-section-heading">
        <p class="homepage-section-label">Publications</p>
        <h2>Selected Work</h2>
      </div>
      <article class="homepage-publication">
        <div class="homepage-publication__tag">EMNLP 2025 · Outstanding Paper Award · Oral Presentation</div>
        <h3>DiscoSG: Towards Discourse-Level Text Scene Graph Parsing through Iterative Graph Refinement</h3>
        <p>
          <strong>Shaoqing Lin</strong>, <a href="https://jszy.whu.edu.cn/tengchong/zh_CN/index.htm">Chong Teng</a>, Fei Li, Donghong Ji, Lizhen Qu, <a href="https://zhuang-li.github.io/">Zhuang Li</a>.
          Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing.
          <a href="http://cips-cl.org/?p=88817">Outstanding Paper Award</a>, one of seven such awards among 3,200+ accepted papers.
        </p>
        <div class="homepage-link-row">
          <a href="https://arxiv.org/abs/2506.15583">
            <i class="fas fa-file-lines" aria-hidden="true"></i>
            Paper
          </a>
          <a href="https://github.com/ShaoqLin/DiscoSG">
            <i class="fab fa-github" aria-hidden="true"></i>
            Code
          </a>
          <a href="http://cips-cl.org/?p=88817">
            <i class="fas fa-award" aria-hidden="true"></i>
            Award
          </a>
        </div>
      </article>
    </div>
  </section>

  <section class="homepage-band homepage-band--soft" id="research">
    <div class="homepage-container">
      <div class="homepage-section-heading">
        <p class="homepage-section-label">Research</p>
        <h2>Research Projects</h2>
      </div>
      <div class="homepage-project-list">
        <article class="homepage-project">
          <span>Discourse-Level Scene Graph Parsing</span>
          <h3>Structured understanding for long image descriptions</h3>
          <p>Built the DiscoSG-DS dataset and proposed DiscoSG-Refiner for iterative graph refinement over discourse-level textual scene graphs.</p>
        </article>
        <article class="homepage-project">
          <span>Uncertainty Estimation</span>
          <h3>Reliability in multi-step decision-making</h3>
          <p>Studying how language models recognize and manage uncertainty across tool use, agentic planning, and MoE routing.</p>
        </article>
        <article class="homepage-project">
          <span>Agentic Tool Use</span>
          <h3>Flow-grounded trace synthesis</h3>
          <p>Studying reusable flow structures for generating tool-use trajectories from dialogue while preserving task-level constraints.</p>
        </article>
        <article class="homepage-project">
          <span>Microsoft Internship</span>
          <h3>Excel Copilot and chart-analysis pipelines</h3>
          <p>Built rollout training workflows for Excel Python and Formula generation, and expanded high-diversity chart-analysis training data.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="homepage-band" id="education">
    <div class="homepage-container homepage-two-column">
      <div>
        <p class="homepage-section-label">Education</p>
        <h2>Academic Background</h2>
      </div>
      <div class="homepage-timeline">
        <article>
          <span>2026 - 2030</span>
          <h3>City University of Hong Kong</h3>
          <p>Incoming PhD Student. Advisor: <a href="https://kaidixu.com/">Prof. Kaidi Xu</a>.</p>
        </article>
        <article>
          <span>2023 - 2026</span>
          <h3>Wuhan University</h3>
          <p>M.S. student, Cyber Security. Advisor: <a href="https://jszy.whu.edu.cn/tengchong/zh_CN/index.htm">Prof. Chong Teng</a>.</p>
        </article>
        <article>
          <span>2019 - 2023</span>
          <h3>Shandong University</h3>
          <p>B.S., Computer Science and Technology</p>
        </article>
      </div>
    </div>
  </section>

  <section class="homepage-band homepage-skills" id="skills">
    <div class="homepage-container">
      <div class="homepage-section-heading">
        <p class="homepage-section-label">Skills</p>
        <h2>Technical Stack</h2>
      </div>
      <div class="homepage-skill-grid">
        <div>
          <h3>Languages</h3>
          <p>Python, Shell, C++, Java, CUDA, C#</p>
        </div>
        <div>
          <h3>Frameworks</h3>
          <p>PyTorch, HuggingFace, vLLM, DeepSpeed, Verl, Ray</p>
        </div>
        <div>
          <h3>Languages</h3>
          <p>Chinese, English</p>
        </div>
      </div>
    </div>
  </section>
</main>
