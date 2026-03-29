### Hyper-Personalization & Recommendation Engine - Project Overview

**Problem:** Public-facing web properties lacked the segmentation logic required to provide curated experiences for both prospects and existing
clients, resulting in a generic user journey that limited conversion opportunities across a high-volume user base.

**Solution:** Increased conversions by architecting a segmentation-aware recommendation engine, achieving a 63% New-to-Bank (NTB) conversion
rate for key financial products. Developed an automated AWS S3-to-ElastiCache (Redis OSS) data pipeline using AWS Glue (PySpark) and
Apache Airflow to transform raw user signals into personalized content triggers. Engineered a low-latency TypeScript-based RESTful API
orchestration for delivery of curated offers based on unique user identifiers; utilized Dynatrace for full-stack observability and proactive
bottleneck identification. Implemented horizontal auto-scaling for containerized services on AWS ECS/Fargate alongside a zero-downtime
deployment workflow to maintain performance across high-volume traffic.

<p align="center">
  <a href="hyper-personalization-recommendation-engine.svg" target="_blank">
    <img src="hyper-personalization-recommendation-engine.svg" alt="System Architecture SVG" width="100%">
  </a>
  <br>
  <em>(Click image to open high-resolution SVG for infinite zoom)</em>
</p>

---

### 📂 Technical Assets
For offline viewing or specific zoom requirements, choose a format below:

* **[Scalable Vector (SVG)](hyper-personalization-recommendation-engine.svg)** - Recommended for mobile & browser zooming.
* **[High-Resolution Image (PNG)](hyper-personalization-recommendation-engine.png)** - Recommended for 300 DPI static render.
* **[Document Version (PDF)](hyper-personalization-recommendation-engine.pdf)** - Recommended for printing.
