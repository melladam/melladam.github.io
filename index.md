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

<style>
  .simple-title{
    margin: 28px 0 10px 0;
    font-size: 1.45rem;
    font-weight: 800;
    color: #4A2B6B;
  }

  .simple-list{
    margin: 10px 0 14px 0;
    padding-left: 22px;
    line-height: 1.7;
  }

  .simple-list li{
    margin-bottom: 6px;
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

<p style="font-weight:700; font-size:1.15rem; color:#4A2B6B;">
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
    top: 15%;
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
    color: #4A2B6B;
    margin-bottom: 16px;
    font-size: 1.5rem;
  }

  .frame-content ul {
    margin: 0;
    padding-left: 22px;
    font-size: 1rem;
    line-height: 1.50;
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
    color: #4A2B6B;
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
    color: #4A2B6B;
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
  </div>
</div>

<!-- SIMPLE BLOCK 1 -->
<h2 class="simple-title">A quick reality check: Gaming is not a “small niche”</h2>
<p>
  Before talking about “community strength”, we first look at something objective:
  <strong>how big each category is</strong> on YouTube.
</p>
<p>
  The donut charts below show the share of total <strong>views</strong>, <strong>subscribers</strong>, and <strong>channels</strong>
  across categories (2015–2019). And the takeaway is clear:
  <span class="solution-highlight">Gaming sits among the biggest categories on the platform</span>. It’s indeed a major part of YouTube’s ecosystem — with a large audience, a large creator base,
  and a strong ability to attract subscribers.
</p>

<div class="plotly-block">
  {% include donuts_plotly_snippet.html %}
</div>

<!-- SIMPLE BLOCK 2 -->
<h2 class="simple-title">From “big” to “alive”: does Gaming keep growing over time?</h2>
<p>
  Being big is one thing. But a strong category should also show <strong>momentum</strong>:
  creators keep uploading, audiences keep watching, and the category doesn’t depend on a single viral moment.
</p>
<p>
  To test that, we look at quarterly time series using <strong>delta</strong> metrics:
  how many new views and subscribers appear each quarter (rather than a single total snapshot).
</p>
<p>
  <em>Data note:</em> Youniverse gives us these time series, but coverage is limited to <strong>2015–2019</strong>
  and only includes <strong>English-language</strong> channels with at least <strong>&gt;10k subscribers</strong> and
  <strong>&gt;10 videos</strong>.
</p>

<h2 class="simple-title">A quick methodological warning: dataset composition changes over time</h2>

<p>
  Before interpreting growth curves, we need one sanity check: the dataset is not “static” across time.
  In YouNiverse, the number of channels covered increases sharply, and this expansion is strongly aligned
  with increases in average performance metrics (views/subscribers). This creates a <strong>sampling/composition bias</strong>:
  part of the observed growth may reflect <em>which channels enter the sample</em>, not only real changes in behavior.
</p>

<style>
  .bias-grid{
    max-width: 1000px;
    margin: 22px auto 50px auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 18px;
    align-items: start;
  }
  .bias-card{
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 0px;
    padding: 12px 12px 10px 12px;
    background: rgba(255,255,255,0.02);
  }
  .bias-card img{
    width: 100%;
    height: auto;
    display: block;
  }
  .bias-caption{
    margin: 10px 2px 0 2px;
    font-size: 0.95rem;
    line-height: 1.55;
    opacity: 0.95;
  }
  .bias-caption b{
    color: #4A2B6B;
  }
  @media (max-width: 800px){
    .bias-grid{ grid-template-columns: 1fr; }
  }
</style>

<div class="bias-grid">

  <!-- Plot 1: Dual-axis timeseries -->
  <div class="bias-card">
    <img src="/assets/img/3.1.1.png"
         alt="Average delta views per channel vs dataset sample size over time">
    <p class="bias-caption">
      As the dataset sample size (number of channels) expands, the
      <strong>average delta views per channel</strong> rises too.
      The parallel upward trends suggest that “growth over time” is partly confounded by changing coverage.
    </p>
  </div>

  <!-- Plot 2: Correlation scatter (views) -->
  <div class="bias-card">
    <img src="/assets/img/3.1.2.png"
         alt="Correlation between dataset sample size and average delta views">
    <p class="bias-caption">
      The strong relationship between <strong>sample size</strong> and
      <strong>avg delta views</strong> indicates a composition effect:
      when more channels are included, the measured “average performance” increases.
      So absolute trend levels should be treated as <em>descriptive</em>, not causal.
    </p>
  </div>

  <!-- Plot 3: Dual-axis timeseries (subscribers) -->
  <div class="bias-card">
    <img src="/assets/img/3.3.3.png"
         alt="Average total subscribers per channel vs dataset sample size over time">
    <p class="bias-caption">
      <b>Same pattern with subscribers:</b> the average subscriber count per channel also rises with sample expansion,
      reinforcing that the dataset progressively captures <strong>larger / more established channels</strong> over time.
    </p>
  </div>

  <!-- Plot 4: Correlation scatter (subscribers) -->
  <div class="bias-card">
    <img src="/assets/img/3.3.4.png"
         alt="Correlation between dataset sample size and average subscribers">
    <p class="bias-caption">
      This supports the idea that “bigger sample” ≈ “bigger channels”.
      That’s exactly why we avoid over-interpreting upward time trends as pure community growth.
    </p>
  </div>

</div>

<p>
  From this point onward, we focus on analyses that are more robust to sample expansion:
  <strong>within-channel baselines</strong> (spike detection using rolling medians),
  <strong>ratio-based engagement metrics</strong> (comments/view, likes/view, appreciation),
  and <strong>fair comparisons within subscriber-size clusters</strong>.
  This lets us study community structure and interaction patterns without conflating them with dataset growth.
</p>


<!-- SIMPLE BLOCK 3 -->
<h2 class="simple-title">Gaming in delta: subscribers and views keep moving up</h2>
<p>
  In the dashboard, select <strong>Gaming</strong> and set the metric to <strong>delta</strong>.
  Quarter after quarter, Gaming keeps adding audience attention.
</p>
<p>
  This is a strong signal that Gaming isn’t just popular : it’s <strong>durable</strong>.
  Even when the number of uploaded videos fluctuates, the category keeps generating new views
  and keeps pulling new subscribers.
</p>

<ul class="simple-list">
  <li><strong>Delta views:</strong> shows how much new attention Gaming gained during each quarter</li>
  <li><strong>Delta subscribers:</strong> shows how much new audience Gaming converted during each quarter</li>
  <li><strong>Spikes:</strong> often match “event moments” (big releases, trending games, viral challenges)</li>
</ul>
<div class="plotly-block">
  {% include quarterly_dashboard_all_categories.html%}
</div>

<!-- SIMPLE BLOCK 4 -->
<p>
  The graph illustrate that Gaming is <strong>reactive</strong> (as it spikes) and <strong>stable</strong> (as it keeps growing).
</p>
<p>
  <strong>Views climb sharply over time:</strong> instead of a slow, flat progression, the curve rises quickly,
  which means Gaming keeps capturing new attention quarter after quarter. This is what we expect from a category
  that has become mainstream: more creators join in, more viewers show up, and the audience keeps expanding.
</p>
<p>
  <strong>Uploads don’t follow a perfectly smooth rhythm:</strong> The number of videos posted per quarter goes up and down,
  which is normal for a fast-moving ecosystem: production often follows external timing (big releases, seasonal periods,
  major online trends), and creators adapt their output accordingly. What matters is that even with these variations,
  Gaming continues to accumulate views and stay active.
</p>

<p>
  If Gaming combines <strong>scale</strong> (it represents a large part of YouTube) with <strong>momentum</strong>
  (its quarterly changes keep moving upward), then it already looks like a category powered by a strong creator base
  and a loyal audience. 
</p>
<p>
  Now that we have the <strong>big picture</strong>, we can zoom in and <strong>compare categories</strong> by looking at how their
  time series evolve—i.e., how their deltas rise, fall, or stabilize over time.
</p>


<h2 class="simple-title">A relative check: how does Gaming rank each year?</h2>

<p>
  Absolute growth can be misleading when the dataset changes over time. So we also look at a simpler signal:
  <strong>yearly ranks</strong> across categories (1 = best) for <strong>views</strong>, <strong>subs</strong>, and <strong>uploads</strong>.
</p>

<style>
  .table-card{
    max-width: 1000px;
    margin: 18px auto 50px auto;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 0px;
    padding: 12px;
    background: rgba(255,255,255,0.02);
  }
  .table-card img{
    width: 100%;
    height: auto;
    display: block;
  }
  .table-caption{
    margin: 10px 2px 0 2px;
    font-size: 0.95rem;
    line-height: 1.55;
    opacity: 0.95;
  }
</style>

  <img src="/assets/img/4.2.png"
       alt="Category rankings by year for subs, videos and views">


<h2 class="simple-title">How categories evolve over time (All categories)</h2>

<p>
  Before focusing specifically on Gaming, we briefly contextualize it by looking at how
  <strong>all categories</strong> evolve over time in terms of dataset coverage, attention,
  subscriber base, and upload activity.
</p>

<img src="/assets/img/5.1.png"
     alt="Number of unique channels per category over time"
     style="width:100%; margin:30px auto 10px auto; display:block;">

<p style="max-width:1000px; margin:0 auto 40px auto;">
  The number of tracked channels increases steadily across all categories,
  confirming that dataset coverage expands over time.
</p>

<img src="/assets/img/5.2.png"
     alt="Average delta views per channel over time for all categories"
     style="width:100%; margin:30px auto 10px auto; display:block;">

<p style="max-width:1000px; margin:0 auto 40px auto;">
  Categories differ strongly in their typical view gains,
  motivating the use of relative and within-channel metrics rather than raw levels.
</p>

<img src="/assets/img/5.3.1.png"
     alt="Average total subscribers per channel over time for all categories"
     style="width:100%; margin:30px auto 10px auto; display:block;">

<p style="max-width:1000px; margin:0 auto 40px auto;">
  Subscriber bases grow across most categories, but at different speeds,
  reinforcing the need for careful cross-category comparison.
</p>

<img src="/assets/img/5.4.png"
     alt="Average delta videos per channel over time for all categories"
     style="width:100%; margin:30px auto 10px auto; display:block;">

<p style="max-width:1000px; margin:0 auto 60px auto;">
  Upload dynamics vary substantially between categories,
  helping explain differences in volatility and spike behavior observed later.
</p>


<h2 class="simple-title">How categories evolve over time (All categories)</h2>
<h2 class="simple-title">Zooming in: Gaming category dynamics</h2>

<p>
  After looking at global category trends, we now focus specifically on <strong>Gaming</strong>.
  The goal is to understand how Gaming channels evolve over time in terms of views, uploads, and subscriber growth,
  while keeping in mind the dataset expansion effect discussed earlier.
</p>

<img src="/assets/img/6.2.1.png"
     alt="Average delta views per gaming channel over time"
     style="width:100%; margin:30px auto 10px auto; display:block;">
     
<p style="max-width:1000px; margin:0 auto 40px auto;">
  Similarly to what we saw previously, in 2017 average monthly delta views per Gaming channel seem to drop.
  With the expansion of the dataset both the mean and the standard deviation increase abruptly in the second half of 2017
  and then seem to show constant growth for the rest of the studied period.
  We don't have enough data to show any seasonal pattern with certainty.
  However, in 2018–2020 we observe recurring peaks during the summer, which could plausibly be linked to school vacations
  and higher activity among young audiences.
</p>

<img src="/assets/img/6.2.2.png"
     alt="Average delta videos per gaming channel over time"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  Looking at average monthly delta videos (new uploads) per gaming channel confirms the unreliability of early data in 2016–2017.
  From 2018 to 2020 we observe a slight decrease in the average monthly upload rate, while the standard deviation increases.
  On average, channels are posting roughly one less video per month in 2020 compared to 2018, suggesting a shift in production dynamics.
</p>

<img src="/assets/img/6.2.3.png"
     alt="Average delta subscribers per gaming channel over time"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  Despite the decrease in upload frequency, new subscribers increase steadily from around 32k per month in 2018 to about 52k in 2020.
  This suggests that the category continues to grow and attract new audiences even as posting slows down.
</p>

<img src="/assets/img/6.2.4.png"
     alt="Average total subscribers per gaming channel over time"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  Unlike delta subscribers (monthly gains), <strong>total subscribers</strong> represents the absolute audience size.
  The average gaming channel grows from roughly 115,736 subscribers in 2018 to about 186,486 in 2020.
  The growth is clearly positive, although it is slower than in some other categories.
</p>

<img src="/assets/img/6.3.1.png"
     alt="Monthly delta subscribers for top 10 gaming channels"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  This plot shows an interesting event in the gaming community: a major peak in late 2019 in PewDiePie’s delta subscribers.
  This corresponds to a well-known subscriber competition event where many users subscribed massively, highlighting how
  community-driven dynamics can create sudden surges in engagement.
</p>

<img src="/assets/img/6.3.2.png"
     alt="Total subscribers for top 10 gaming channels"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  This plot shows the <strong>total subscriber count</strong> for each of the top 10 gaming channels over time,
  reflecting absolute audience size rather than growth rates.
</p>

<img src="/assets/img/6.3.3.png"
     alt="Monthly delta videos for top 10 gaming channels"
     style="width:100%; margin:30px auto 10px auto; display:block;">
<p style="max-width:1000px; margin:0 auto 40px auto;">
  By looking at monthly delta videos for top gaming channels, we clearly see the decrease in upload frequency analyzed above.
  From 2019 onward, channels like Markiplier and jacksepticeye go from roughly 50–70 monthly uploads down to 20–30,
  reflecting a shift in production/consumption patterns in Gaming content.
</p>






<p>
  With that relative context in mind, we now zoom into <strong>spikes</strong> to compare categories more fairly,
  using within-channel baselines rather than raw totals.
</p>


<h3>Defining “Spikes” to Compare Categories Fairly</h3>
<p>
  To make that comparison fair, we also introduced a simple idea: a <strong>spike</strong>. In practice, a spike is a week where a
  category suddenly “jumps” far above its usual level. We first define what a <em>normal</em> week looks like for each category
  (using its typical weekly view gain), and then we flag the weeks that are at least <strong>2× higher</strong> than that baseline.
  Once those spike weeks are identified, we can ask a more interesting question: when a category surges, is it because the whole
  ecosystem moves together, or because a handful of channels (sometimes even one) captures most of the extra views?
</p>

<div class="plotly-block">
  {% include spike_concentration_plot.html%}
</div>

<p>
  The interactive chart below zooms in on those <strong>spike weeks</strong> and asks a simple question: when a category spikes,
  <em>how concentrated is that spike?</em> For every week flagged as a spike, we compute the share of that week’s
  <strong>delta views</strong> captured by the <strong>top 10 channels</strong> in the category. Each dot is one spike week,
  and the box summarizes the distribution (median and spread) across all spike weeks for that category.
</p>
<p>
  Interpreting it is straightforward: a <strong>higher</strong> top-10 share means spikes are often driven by a small set of
  big channels; a <strong>lower</strong> share means the surge is more broadly shared across creators. And here, the signal is
  especially clear: <strong>Gaming has the lowest median</strong> top-10 share (around <strong>~11%</strong>) of all categories.
  In other words, even when Gaming “spikes”, the extra views are <strong>the least concentrated</strong> and are spread across
  many channels, not captured by a handful of spike-makers. That’s a strong sign of a category built on a deep, resilient creator
  ecosystem.
</p>

<h3>Measuring Spike Magnitude Across Categories</h3>

<p>
  Once we’ve seen <em>how concentrated</em> spike weeks are, the next step is to measure <strong>how intense</strong> those spikes get.
  In other words: when a category surges, is it a small bump—or a massive jump?
</p>
<p>
  To answer that, we switch from a category-wide view to a <strong>channel-level</strong> spike detector: for every channel, we estimate
  what a “normal” week looks like using a <strong>rolling median</strong> of weekly new views over the past <strong>~52 weeks</strong>
  (with at least 13 weeks of history). This matters because YouTube grows over time, so a week in 2019 should be compared to that same
  channel’s recent baseline, not to its early 2015 numbers. A week is then labeled a spike when its <code>delta_views</code> is at least
  <strong>2×</strong> the rolling median. Finally, we aggregate all detected spikes back up to the <strong>category</strong> level to
  summarize the distribution of spike magnitudes (median, percentiles, max) and the overall “spike impact” in absolute views.
  The results below show which categories have the most intense spikes—and which ones grow in a steadier, less bursty way.
</p>

<div class="plotly-block">
  {% include spikes_frequency_bar.html%}
</div>
<p>
Gaming has the highest spike frequency of all categories, with roughly 20% of channel-weeks flagged as spikes. This shows that sudden jumps in views are a routine part of how Gaming channels grow, not rare exceptions. Compared to other categories, Gaming content experiences sharp bursts of attention much more often, reflecting a highly event-driven and volatile ecosystem.
</p>


<div class="plotly-block">
  {% include spikes_tail_scatter.html%}
</div>
<p>
Gaming stands out strongly when looking at the most extreme spikes. Its very high 90th-percentile spike magnitude, combined with one of the largest single spikes observed, shows that Gaming’s biggest moments are far more intense than those in other categories. This heavier tail means that viral Gaming events are not only frequent, but also unusually powerful.
</p>

<div class="plotly-block">
  {% include spikes_totalviews_scatter.html%}
</div>
<p>
Gaming combines large relative spikes with large absolute impact. When a Gaming channel spikes, views often increase by more than four times a normal week, and these surges translate into substantial total view counts. The large bubble size indicates that this effect comes from many channels spiking together, rather than a small number of isolated viral videos.
</p>


<div class="plotly-block">
  {% include spikes_universal_scatter.html%}
</div>
<p>
Spikes in Gaming are nearly universal across the category, with almost all channels experiencing at least one spike over time. Unlike many other categories, Gaming also pairs this wide participation with higher typical spike magnitudes. In practice, this means that spikes are both widespread and meaningful for most Gaming creators, not limited to a small top tier.
</p>

<!-- Simple repeatable block -->
<h2 class="simple-title">From attention to interaction: do Gaming viewers engage differently?</h2>
<p>
Up to now, we’ve looked at YouTube from a distance:
<strong>views</strong>, <strong>growth</strong>, <strong>spikes</strong>.
But community is not just about <strong>how many people show up</strong> :
it’s about what they do once they’re there.
</p>

<p>
Do viewers simply watch and leave? Or do they like, comment, react, and come back?
</p>

<p>
To answer this, we move from platform-level dynamics to
<strong>viewer interaction metrics</strong>,
and we compare <strong>Gaming</strong> against every other category.
Because interaction patterns on YouTube are strongly influenced by channel size, we first account for this structural effect before making comparisons.
Using the number of subscribers, we group channels into <strong>six size-based clusters</strong> with <strong>k-means</strong>,
so that creators operating in similar audience environments are analyzed together.
This choice is also motivated by the <strong>scale of the dataset</strong>: with hundreds of thousands of channels,
a single global analysis would mask important heterogeneity in interaction patterns.
By clustering, we can compare <strong>interactional behavior</strong> across categories—likes, comments, and reactions—without conflating community effects with simple scale differences.
</p>


<p>
To make this comparison rigorous, we rely on <strong>non-parametric statistical tests</strong> adapted to the highly skewed and heavy-tailed nature of YouTube data. We first use a <strong>Kruskal–Wallis test</strong> to verify that meaningful differences in engagement exist between categories. Once this is established, we perform <strong>pairwise Mann–Whitney U tests</strong> to compare <strong>Gaming</strong> against every other category, while applying a <strong>Holm–Bonferroni correction</strong> to control for multiple comparisons. These tests are applied to five complementary <strong>interaction metrics</strong>: the <strong>comments per view</strong> ratio (discussion intensity), the <strong>likes per view</strong> ratio (active support), the <strong>dislikes per view</strong> ratio (active rejection), the <strong>appreciation ratio</strong> defined as likes over total reactions, and the <strong>views per subscriber</strong> ratio, which captures how strongly a channel’s audience is anchored in its subscriber base.
</p>

<!-- Row 1 -->
<div style="max-width:1000px; margin:30px auto; display:flex; gap:20px;">
  <img src="/assets/img/group_0_HMC.png"
       alt="Heatmap Group 0"
       style="width:50%;">
  <img src="/assets/img/group_1_HMC.png"
       alt="Heatmap Group 1"
       style="width:50%;">
</div>

<!-- Row 2 -->
<div style="max-width:1000px; margin:30px auto; display:flex; gap:20px;">
  <img src="/assets/img/group_2_HMC.png"
       alt="Heatmap Group 2"
       style="width:50%;">
  <img src="/assets/img/group_3_HMC.png"
       alt="Heatmap Group 3"
       style="width:50%;">
</div>

<!-- Row 3 -->
<div style="max-width:1000px; margin:30px auto; display:flex; gap:20px;">
  <img src="/assets/img/group_4_HMC.png"
       alt="Heatmap Group 4"
       style="width:50%;">
  <img src="/assets/img/group_5_HMC.png"
       alt="Heatmap Group 5"
       style="width:50%;">
</div>


<p>
We interpret these results by focusing on the <strong>pairwise comparisons</strong> between
<strong>Gaming</strong> and the other categories, which reveal how consistently Gaming stands out
across engagement metrics and subscriber groups.
</p>

<p>
The clearest and most robust signal comes from the <strong>comments per view</strong> ratio.
Across almost all groups and category comparisons, Gaming shows
<strong>significantly higher commenting activity</strong>,
with the only notable exception being <em>How-to &amp; Style</em> in the smallest group.
This indicates that Gaming viewers are more likely to
<strong>participate in discussions</strong>, making comments a strong marker of community engagement.
</p>

<p>
Gaming also performs well on <strong>likes per view</strong>, especially for larger channels,
suggesting higher levels of <strong>active support</strong>.
Some categories, such as <em>People &amp; Blogs</em> and <em>Comedy</em>, show comparable results in smaller groups,
but the overall pattern remains in Gaming’s favor.
</p>

<p>
The <strong>dislikes per view</strong> ratio does not show clear differences, which is likely due to
the generally low number of dislikes across YouTube.
In contrast, the <strong>appreciation ratio</strong> tends to be higher for Gaming,
particularly in higher subscriber groups, with <em>NonProfit &amp; Activism</em> as a recurring exception.
</p>

<p>
Finally, the <strong>views per subscriber</strong> ratio does not consistently favor Gaming.
This suggests that Gaming communities are not closed or insular, but rather
<strong>open and dynamic</strong>, attracting both loyal subscribers and new viewers.
</p>

<p>
These results show that Gaming does not just capture attention :
it more reliably <strong>turns views into interaction</strong>,
confirming its role as one of the most socially engaged ecosystems on YouTube.
</p>

<!-- Simple repeatable block -->
<h2 class="simple-title">Cohesion in Gaming Content: Evidence from Top-K Tag Coverage</h2>
<p>
  To quantify how <strong>cohesive</strong> each YouTube category is, we use a simple metric called
  <strong>Top-K tag coverage</strong> (we fixed <strong>K = 20</strong> after manual testing). Within each category, we count how many <strong>distinct videos</strong> contain each tag. We keep the <strong>K most common tags</strong> and compute the share of videos that contain <strong>at least one</strong> of these Top-K tags.
</p>
<p>
  The intuition is straightforward: if a small set of tags covers a large portion of videos, the category likely shares a
  <strong>common vocabulary</strong> and recurring references—an indicator of <strong>internal cohesion</strong>. Conversely, if Top-K
  coverage is low, the category is more <strong>heterogeneous</strong>, relying on many niche or fragmented tags. We apply this procedure
  consistently across our 6 clusters to ensure the signal is not driven by a single batch.
</p>

<img src="/assets/img/newplot.png"
       alt="heatmap"
       style="width:100%;">

<p>
  The <strong>Top-K tag coverage heatmap</strong> suggests that <strong>Gaming</strong> stays fairly consistent across all
  <strong>subscriber clusters</strong>: a relatively small set of tags already covers a large share of Gaming videos,
  whatever the channel size. Some categories like <strong>Autos &amp; Vehicles</strong> and <strong>Music</strong> also look
  quite cohesive, but Gaming seems a bit more stable overall, while many other categories fluctuate more and look more mixed.
  In practice, this likely comes from recurring game titles, genres, and common community references that show up again and again.
</p>

<img src="/assets/img/word_cloud.png"
     alt="heatmap"
     style="width:60%; display:block; margin:30px auto;">



<!-- Simple repeatable block -->
<h2 class="simple-title">Title</h2>
<p>Paragraph 1.</p>
<p>Paragraph 2.</p>
<p>Paragraph 3.</p>

<!-- Simple repeatable block -->
<h2 class="simple-title">Title</h2>
<p>Paragraph 1.</p>
<p>Paragraph 2.</p>

<ul class="simple-list">
  <li>Bullet 1</li>
  <li>Bullet 2</li>
  <li>Bullet 3</li>
</ul>
<p>Paragraph 3.</p>

<h2 class="simple-title">Title</h2>
<p>Paragraph 1.</p>
<p>Paragraph 2.</p>
<p>Paragraph 3.</p>

<h2 class="simple-title">Title</h2>
<p>Paragraph 1.</p>
<p>Paragraph 2.</p>
<p>Paragraph 3.</p>

<h2 class="simple-title">Title</h2>
<p>Paragraph 1.</p>
<p>Paragraph 2.</p>

<ul class="simple-list">
  <li>Bullet 1</li>
  <li>Bullet 2</li>
  <li>Bullet 3</li>
</ul>
<p>Paragraph 3.</p>

<style>
  .plotly-block{
    max-width: 1000px;
    margin: 30px auto 60px auto;
  }
</style>




  

