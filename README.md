<div align="center">

<!-- ==================== 00. ANIMATED IVIN.IN HERO BANNER ==================== -->
<a href="https://ivin.in">
  <img src="./assets/hero-banner.svg?v=2" width="100%" alt="Ivin Baiju — Ideas into Intelligent Systems" />
</a>

<br/>

<!-- ==================== ANIMATED SIGNAL STRIP ==================== -->
<img src="./assets/signal-strip.svg?v=2" width="100%" alt="Current Curiosities — Artificial Intelligence, Computer Vision, Systems Engineering, SLM Inference, Product Building" />

<br/><br/>

[![Website ivin.in](https://img.shields.io/badge/%3C%2F%3E_ivin.in-LIVE_PORTFOLIO-F05A28?style=for-the-badge&labelColor=171A1E)](https://ivin.in)
[![Visionlytics Live](https://img.shields.io/badge/VISIONLYTICS_v1.0-LIVE_SAAS_APP-8FBD9C?style=for-the-badge&labelColor=171A1E)](https://ivin-baiju.github.io/Visionlytics/)
[![SLM Inference Engine](https://img.shields.io/badge/SLM_INFERENCE-48.3_TPS_M4_MPS-8EBAE0?style=for-the-badge&labelColor=171A1E)](https://github.com/ivin-baiju/Custom_SLM_Inference)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-in%2Fivin--baiju-C7A3DF?style=for-the-badge&labelColor=171A1E)](https://in.linkedin.com/in/ivin-baiju)
[![X / Twitter](https://img.shields.io/badge/X_%2F_TWITTER-%40Gargantuaq1-E0C68A?style=for-the-badge&labelColor=171A1E)](https://x.com/Gargantuaq1)

</div>

---

## `01` · SELECTED WORK & EXPERIMENTS — *Things I’m bringing to life.*

> A mix of production systems, custom inference engines, and spatial intelligence consoles. I care about the problem, the mathematical architecture behind the solution, and the engineering details that make it genuinely useful.

<div align="center">
  <a href="https://ivin.in/#work">
    <img src="./assets/projects-showcase.svg" width="100%" alt="Selected Work — Visionlytics, MONARCH, ATC Simulation, Custom SLM Inference" />
  </a>
</div>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><code>V / 001</code> · <a href="https://github.com/ivin-baiju/Visionlytics">Visionlytics v1.0</a></h3>
      <p><sub><b>COMPUTER VISION SAAS · MULTI-OBJECT TRACKING · APACHE-2.0 ONNX</b></sub></p>
      <p>Full-stack, multi-tenant computer vision SaaS platform analysing images, videos, live webcams, and RTSP streams per frame — rebuilt from scratch as a Turborepo monorepo.</p>
      <ul>
        <li><b>Detection &amp; Tracking:</b> Calibrated Apache-2.0 <b>RT-DETRv2-R18vd</b> &amp; <b>YOLOS-Tiny ONNX</b> (+ SAHI 2×2 tiled pass) paired with <b>ByteTrack</b> (Alpha-Beta Kalman filter + 26-d HSV/Lab appearance Re-ID).</li>
        <li><b>Perceptual Garment Colour Pipeline:</b> Elliptical foreground mask + 15% border-ring subtraction, k-means (<code>k = 3</code>) in <b>CIELAB</b> space, and <b>CIEDE2000 (ΔE00)</b> matching across a 28-colour palette with upper-torso / lower-leg split.</li>
        <li><b>Measured Golden Telemetry:</b> <code>mAP@50: 91.43%</code> · <code>mAP@50:95: 85.14%</code> · <code>CIEDE2000 Acc: 85.71%</code> · <code>Person Count MAE: 0.00</code> · <code>60 FPS</code> WebGL2 + Canvas HUD.</li>
      </ul>
      <p>
        <a href="https://ivin-baiju.github.io/Visionlytics/"><b>Open Live App ↗</b></a> ·
        <a href="https://github.com/ivin-baiju/Visionlytics"><b>Source Code &amp; Architecture ↗</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><code>L / 004</code> · <a href="https://github.com/ivin-baiju/Custom_SLM_Inference">Custom SLM Inference Engine</a></h3>
      <p><sub><b>FROM-SCRATCH TRANSFORMER RUNTIME · APPLE SILICON M4 MPS</b></sub></p>
      <p>Bespoke small-language-model inference engine hand-forged in PyTorch for Apple Silicon — zero <code>transformers.generate()</code> wrappers, streaming safetensor weights layer-by-layer.</p>
      <ul>
        <li><b>Hand-Written Architecture:</b> Explicit <b>RoPE</b> rotary embeddings, <b>Grouped-Query Attention (GQA)</b>, <b>SwiGLU</b> MLP projections, RMSNorm, and pre-allocated static KV-cache.</li>
        <li><b>Low-Bit Quantization:</b> Layer-streamed INT8 &amp; INT4 weight quantization fitting <b>Qwen2.5-3B</b> into just <b>4.13 GB VRAM</b> on a 16 GB Unified Memory Mac.</li>
        <li><b>Measured Benchmarks:</b> <code>1.00000179</code> cosine logits parity vs HuggingFace · <code>48.3 tps</code> FP16 on Qwen2.5-0.5B (<code>36.8 ms</code> TTFT) · <code>19/19</code> pytest suite passing.</li>
      </ul>
      <p>
        <a href="https://github.com/ivin-baiju/Custom_SLM_Inference"><b>Explore Repository &amp; Benchmarks ↗</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><code>M / 002</code> · <a href="https://ivin.in/#work">MONARCH</a></h3>
      <p><sub><b>GEOSPATIAL INTELLIGENCE CONSOLE · PRODUCT ENGINEERING</b></sub></p>
      <p>A dark-first spatial intelligence console built around georeferenced imagery, mapped coordinate bounds (<code>28° 27′ 18″ N, 77° 30′ 09″ E</code>), 8 active spatial layers, and 12 live telemetry sources.</p>
      <ul>
        <li><b>Stack:</b> React, TypeScript, Framer Motion, geospatial layer orchestration, and high-contrast tactical UI ergonomics.</li>
      </ul>
      <p><a href="https://ivin.in/#work"><b>View on ivin.in ↗</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3><code>S / 003</code> · <a href="https://ivin.in/#work">ATC Simulation</a></h3>
      <p><sub><b>AI · REAL-TIME AIRSPACE &amp; CONFLICT SIMULATION</b></sub></p>
      <p>An AI air-traffic-control simulation concept: replay multi-aircraft flight corridors, inject close-call separation scenarios, detect trajectory conflicts, and evaluate autonomous controller instructions.</p>
      <ul>
        <li><b>Focus:</b> Multi-agent simulation, trajectory conflict detection, decision-support telemetry, and radar HUD visualization.</li>
      </ul>
      <p><a href="https://ivin.in/#work"><b>View on ivin.in ↗</b></a></p>
    </td>
  </tr>
</table>

---

## `02` · BEYOND THE SURFACE LAYER — *The interests that drive the build.*

> I’m drawn to the layers underneath a product: the models, data, mathematical guarantees, and systems decisions that make the experience possible.

<div align="center">
  <img src="./assets/focus-radar.svg" width="100%" alt="Beyond the Surface Layer — AI/ML, Computer Vision, Systems & Performance, Product Engineering" />
</div>

---

## `03 & 04` · ABOUT ME & THE WORKING TOOLKIT — *Curious by nature. Engineer by practice.*

<div align="center">
  <img src="./assets/about-toolkit.svg" width="100%" alt="About Ivin Baiju and The Working Toolkit" />
</div>

---

## `05` · THE FOUNDATIONS — *Learning is part of the build.*

> Formal foundations matter. So does staying curious outside the syllabus. Here is a snapshot of my academic path at **Bennett University** and selected engineering certifications.

<div align="center">
  <img src="./assets/credentials-board.svg" width="100%" alt="Bennett University B.Tech CSE and Selected Certifications" />
</div>

---

## `06` · OPEN CHANNEL — *Have an idea worth building?*

<div align="center">
  <a href="https://ivin.in/#connect">
    <img src="./assets/connect-footer.svg" width="100%" alt="Open Channel — Connect with Ivin Baiju on ivin.in, LinkedIn, X, Instagram" />
  </a>

  <br/>

  <sub><b>&lt;/&gt; ivin.</b> · Designed around curiosity. Built with intent. · <b>INDIA · UTC +05:30</b> · <a href="mailto:lightningspeed.flh@gmail.com">lightningspeed.flh@gmail.com</a></sub>
</div>
