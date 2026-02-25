---
layout: page
title: "Research"
permalink: /research/
description:
nav: true
nav_order: 1
_styles: |
  .post-header {
    display: none;
  }
  .research-section {
    margin-top: 2rem;
  }
  .research-section:first-child {
    margin-top: 0;
  }
  .research-section h1 {
    text-align: center;
    margin-bottom: 1rem;
  }
  .research-list li {
    margin-bottom: 1.25rem;
  }
  .research-list details {
    margin-top: 0.5rem;
  }
---

<section class="research-section">
<h3>Research Focus</h3>

I study why creative products succeed and how creators can use innovation, borrowing, and generative AI to design content that resonates rather than disappears.

My work combines economics, statistics, and multi-modal machine learning to understand diffusion and performance outcomes in music, online video, and video games.

<details>
  <summary><strong>Details</strong></summary>
  Entertainment markets differ fundamentally from traditional product markets because creative goods are high-dimensional and audience preferences are largely implicit—people know they like a song or a video but cannot easily explain why. My research develops interpretable, theory-guided representations of creative content and embeds them into a historical style space to measure innovation and borrowing relative to past successful works. On the supply side, I study how creators strategically position themselves in style space based on goals (entry, ranking, persistence) and identity (incumbent vs. entrant). I use counterfactual experiments and generative AI pipelines to evaluate how creative decisions affect real outcomes, offering guidance at a moment when AI enables large-scale creation but amplifies noise and uncertainty.
</details>
</section>

<section class="research-section">
<h3>Job Market Paper</h3>

<ol class="research-list">
  <li>
    <strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Yingkang Xie. "Generative AI Music Design Through Controlled Similarity to Historical Styles."
    <details>
      <summary>Abstract</summary>
      With the rapid diffusion of generative AI in creative industries, a central question is how to use these tools to design successful content. This paper proposes a novel data-driven framework for designing music with controlled similarity to past music styles. We first construct an Interpretable Music Attribute Representation (IMAR) by separating each track into vocal, bass, drum, and accompaniment stems using Demucs, then extracting theory-grounded features for melody, harmony, rhythm, and timbre using deep learning models (CNNs, PANNs, madmom, Basic Pitch, EchoNest) integrated with music-theoretic analysis, creating representations that closely mirror a music sheet. Using all Billboard Hot 100 (24,618) songs from 1958--2017, we cluster songs within rolling five-year windows via Partitioning Around Medoids with Gower distance and then aggregate medoids using a forward 2.5-MAD single-linkage rule to obtain robust historical "styles." Utilizing 29,331 songs from 2018--2025, we then compute similarity measures between focal songs and these styles and show that successful contemporary music achieves optimal distinctiveness through a strategic balance: melodies and rhythms that blend multiple past styles (with melodies tilting toward newer styles and rhythms toward older ones), fusion-oriented harmonies, and innovative timbres that diverge from traditional patterns. Next, we train a state-of-the-art predictive model of Billboard entry based on audio-derived IMAR features, and demonstrate that the inclusion of style-based similarity measures yields substantial gains in predictive accuracy. Finally, we operationalize these insights for generative AI: using a retrieval-augmented generation scheme that conditions on historical style medoids, we compare multiple candidate editing strategies for new songs and find that the empirically motivated "fusion" strategy achieves the highest predicted success among all tested alternatives. Our framework offers one of the first end-to-end, implementable guidelines for using generative AI to solve the product design problem in music creation.
    </details>
  </li>
</ol>
</section>

<section class="research-section">
<h3>Working Papers</h3>

<ol class="research-list" start="2">
  <li>
    <strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5492026" target="_blank" rel="noopener">"Instant versus Sustained Diffusion of YouTube Videos: A Multimodal Analysis of Content Characteristics."</a> Reject and Resubmit, <strong>Journal of Marketing Research</strong>.
    <details>
      <summary>Abstract</summary>
      Despite an emerging body of research on online content diffusion, there has been little to no investigation of how content characteristics drive distinct temporal diffusion patterns. This study addresses this gap by investigating two primary questions: (1) What are the main diffusion patterns of online videos? (2) Which specific content characteristics influence these patterns? We estimate the Bass diffusion model on a random sample of one million YouTube videos and identify 42,046 videos with highly predictable temporal diffusion patterns. Using K-means clustering, we find that these videos fall under two broad types: (1) instant diffusion (rapid spike followed by quick decline), (2) sustained diffusion (steady growth over time). Guided by Dual Process Theory, we apply state-of-the-art machine learning methods—(1) Spotify audio analysis, (2) Whisper transcription, (3) Sentence-BERT embeddings, and (4) Topic modeling—to extract audio, visual, and textual features corresponding to System 1 (fast, emotional) versus System 2 (slow, analytical) cognitive processes. Logistic regression analyses reveal that instant diffusion is associated with high-energy, emotionally engaging content (System 1), whereas sustained diffusion is associated with informational density and complexity (System 2). Viewer engagement metrics (comment complexity, delayed sharing, longer watch times) further validate these cognitive distinctions. Our findings can be used by YouTube content creators to design video content that is tailored to achieve specific temporal viewership objectives.
    </details>
  </li>
  <li>
    <strong>Haihao Guo</strong>, Baojun Jiang, P. B. (Seethu) Seetharaman. "When Should Developers Partner with a Publisher? Theory and Evidence from Steam."
    <details>
      <summary>Abstract</summary>
      Independent game developers must choose whether to self-publish or partner with a publisher that can amplify demand through marketing. We build an analytical model in which the developer's effort is unobservable and the integration choice (partnering vs. self-publishing) is endogenous. Publisher marketing raises the marginal return to quality but weakens effort incentives under standard revenue sharing. We show that equilibrium price, effort, and mode are characterized by two cutoff values—one in the publisher's marketing capability and one in the developer's quality-to-cost ratio. The developer will self-publish only when both its quality-to-cost ratio and the publisher's marketing capability are below some threshold levels; otherwise it will partner with the publisher. We show that profit-sharing contracts expand the region where partnerships are feasible and efficient by better aligning incentives. We test the model's implications using the Steam PC games market (2015--2025), combining mode choice with price and performance outcomes and correcting for selection. The evidence is consistent with the theory: publisher-backed titles—especially when publisher capability is high—exhibit higher launch prices and stronger first-year performance, with patterns that map to the predicted thresholds. This paper offers actionable guidance on when developers should partner, how publishers should set terms, and how platforms should design policies that balance discovery with incentives.
    </details>
  </li>
</ol>
</section>

<!--
<section class="research-section">
<h3>Selected Work in Progress</h3>

<ol class="research-list" start="4">
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Baojun Jiang. "Dynamic Reference Point in Price: Evidence from Video Games Market."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. "Accelerating Social Science Research with DeepWalk Algorithm."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. "Impact of Audio vs. Visual on Diffusion of Music Videos."</li>
</ol>
</section>
-->
