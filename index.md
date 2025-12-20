---
layout: page
title: Is the Gaming community the best community on YouTube ?
subtitle: 
cover-img: /assets/img/background_picture.png
cover-img-opacity: 0.35
---

<p style="text-align:center; margin-top:20px; margin-bottom:35px;">
  <img src="/assets/img/introduction_image.png" 
       alt="Introduction illustration"
       style="width:1000px; border-radius:0px">
</p>

<style>
  .intro-block {
    display: flex;
    gap: 26px;
    align-items: flex-start;
    margin: 25px 0 35px 0;
  }

  .intro-img {
    flex: 0 0 34%;       
    max-width: 300px;
  }

  .intro-img img {
    width: 100%;
    border-radius: 0px;
    display: block;
  }

  .intro-text {
    flex: 1;
    font-size: 1.05rem;
    line-height: 1.7;
  }

  @media (max-width: 700px) {
    .intro-block {
      flex-direction: column;
    }
    .intro-img {
      max-width: none;
      width: 100%;
    }
  }
</style>

<div class="intro-block">
  <div class="intro-img">
    <img src="/assets/img/gamer_intro.png" alt="Gamer watching gaming videos">
  </div>

  <div class="intro-text">
    <p>
      Imagine the scene from a parent’s point of view: it’s late, the hallway light is on, and loud explosions and excited voices spill out from behind a half-closed bedroom door. Inside, a teenager sits in front of a screen, headset on, laughing with strangers online instead of doing what seems “productive.”

    </p>

    <p>
      From the outside, it looks like noise, distraction, and wasted time. But inside that room, something very different is happening.
    </p>
  </div>
</div>

<p>
For many of us, growing up meant spending hours on YouTube watching gaming videos — learning strategies, sharing jokes, celebrating wins, and venting frustration together. These weren’t just videos. They were shared experiences. Viewers weren’t passive spectators; they were active participants in a space that felt welcoming and familiar.
</p>

<p>
Gaming content didn’t just entertain. It connected people. It created communities that felt real, supportive, and alive — even through a screen.
</p>

<p style="font-weight:700; font-size:1.15rem; color:#2b8cff;">
But was that sense of belonging truly unique to the gaming community? Or was it simply nostalgia shaping our perception?</p>

<p>
Today, with access to data and analytical tools, we can move beyond personal memories and examine YouTube objectively. This project explores one central question:
</p>

<style>
  .frame-container {
    position: relative;
    max-width: 1000px;
    margin: 40px auto 60px auto;
  }

  .frame-img {
    width: 100%;
    display: block;
  }

  .frame-content {
    position: absolute;
    top: 10%;
    left: 15%;
    width: 70%;
    height: 64%;
    display: flex;
    flex-direction: column;
    justify-content: center;

    text-align: left;
    padding: 20px 30px;

    /* optional for readability */
    border-radius: 16px;
  }

  .frame-content h2 {
    text-align: center;
    color: #2b8cff;
    margin-bottom: 16px;
    font-size: 1.5rem;
  }

  .frame-content ul {
    margin: 0;
    padding-left: 22px;
    font-size: 1.05rem;
    line-height: 1.7;
  }

  .frame-content li {
    margin-bottom: 10px;
  }

  @media (max-width: 768px) {
    .frame-content {
      top: 14%;
      left: 12%;
      width: 88%;
      height: 72%;
      font-size: 0.95rem;
    }
  }
</style>


<div class="frame-container">
  <img src="/assets/img/research_question.png"
       alt="Research questions frame"
       class="frame-img">

  <div class="frame-content">
    <h2>Research Questions</h2>
    <ul>
      <li>
        Are there real differences in the users' interactions with videos between categories ? What kind ?
      </li>
      <li>
        Are there real differences in the users' interactions with channels between cateogries ? What kind ?
      </li>
      <li>
        Are there categories' communities that are tighter than others ? How so ?
      </li>
      <li>
        Are there categories that are more dynamic than others ? How so ?
      </li>
      <li>
       Is it possible to identify one or different cultures, as well as their importance, emanating from those categories ?
      </li>
      <li>
      Is it possible to identify and quantify the communities within the categories ?
      </li>
    </ul>
  </div>
</div>

<!-- ========================= -->
<!-- How are we going to solve this? (YouNiverse) -->
<!-- Plug this right after your Research Questions block -->
<!-- ========================= -->

<style>
  .solution-wrap {
    max-width: 1000px;
    margin: 10px auto 60px auto;
  }

  .solution-title {
    font-size: 2rem;
    font-weight: 800;
    margin: 0 0 18px 0;
  }

  .solution-card {
    border-radius: 0px;
    padding: 26px 28px;
    line-height: 1.8;
    font-size: 1.05rem;
    background: rgba(255, 255, 255, 0.02);
  }

  .solution-lead {
    margin-top: 0;
    margin-bottom: 14px;
  }

  .solution-highlight {
    font-weight: 700;
    color: #2b8cff;
  }

  .solution-metrics {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 14px;
    margin: 22px 0 10px 0;
  }

  .metric-box {
    border-radius: 0px;
    padding: 14px 14px;
    border: 1px solid rgba(255, 255, 255, 0.10);
    background: rgba(0, 0, 0, 0.12);
  }

  .metric-num {
    font-size: 1.25rem;
    font-weight: 800;
    color: #2b8cff;
    margin: 0 0 4px 0;
  }

  .metric-label {
    margin: 0;
    opacity: 0.9;
    font-size: 0.95rem;
    line-height: 1.35;
  }

  .solution-divider {
    height: 1px;
    background: rgba(255, 255, 255, 0.12);
    margin: 18px 0 18px 0;
  }

  .solution-list {
    margin: 0;
    padding-left: 22px;
  }

  .solution-list li {
    margin-bottom: 10px;
  }

  .solution-note {
    margin: 16px 0 0 0;
    opacity: 0.95;
  }

  @media (max-width: 900px) {
    .solution-metrics {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  @media (max-width: 600px) {
    .solution-title {
      font-size: 1.6rem;
    }
    .solution-card {
      padding: 20px 18px;
      font-size: 1rem;
    }
    .solution-metrics {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="solution-wrap">
  <h1 class="solution-title">How are we going to solve this?</h1>

  <div class="solution-card">
    <p class="solution-lead">
      Up to now, we’ve been talking about a feeling : that sense that Gaming on YouTube was
      <span class="solution-highlight">more than content</span>.
      But nostalgia isn’t proof. So we decided to do what we couldn’t do as kids:
      step back, and test it with real evidence.
    </p>

    <p>
      Our main tool is <span class="solution-highlight">YouNiverse</span>, a large-scale dataset built from YouTube.
      Instead of looking at a few famous creators or a couple of viral clips, it captures the platform at
      community level, so we can observe how categories behave, how audiences interact, and how creators connect.
    </p>

    <div class="solution-metrics">
      <div class="metric-box">
        <p class="metric-num">136k+</p>
        <p class="metric-label">YouTube channels</p>
      </div>
      <div class="metric-box">
        <p class="metric-num">~72.9M</p>
        <p class="metric-label">videos (2005 → 2019)</p>
      </div>
      <div class="metric-box">
        <p class="metric-num">Weekly</p>
        <p class="metric-label">views & subscribers time series (most channels)</p>
      </div>
      <div class="metric-box">
        <p class="metric-num">~449M</p>
        <p class="metric-label">anonymous users linked to commented videos</p>
      </div>
    </div>

    <div class="solution-divider"></div>

    <p>
      Why does this matter for our question? Because community strength on YouTube isn’t just about views.
      It’s about <span class="solution-highlight">interaction</span>:
      who shows up, who returns, who clusters around the same creators, and how tightly those clusters hold together.
    </p>

    <ul class="solution-list">
      <li>
        We compare <span class="solution-highlight">engagement signals</span> across categories
        (how often viewers interact, and how concentrated those interactions are).
      </li>
      <li>
        We model YouTube as a <span class="solution-highlight">network</span>:
        channels as nodes, user interactions as links.
      </li>
      <li>
        We detect <span class="solution-highlight">sub-communities</span> inside Gaming and measure how cohesive they are.
      </li>
      <li>
        We check whether Gaming looks structurally different —
        denser, more interconnected, and more “home-like” than other categories.
      </li>
    </ul>

    <p class="solution-note">
      If Gaming truly is the strongest community, it shouldn’t just be a memory.
      It should show up in the data as a measurable pattern.
    </p>
  </div>
</div>

---

## Project in order

- Pre-processing explained to deal with large dataset
- ML clustering?
- Hypothesis Testing
- Results from P2 (adapted to the new data pre-process?)
  

