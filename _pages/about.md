---
permalink: /
title: "Hello, I'm Jaehyeong Cho!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![AI-enhanced HCI concept](/images/my%20dream.png){: .align-right width="320" }

I’m a CS undergraduate at **Yonsei University**


Growing up, games were my main way to connect with people. That experience, combined with my love for math and logic, shaped my goal: to build programs that bring people together or help them share meaningful fun.


I’m interested in creating immersive interaction—using **AI** to make human-computer interaction feel more natural and lifelike. While I’m early on hands-on experience, I’m building foundations through coursework (e.g., deep neural networks and related topics).


Also, I enjoy algorithmic problem solving and thrive learning with peers in contests and study groups.

## Education

| Degree | Institution | Period | Details          |
|---|---|---|------------------|
| B.S. in Computer Science | Yonsei University, Seoul, South Korea | Mar 2023 – Present | GPA **3.86/4.3** |

**Relevant Coursework:** Data Structures, Internet Programming, Object-Oriented Programming


## Projects

<style>
.proj{
  display:grid;
  grid-template-columns: 60% 40%; /* text 60% | image 40% */
  gap:1.25rem;
  align-items:center;
  margin:1.25rem 0;
  padding:1rem;
  border:1px solid #e5e7eb;
  border-radius:12px;
  background:#fff;
}
.proj .txt{line-height:1.7}
.proj .txt p{font-size:1.0rem; line-height:1.65;} /* ↓ 본문만 살짝 축소 */
.proj h3{margin:0 0 .25rem 0}
.proj .meta{font-size:.95rem;color:#6b7280;margin:.25rem 0 .75rem 0}
.proj .img img{
  width:100%;
  height:auto;
  display:block;
  border-radius:10px;
  object-fit:cover;
}
.proj.noimg{grid-template-columns:1fr}
.proj.noimg .img{display:none}
@media (max-width: 820px){
  .proj{grid-template-columns: 1fr}
  .proj .img{order:2}
}
</style>

<div class="proj">
  <div class="txt">
    <h3>Where2Meet (2025)</h3>
    <p class="meta">Web app · Node.js · Express · MySQL · Google Maps API</p>
    <p>A simple web app that helps groups choose a time and place that feels fair to everyone. It collects each member’s availability and rough location, suggests overlapping time windows, and surfaces accessible meeting spots on a map. I focused on the map experience and the flow between the front end and server so that data moved cleanly and recommendations appeared where people expected them.</p>
  </div>
  <div class="img">
    <img src="/images/where2meet3.png" alt="Where2Meet map and suggested places">
  </div>
</div>

<div class="proj">
  <div class="txt">
    <h3>Genetic Disorder Simulation (2022)</h3>
    <p class="meta">Rule-based simulation · Python (plots)</p>
    <p>I built a rule-based simulation to explore a simple question: how can a lethal dominant disorder persist in a population? Starting from a synthetic population annotated with age, sex, and genotype, the model advances in five-year steps (pairing, births, deaths) and sweeps mortality and fertility weights to examine prevalence changes. Across runs, higher mortality suppressed spread while higher fertility amplified it; under some settings the trait persisted or even grew. The project has clear limits—simplified assumptions and spaghetti code from my high-school days—but it sparked my curiosity and taught me grit through repeated iteration and debugging.</p>
  </div>
  <div class="img">
    <img src="/images/simul.png" alt="Heatmap showing prevalence under mortality/fertility sweeps">
  </div>
</div>

<div class="proj noimg">
  <div class="txt">
    <h3>2D Character Movement & Animation (2021)</h3>
    <p class="meta">Game mechanics · Sprite sheet · State machine</p>
    <p>Implemented basic character control and animation using a sprite-sheet pipeline. Built a small finite-state machine (idle → walk → run → jump/land) with input-driven transitions, per-state frame timing, and sprite flipping on direction changes. Movement used delta-time updates for consistent speed, and a simple ground/collision check to keep motion stable.</p>
  </div>
  <div class="img"></div>
</div>

## Activities

<style>
.xtra{
  display:grid;
  grid-template-columns: 60% 40%; /* text | image */
  gap:1rem;
  align-items:center;
  margin:1rem 0;
  padding:.75rem;                 /* ↓ 세로 높이 살짝 축소 */
  border:1px solid #e5e7eb;
  border-radius:12px;
  background:#fff;
}
.xtra .txt{line-height:1.6}
.xtra .txt p{font-size:.98rem; line-height:1.6; margin:0}
.xtra h3{margin:0 0 .25rem 0}
.xtra .meta{font-size:.9rem;color:#6b7280;margin:.25rem 0 .5rem 0}
.xtra .img img{
  width:100%;
  height:auto;                   /* 비율 유지 */
  display:block;
  border-radius:10px;
  object-fit:cover;
}
.xtra.noimg{grid-template-columns:1fr} /* 이미지 없는 블럭 */
.xtra.noimg .img{display:none}
@media (max-width: 820px){
  .xtra{grid-template-columns:1fr}
  .xtra .img{order:2}
}
</style>

<div class="xtra">
  <div class="txt">
    <h3>Algorithmic Practice — Morigorism Club (2024– )</h3>
    <p>Ongoing problem solving with a study group; ~250 problems across Baekjoon/Codeforces, focusing on graphs, DP, greedy, and clean implementation.</p>
  </div>
  <div class="img">
    <img src="/images/solved%20ac.png" alt="Baekjoon profile/statistics screenshot">
  </div>
</div>

<div class="xtra noimg">
  <div class="txt">
    <h3>Programming Contests</h3>
    <p>Participated in collegiate contests including <strong>ICPC Seoul Regional 2024/2025</strong>, <strong>SUAPC 2025</strong>. </p>
  </div>
  <div class="img"></div>
</div>


<div class="xtra">
  <div class="txt">
    <h3>Teaching — ProTeen Club (Jul–Dec 2024)</h3>
    <p>Mentored elementary students using Entry (block-based) to make small games/animations; learned to scaffold concepts and keep momentum with bite-sized milestones.</p>
  </div>
  <div class="img">
    <img src="/images/proteen.png" alt="Mentoring at ProTeen Club">
  </div>
</div>

## Skills & Abilities

<style>
.meters{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.meter{background:#fff;border:1px solid #e5e7eb;border-radius:10px;padding:10px 12px}
.meter label{display:block;font-weight:600;margin-bottom:6px}
.meter meter{width:100%;height:14px}
@media (max-width:820px){.meters{grid-template-columns:1fr}}
</style>

<div class="meters">
  <div class="meter"><label>C++</label><meter min="0" max="5" value="4"></meter></div>
  <div class="meter"><label>Python</label><meter min="0" max="5" value="4"></meter></div>
  <div class="meter"><label>Java</label><meter min="0" max="5" value="2"></meter></div>
  <div class="meter"><label>HTML / CSS / JS</label><meter min="0" max="5" value="3"></meter></div>
  <div class="meter"><label>Korean (Native)</label><meter min="0" max="5" value="5"></meter></div>
  <div class="meter"><label>English </label><meter min="0" max="5" value="4"></meter></div>
</div>