---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Montserrat:wght@600;700&display=swap');

  /* 全局正文字体与行高优化 */
  body, p, li, a {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    line-height: 1.7;
    color: #374151; 
  }

  /* 标题字体与间距优化 */
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Montserrat', sans-serif !important;
    font-weight: 700;
    color: #111827;
    margin-top: 1.6em;
    margin-bottom: 0.6em;
  }

  b, strong {
    font-weight: 600;
    color: #111827;
  }

  /* --- 研究兴趣标签美化 (极简学术风) --- */
  .research-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin: 12px 0;
  }

  .research-tag {
    background-color: #f8fafc;
    color: #0f172a;
    padding: 6px 14px;
    border-radius: 8px;
    font-size: 0.9em;
    font-weight: 600;
    border: 1px solid #e2e8f0;
    box-shadow: 0 1px 2px rgba(0,0,0,0.03);
    display: flex;
    align-items: center;
    transition: all 0.2s ease;
  }

  /* 添加学术风的高级蓝色小圆点作为 Icon */
  .research-tag::before {
    content: "";
    display: inline-block;
    width: 6px;
    height: 6px;
    background-color: #0284c7; /* 与主题蓝呼应 */
    border-radius: 50%;
    margin-right: 8px;
  }

  .research-tag:hover {
    border-color: #cbd5e1;
    transform: translateY(-1px);
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

  /* --- 实习经历专属美化 (时间线胶囊版) --- */
  .exp-list {
    padding-left: 0;
    list-style: none;
    margin-top: 15px;
  }
  
  .exp-list li {
    margin-bottom: 1.5em; 
    padding-left: 16px;
    border-left: 3px solid #e2e8f0;
    transition: border-color 0.3s ease;
  }

  .exp-list li:hover {
    border-left-color: #93c5fd; 
  }

  .exp-title {
    font-size: 1.1em;
    font-family: 'Montserrat', sans-serif !important; 
    font-weight: 700;
    color: #111827;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 6px; 
  }

  .exp-program {
    font-family: 'Inter', sans-serif !important;
    font-weight: 600;
    color: #0369a1; 
    background-color: #e0f2fe; 
    padding: 3px 12px;
    border-radius: 20px; 
    font-size: 0.75em;
    letter-spacing: 0.5px; 
  }

  .exp-desc {
    font-family: 'Inter', sans-serif !important;
    color: #64748b; 
    font-size: 0.95em;
    line-height: 1.6;
  }

  /* --- 论文列表专属美化 (纯HTML结构，100%稳定) --- */
  .pub-list {
    padding-left: 20px;
    margin-top: 10px;
  }
  
  .pub-list li {
    margin-bottom: 1.5em; 
    line-height: 1.6;
  }
  
  /* 将斜体的会议名称渲染为高亮标签 */
  .pub-list em {
    font-style: normal;
    font-weight: 600;
    color: #0284c7; 
    background-color: #f0f9ff; 
    padding: 2px 8px;
    border-radius: 6px;
    font-size: 0.9em;
    margin-right: 8px;
    display: inline-block;
    margin-top: 4px;
  }

  /* 将 Paper/Code 链接渲染为现代按钮 */
  .pub-list a.btn {
    display: inline-block;
    background-color: #f3f4f6;
    color: #374151 !important;
    padding: 3px 10px;
    border-radius: 6px;
    font-size: 0.85em;
    font-weight: 500;
    text-decoration: none !important;
    border: 1px solid #e5e7eb;
    transition: all 0.2s ease-in-out;
    margin-right: 5px;
    margin-top: 4px;
  }
  
  .pub-list a.btn:hover {
    background-color: #e5e7eb;
    transform: translateY(-1px);
    box-shadow: 0 2px 5px rgba(0,0,0,0.08);
  }
</style>

<div style="text-align:center; background: linear-gradient(135deg, #f0f7ff 0%, #e0f2fe 50%, #bae6fd 100%); padding:18px; border-radius:12px; margin-bottom:25px; color: #0369a1; font-family: 'Montserrat', sans-serif; box-shadow: 0 4px 12px rgba(0,0,0,0.03);">
  <h2 style="font-size:1.6em; margin:0; border-bottom: none; text-decoration: none; color: #0c4a6e;">
    👋 Welcome to <span style="color:#0284c7;">Rui Li</span>'s Homepage
  </h2>
</div>

## 🧑‍🎓 About Me

My name is Rui Li. I am currently a third-year PhD candidate in Renmin University of China, supervised by [Prof. Xu Chen](https://scholar.google.com/citations?user=loPoqy0AAAAJ&hl=en&oi=ao). Before embarking on my PhD journey, I received my BSc and MSc degrees in Computer Science at Dalian University of Technology, under the guidance of [Prof. Yanming Shen](https://scholar.google.com/citations?user=MvlgpWcAAAAJ&hl=en&oi=ao). 

My current research mainly focuses on:
<div class="research-tags">
  <span class="research-tag">Agentic Memory</span>
  <span class="research-tag">LLM-Based Multi-Agent Systems</span>
  <span class="research-tag">Self-Evolving LLM Agents</span>
</div>
I also maintain a strong interest in GNNs and Knowledge Graphs, particularly their interactions with LLM systems.

## 🗞️ News

- 🎉 One paper about agent optimization has been accepted by **ICLR 2026**.
- 🎉🎉 Two papers about LLM memory have been accepted by **NeurIPS 2025**.
- 🎉 One paper about RAG has been accepted by **KDD 2025**.
- 🎉 One paper about KG has been accepted by **ICML 2024**.
- 🎉 One paper about KG has been accepted by **ACL 2023**.
- 🎉🎉 Two papers about KG and GNN have been accepted by **ICML 2022**.

<div style="background-color: #fffbeb; border-left: 4px solid #f59e0b; padding: 12px 18px; margin: 25px 0; border-radius: 4px;">
  <p style="color: #92400e; margin: 0; font-size: 0.95em;">💡 I expect to graduate in June 2027. I am currently seeking internship opportunities related to <b>LLM Agents</b>, particularly focusing on <b>Multi-Agent Systems</b> and <b>Agentic Memory</b>. Please feel free to contact me if you are interested in my research or background.</p>
</div>

## 🧑‍💻 Internship Experiences

<ul class="exp-list">
  <li>
    <div class="exp-title">ByteDance TikTok <span class="exp-program">Soaring Star Talent Intern Program</span></div>
    <div class="exp-desc">Worked on personalized memory system design for Tako.</div>
  </li>
  <li>
    <div class="exp-title">Xiaohongshu <span class="exp-program">AI Search</span></div>
    <div class="exp-desc">Worked on multi-agent systems and agentic RL.</div>
  </li>
  <li>
    <div class="exp-title">Huawei Noah's Ark Lab <span class="exp-program">Agentic Memory</span></div>
    <div class="exp-desc">Worked on LLM agentic memory and self-bootstrapping retrieval-augmented generation.</div>
  </li>
  <li>
    <div class="exp-title">Microsoft Research Asia <span class="exp-program">Graph Learning</span></div>
    <div class="exp-desc">Worked on knowledge representation learning and joint training of GNNs & LMs.</div>
  </li>
</ul>

## 📚 Selected Publications

<ul class="pub-list">
  <li>
    <b>Towards Adaptive, Scalable, and Robust Coordination of LLM Agents: A Dynamic Ad-Hoc Networking Perspective</b><br>
    <b>Rui Li</b>, Zeyu Zhang, Xiaohe Bo, Quanyu Dai, Chaozhuo Li, Feng Wen, Xu Chen<br>
    <em>Under Review</em> 
    <a href="https://arxiv.org/pdf/2602.08009" class="btn">📄 Paper</a>
  </li>

  <li>
    <b>Prompt and Parameter Co-Optimization for Large Language Models</b><br>
    Xiaohe Bo*, <b>Rui Li</b>*, Zexu Sun, Quanyu Dai, Zeyu Zhang, Zihang Tian, Xu Chen, Zhenhua Dong<br>
    <em>ICLR 2026</em> 
    <a href="https://arxiv.org/pdf/2509.24245" class="btn">📄 Paper</a>
  </li>

  <li>
    <b>CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension</b><br>
    <b>Rui Li</b>, Zeyu Zhang, Xiaohe Bo, Zihang Tian, Xu Chen, Quanyu Dai, Zhenhua Dong, Ruiming Tang<br>
    <em>NeurIPS 2025</em> 
    <a href="https://arxiv.org/abs/2510.05520" class="btn">📄 Paper</a> 
    <a href="https://github.com/rui9812/CAM" class="btn">💻 Code</a>
  </li>

  <li>
    <b>KnowTrace: Bootstrapping Iterative Retrieval-Augmented Generation with Structured Knowledge Tracing</b><br>
    <b>Rui Li</b>, Quanyu Dai, Zeyu Zhang, Xu Chen, Zhenhua Dong, Ji-Rong Wen<br>
    <em>KDD 2025</em> 
    <a href="https://arxiv.org/pdf/2505.20245" class="btn">📄 Paper</a> 
    <a href="https://github.com/rui9812/KnowTrace" class="btn">💻 Code</a>
  </li>

  <li>
    <b>Generalizing Knowledge Graph Embedding with Universal Orthogonal Parameterization</b><br>
    <b>Rui Li</b>, Chaozhuo Li, Yanming Shen, Zeyu Zhang, Xu Chen<br>
    <em>ICML 2024</em> 
    <a href="https://arxiv.org/pdf/2405.08540" class="btn">📄 Paper</a> 
    <a href="https://github.com/rui9812/GoldE" class="btn">💻 Code</a>
  </li>

  <li>
    <b>To Copy Rather Than Memorize: A Vertical Learning Paradigm for Knowledge Graph Completion</b><br>
    <b>Rui Li</b>, Xu Chen, Chaozhuo Li, Yanming Shen, Jianan Zhao, Yujing Wang, Weihao Han, Hao Sun, Weiwei Deng, Qi Zhang, Xing Xie<br>
    <em>ACL 2023 Main Conference</em> 
    <a href="https://arxiv.org/pdf/2305.14126" class="btn">📄 Paper</a> 
    <a href="https://github.com/rui9812/VLP" class="btn">💻 Code</a>
  </li>

  <li>
    <b>HousE: Knowledge Graph Embedding with Householder Parameterization</b><br>
    <b>Rui Li</b>, Jianan Zhao, Chaozhuo Li, Di He, Yiqi Wang, Yuming Liu, Hao Sun, Senzhang Wang, Weiwei Deng, Yanming Shen, Xing Xie, Qi Zhang<br>
    <em>ICML 2022</em> 
    <a href="https://proceedings.mlr.press/v162/li22ab/li22ab.pdf" class="btn">📄 Paper</a> 
    <a href="https://github.com/rui9812/HousE" class="btn">💻 Code</a>
  </li>

  <li>
    <b>A New Perspective on the Effects of Spectrum in Graph Neural Networks</b><br>
    Mingqi Yang, Yanming Shen, <b>Rui Li</b>, Heng Qi, Qiang Zhang, Baocai Yin<br>
    <em>ICML 2022</em> 
    <a href="https://proceedings.mlr.press/v162/yang22n/yang22n.pdf" class="btn">📄 Paper</a> 
    <a href="https://github.com/qslim/gnn-spectrum" class="btn">💻 Code</a>
  </li>
</ul>

## 🏆 Awards

- Outstanding Innovative Talents Cultivation Programs, 2024-2025.
- Outstanding Master's Thesis in Liaoning Province, 2023.
- National Scholarship for Postgraduate Students, 2022.
- Outstanding Graduate Student, Dalian University of Technology, 2022.
- Outstanding Undergraduate Graduate, Dalian University of Technology, 2020.
- First-class Academic Scholarship, Dalian University of Technology, 2017-2019.

---

<div style="text-align: center; margin-top: 50px;">
  <script type="text/javascript" id="clustrmaps" 
    src="//clustrmaps.com/map_v2.js?d=rExufzDkijQ4_HMmB45Q83dI6zdMP7Lcp9TTwd-MUJA&cl=ffffff&w=320&t=tt">
  </script>
</div>
