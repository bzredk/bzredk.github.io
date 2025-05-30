---
layout: about
title: about
permalink: /

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: ""
selected_papers: false
social: false
announcements:
  enabled: false
  scrollable: true
  limit: 5
latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<!-- 顶部：照片右侧大名/单位/社交 -->
<div style="display:flex;align-items:flex-start;gap:2.5rem;flex-wrap:wrap;margin-bottom:2.5rem;">
  <div style="flex:0 0 auto;max-width:320px;">
    <img src="{{ site.baseurl }}/assets/img/prof_pic.jpg" alt="profile picture" style="width:100%;max-width:320px;height:auto;border-radius:4px;">
  </div>
  <div style="flex:1 1 320px;min-width:260px;max-width:480px;display:flex;flex-direction:column;justify-content:space-between;height:320px;">
    <div>
      <div style="font-size:2.5rem;font-weight:bold;text-transform:uppercase;line-height:1.1;">ZHIRUI BIAN <span style="font-size:1.5rem;font-weight:normal;vertical-align:middle;">(卞直瑞)</span></div>
      <div style="font-size:1.1rem;margin:0.5rem 0 0.5rem 0;color:#aaa;">Master's Student, Computer & Information Science Department,<br>University of Pennsylvania</div>
      <div style="font-size:1.05rem;margin-bottom:1.2rem;">bzredk@seas.upenn.edu</div>
    </div>
    <div style="display:flex;align-items:center;gap:0.7em;">
      <a href="mailto:bzredk@seas.upenn.edu"><i class="fas fa-envelope" style="font-size:2.4em;"></i></a>
      <a href="mailto:bzr962166649@gmail.com"><i class="fas fa-envelope-open" style="font-size:2.4em;"></i></a>
      <a href="https://www.linkedin.com/in/zhirui-bian-65857526b/" target="_blank"><i class="fab fa-linkedin" style="font-size:2.4em;"></i></a>
      <a href="https://scholar.google.com.hk/citations?user=vmCWvc8AAAAJ&hl=zh-CN" target="_blank"><i class="ai ai-google-scholar-square" style="font-size:2.4em;"></i></a>
    </div>
  </div>
</div>

<!-- 照片下方：自我介绍 -->
<div style="max-width:1200px;margin:0 auto 2.5rem auto;font-size:1.15rem;">
I am <b>ZHIRUI BIAN</b> (Ray/Redk), currently a master's student in the CIS Department at the University of Pennsylvania.
</div>

<!-- 纵向结构：Research Interest、Previously、Research & Publications -->
<div style="max-width:1200px;margin:0 auto 2.5rem auto;">
  <div style="margin-bottom:2rem;text-align:justify;">
    <h3 style="margin-bottom:0.5rem;">Research Interest</h3>
    My current research focuses on <b>natural-language processing and large-scale language models</b> under the supervision of <a href="https://www.cis.upenn.edu/~ccb/" target="_blank">Prof. Chris Callison-Burch</a>. I am also fascinated by <b>learning theory</b> and the fundamental principles that underpin how models learn and generalize from data. I am particularly interested in <b>bridging NLP/LLM technologies with building science</b>, and have recently started investigating <b>reasoning capabilities in large language models</b>.<br><br>
    My interdisciplinary background bridges <b>computer science, building science, and computational design</b>, and I am passionate about developing intelligent systems that make our built environment more sustainable and responsive.
  </div>
  <div style="margin-bottom:2rem;text-align:justify;">
    <h3 style="margin-bottom:0.5rem;">Previously</h3>
    Prior to joining Penn CIS, I completed the <b>Environmental Building Design (EBD)</b> program at Penn's Weitzman School of Design, where I was advised by <a href="https://www.design.upenn.edu/people/william-w-braham" target="_blank">Prof. William Braham</a>, with a <b>LEED Green Associate</b> credential, on environmental simulation and performance-driven architectural design.<br><br>
    I received my <b>B.Eng.</b> degree from <b>Nanjing University</b>, China, where I was awarded the <b>National Scholarship</b> and recognized as <b>the Outstanding Student</b>.
  </div>
  <div style="margin-bottom:2rem;">
    <h3 style="margin-bottom:0.5rem;"><a href="/publications/" style="color:inherit;text-decoration:none;">Research & Publications</a></h3>
    <div class="publications">
      {% bibliography --query @*[selected=true]* --group_by none %}
    </div>
  </div>
</div>

<!-- Interests -->
<div style="margin:1.5rem 0 1.5rem 0;font-size:1rem;color:#888;"><b>Interests:</b> Basketball & Tennis &bull; Singing & Music &bull; Drawing & Digital Art &bull; Pokémon Games &bull; Romance of the Three Kingdoms (strategy games)</div>
