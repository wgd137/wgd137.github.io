---
permalink: /
title: "Guandi Wang"
excerpt: "Robotics, multimodal perception, and embodied AI."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-home" id="about">
  <div class="profile-intro">
    <p class="profile-lede">He is a master's student at KTH and EURECOM, and a guest student with the Humanoid Sensing and Perception group at the Istituto Italiano di Tecnologia (IIT).</p>
    <p>At KTH, he is pursuing an M.Sc. in ICT Innovation: Autonomous Systems and Intelligent Robots (2025&ndash;Present). At EURECOM, he studies Sensing Big Data for Intelligent Robots (2026&ndash;Present). He received his B.Sc. in Building Electrical and Intelligence from Xi'an University of Architecture and Technology in 2025, graduating in the top 10%.</p>
    <p>His research connects robot perception, multimodal learning, and data-driven modeling, with an emphasis on systems that remain useful outside carefully controlled environments&mdash;from animated visual content to humanoid teleoperation and physical-world forecasting.</p>
    <div class="profile-actions">
      <a class="profile-button profile-button--primary" href="{{ '/files/Guandi_Wang_CV.pdf' | relative_url }}"><i class="fas fa-file-arrow-down" aria-hidden="true"></i> Download CV</a>
      <a class="profile-button" href="mailto:guandi@kth.se"><i class="fas fa-envelope" aria-hidden="true"></i> Email</a>
      <a class="profile-button" href="https://github.com/wgd137"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </div>

  <section class="profile-section" id="news">
    <div class="profile-section__heading">
      <p class="profile-section__eyebrow">Updates</p>
      <h2>Latest News</h2>
    </div>
    <div class="news-list">
      <article class="news-item">
        <time datetime="2026-08">Aug. 2026</time>
        <p><strong>BMVC 2026.</strong> A paper he co-authored, <em>Deep Multimodal Object Detection via Spatial Mask Interaction and Channel Competition</em>, has been accepted.</p>
      </article>
      <article class="news-item">
        <time datetime="2026-06">June 2026</time>
        <p><strong>IIT.</strong> He joined the <a href="https://www.iit.it/it/web/humanoid-sensing-and-perception">Humanoid Sensing and Perception</a> group as a guest student, supervised by Maria Lombardi and led by Lorenzo Natale.</p>
      </article>
      <article class="news-item">
        <time datetime="2026-07">July 2026</time>
        <p><strong>EURECOM.</strong> He started the M.Sc. programme in Sensing Big Data for Intelligent Robots.</p>
      </article>
      <article class="news-item">
        <time datetime="2026-04">Apr. 2026</time>
        <p><strong>PhyGeo-World.</strong> He is contributing to the NAISS-supported project on physics- and geometry-consistent world models for embodied AI.</p>
      </article>
    </div>
  </section>

  <section class="profile-section" id="research">
    <div class="profile-section__heading">
      <h2>Research</h2>
    </div>
    <div class="research-themes">
      <section class="research-theme">
        <header class="research-theme__header">
          <h3>AI for Science <span>AI4S</span></h3>
          <p>Data-driven methods for learning complex physical systems from large-scale scientific observations.</p>
        </header>
        <div class="research-theme__projects">
          <article class="research-project">
            <h4>ForeWind: Spatio-Temporal Wind Forecasting</h4>
            <p>Built a high-resolution meteorological benchmark and large-scale ERA5 data pipeline, then evaluated deep learning baselines for wind-speed forecasting on HPC clusters.</p>
            <p class="research-methods"><strong>Methods:</strong> ERA5, spatio-temporal learning, forecasting, Slurm.</p>
          </article>
        </div>
        <figure class="forewind-demo" aria-labelledby="forewind-demo-title">
          <div class="forewind-demo__header">
            <div>
              <p class="profile-section__eyebrow">ForeWind demo</p>
              <h2 id="forewind-demo-title">Regional Wind Forecasting</h2>
            </div>
            <div class="forewind-demo__controls" role="group" aria-label="Select a ForeWind demo city">
              <button type="button" class="is-active" aria-pressed="true" data-city="Shanghai" data-src="{{ '/images/forewind/shanghai-model-comparison.gif' | relative_url }}">Shanghai</button>
              <button type="button" aria-pressed="false" data-city="Chengdu" data-src="{{ '/images/forewind/chengdu-model-comparison.gif' | relative_url }}">Chengdu</button>
              <button type="button" aria-pressed="false" data-city="Golmud" data-src="{{ '/images/forewind/golmud-model-comparison.gif' | relative_url }}">Golmud</button>
              <button type="button" aria-pressed="false" data-city="Wuhan" data-src="{{ '/images/forewind/wuhan-model-comparison.gif' | relative_url }}">Wuhan</button>
            </div>
          </div>
          <img id="forewind-demo-image" src="{{ '/images/forewind/shanghai-model-comparison.gif' | relative_url }}" alt="Animated ForeWind model comparison for Shanghai" loading="lazy" decoding="async">
          <figcaption>Animated comparison of persistence and deep-learning baselines against ERA5 ground truth.</figcaption>
        </figure>
      </section>

      <section class="research-theme research-theme--stacked">
        <header class="research-theme__header">
          <h3>Robot Perception &amp; Computer Vision</h3>
          <p>Robust visual understanding across sensing modalities, domains, and real-world operating conditions.</p>
        </header>
        <div class="research-theme__projects">
          <article class="research-project">
            <h4>Unified Segmentation for Movies &amp; Cartoons</h4>
            <p>Developing a unified segmentation tool that reconciles different model interfaces, reduces the domain gap between real footage and animation, and supports intuitive semi-automatic annotation.</p>
            <p class="research-methods"><strong>Methods:</strong> segmentation, domain adaptation, Python.</p>
            <figure class="segmentation-demo">
              <a class="segmentation-demo__pipeline" href="{{ '/images/research/segmentation/unified-segmentation-pipeline.png' | relative_url }}" aria-label="Open the unified segmentation pipeline at full size">
                <img src="{{ '/images/research/segmentation/unified-segmentation-pipeline.png' | relative_url }}" alt="Unified segmentation pipeline connecting SAM3, RTMPose, RAFT, manual checking, and final outputs" loading="lazy" decoding="async">
              </a>
              <div class="segmentation-demo__examples">
                <a href="{{ '/images/research/segmentation/cartoon-pose-example-cropped.png' | relative_url }}" aria-label="Open the cartoon character annotation example at full size">
                  <img src="{{ '/images/research/segmentation/cartoon-pose-example-cropped.png' | relative_url }}" alt="Pose annotations over characters in a cartoon illustration" loading="lazy" decoding="async">
                </a>
                <a href="{{ '/images/research/segmentation/video-frame-pose-example-cropped.png' | relative_url }}" aria-label="Open the animated video-frame annotation example at full size">
                  <img src="{{ '/images/research/segmentation/video-frame-pose-example-cropped.png' | relative_url }}" alt="Pose annotations over characters in an animated video frame" loading="lazy" decoding="async">
                </a>
              </div>
              <figcaption>Unified annotation pipeline with representative character-level pose results on illustrations and animated video frames.</figcaption>
            </figure>
          </article>
          <article class="research-project">
            <h4>Deep Multimodal Object Detection</h4>
            <p>Designed spatial-mask interaction and channel-competition mechanisms for robust RGB-thermal object detection under sensor misalignment and adverse conditions.</p>
            <p class="research-methods"><strong>Result:</strong> accepted at BMVC 2026 · <a href="https://arxiv.org/abs/2608.02092">arXiv</a>. <strong>Methods:</strong> RGB-thermal sensing, multimodal learning, PyTorch.</p>
          </article>
        </div>
        <figure class="research-demo research-demo--bmvc">
          <a href="{{ '/images/research/deep-multimodal-object-detection.png' | relative_url }}" aria-label="Open the Deep Multimodal Object Detection architecture at full size">
            <img src="{{ '/images/research/deep-multimodal-object-detection.png' | relative_url }}" alt="Architecture of the Deep Multimodal Object Detection model with spatial mask interaction and channel competition" loading="lazy" decoding="async">
          </a>
          <figcaption>Deep Multimodal Object Detection via spatial mask interaction and channel competition. Select the figure to view it at full size.</figcaption>
        </figure>
      </section>

      <section class="research-theme">
        <header class="research-theme__header">
          <h3>Robotics &amp; Embodied AI</h3>
          <p>Connecting perception, interaction, and physical reasoning for intelligent robots in unstructured environments.</p>
        </header>
        <div class="research-theme__projects">
          <article class="research-project">
            <h4>VR-based R1 Robot Teleoperation</h4>
            <p>Contributing to a confidential teleoperation project involving C programming within the VR stack, <a href="https://www.yarp.it/">YARP</a> middleware, and LeRobot.</p>
            <p class="research-methods"><strong>Methods:</strong> VR, YARP, LeRobot.</p>
          </article>
        </div>
      </section>
    </div>
  </section>

  <section class="profile-section" id="publication">
    <div class="profile-section__heading">
      <h2>Publication</h2>
    </div>
    <article class="publication-card">
      <div class="publication-card__year">2026</div>
      <div>
        <h3>Deep Multimodal Object Detection via Spatial Mask Interaction and Channel Competition</h3>
        <p><strong>British Machine Vision Conference (BMVC 2026)</strong> · Accepted · <a href="https://arxiv.org/abs/2608.02092">arXiv</a></p>
      </div>
    </article>
  </section>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const demo = document.querySelector(".forewind-demo");
    if (!demo) return;

    const image = demo.querySelector("#forewind-demo-image");
    const buttons = demo.querySelectorAll(".forewind-demo__controls button");

    buttons.forEach(function (button) {
      button.addEventListener("click", function () {
        image.src = button.dataset.src;
        image.alt = "Animated ForeWind model comparison for " + button.dataset.city;

        buttons.forEach(function (item) {
          const isActive = item === button;
          item.classList.toggle("is-active", isActive);
          item.setAttribute("aria-pressed", String(isActive));
        });
      });
    });
  });
</script>
