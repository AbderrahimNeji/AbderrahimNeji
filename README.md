<p align="center">
  <img src="assets/hero-midnight-intelligence.svg" alt="Abderrahim Neji — Software and Data Engineering. AI systems, computer vision, RAG / LLM." width="100%">
</p>

<p align="center">
  Software &amp; Data Engineering student at the <strong>University of Carthage</strong> (Faculty of Sciences of Bizerte).<br>
  I build retrieval-backed assistants, computer-vision tooling, and backend services that move sensor and model outputs into usable applications.
</p>

<p align="center">
  <a href="https://abderrahimneji.github.io/abderrahim-neji-portfolio/">Portfolio</a>
  ·
  <a href="https://www.linkedin.com/in/abderrahim-neji">LinkedIn</a>
  ·
  <a href="https://github.com/AbderrahimNeji">GitHub</a>
  ·
  <a href="mailto:nejiabderrahim@gmail.com">nejiabderrahim@gmail.com</a>
</p>

<p align="center">
  <img src="assets/divider-neural.svg" alt="" width="100%">
</p>

## Featured engineering projects

Each entry is labeled as an **own repository**, a **fork / course project**, or a **collaborative fork**. Stacks below match what is in those repositories. No evaluation scores or deployment metrics are invented here.

<p align="center">
  <img src="assets/motif-rag.svg" alt="RAG retrieval motif for ZUPdeCO AI Assistant" width="100%">
</p>

### [ZUPdeCO AI Assistant](https://github.com/AbderrahimNeji/Assistant_ZUPdeCO)
**Own repository** — RAG assistant with chat, document ingestion, and an evaluation path. NestJS API on PostgreSQL (Prisma), LangChain with Google Gemini, a Next.js UI, and Docker. Developed during an AI engineering internship at IT Strategix, under technical supervision.

`RAG` `NestJS` `PostgreSQL` `Prisma` `LangChain` `Google Gemini`

<p align="center">
  <img src="assets/motif-mlops.svg" alt="Data-train-track pipeline motif for the image classification course project" width="100%">
</p>

### [Image Classification MLOps Pipeline](https://github.com/AbderrahimNeji/classification-pytorch)
**Fork / course project** — based on [besmaguesmi/classification-pytorch](https://github.com/besmaguesmi/classification-pytorch). ResNet18 image classification in PyTorch, with DVC for dataset versioning and MLflow for experiment tracking. Coursework on the forked starter, including a local report and recorded runs. **Not sole ownership.**

`PyTorch` `ResNet18` `MLflow` `DVC`

<p align="center">
  <img src="assets/motif-iot.svg" alt="Sensor-to-store motif for Smart Olive Grove" width="100%">
</p>

### [Smart Olive Grove](https://github.com/AbderrahimNeji/OliveGrove_IOT)
**Own repository** — IoT monitoring for olive groves. Arduino sensors via the Web Serial API, a Node.js / Express dashboard, optional MongoDB persistence, sensor-data validation tests, and a scikit-learn Random Forest model (trained on synthetic data) for tree-status predictions.

`IoT` `Node.js` `MongoDB` `scikit-learn` `sensor validation`

<p align="center">
  <img src="assets/motif-cv.svg" alt="Vision and evaluation motif for road degradation detection" width="100%">
</p>

### [FinalProjectDevops](https://github.com/AbderrahimNeji/FinalProjectDevops) — road degradation detection
**Own repository · student team project** — with Aymen Jeddou and Mohamed Amine Trabelsi. Computer-vision coursework around YOLOv8: dataset conversion and validation (including RDD2022 → YOLO tooling), detection and evaluation scripts, and a map dashboard. This profile does not claim a completed production training run or published mAP / GPS accuracy.

`YOLO` `dataset validation` `evaluation tooling` `Docker`

<p align="center">
  <img src="assets/motif-mobile.svg" alt="Client and API motif for the student absence app" width="100%">
</p>

### [Student Absence Management App](https://github.com/AbderrahimNeji/Gestion-Absence-Flutter-App)
**Collaborative fork** — with [Aymen Jeddou](https://github.com/AymenJeddou); original [AymenJeddou/Gestion-Absence-Flutter-App](https://github.com/AymenJeddou/Gestion-Absence-Flutter-App). Attendance app for admins, teachers, and students. Flutter/Dart client and a PHP/MySQL API. **A shared team repository, not a solo project.**

`Flutter` `Dart` `PHP` `MySQL`

<p align="center">
  <img src="assets/divider-neural.svg" alt="" width="100%">
</p>

## Technical domains and technologies

Only tools that appear in the projects above or in the [public portfolio](https://abderrahimneji.github.io/abderrahim-neji-portfolio/). No rating bars.

<table>
  <tr>
    <td width="64" valign="top">
      <img src="assets/icon-aiml.svg" alt="" width="56">
    </td>
    <td valign="top">
      <strong>AI / ML and computer vision</strong><br>
      PyTorch, ResNet18, YOLOv8, scikit-learn, OpenCV
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="assets/icon-rag.svg" alt="" width="56">
    </td>
    <td valign="top">
      <strong>RAG, LLMs, and intelligent systems</strong><br>
      LangChain, Google Gemini, document chunking and retrieval, assistant APIs
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="assets/icon-backend.svg" alt="" width="56">
    </td>
    <td valign="top">
      <strong>Backend and APIs</strong><br>
      NestJS, Express, FastAPI, Prisma, PHP
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="assets/icon-data.svg" alt="" width="56">
    </td>
    <td valign="top">
      <strong>Data and databases</strong><br>
      PostgreSQL, MongoDB, MySQL, SQL
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="assets/icon-mlops.svg" alt="" width="56">
    </td>
    <td valign="top">
      <strong>MLOps and DevOps</strong><br>
      Docker, DVC, MLflow, GitHub Actions, Git
    </td>
  </tr>
</table>

Languages used across this work: Python, TypeScript, JavaScript, SQL, Dart, PHP.

<p align="center">
  <img src="assets/divider-neural.svg" alt="" width="100%">
</p>

## Engineering principles and areas of interest

I care about systems that can be inspected, not just demos that look finished.

- **Retrieval you can test** — document ingestion, embeddings, and assistant APIs with an evaluation path (ZUPdeCO).
- **Versioned experiments** — dataset lineage and run tracking before claiming a better model (DVC + MLflow on the classification coursework).
- **Honest evaluation tooling** — conversion, validation, and metric scripts belong in the repo even when a training run is incomplete (FinalProjectDevops).
- **Validate the signal** — sensor payloads and IoT paths need checks before a model sees them (Smart Olive Grove).
- **APIs as the product surface** — NestJS, Express, FastAPI, and PHP services that expose the model or the domain, not notebooks alone.

**Areas of interest:** AI/ML, computer vision, MLOps, RAG/LLM systems, intelligent applications, and backend engineering.

<p align="center">
  <img src="assets/divider-neural.svg" alt="" width="100%">
</p>

## Education and professional direction

Fifth-year **Software &amp; Data Engineering** student at the Faculty of Sciences of Bizerte, University of Carthage (Tunisia).

Recent public work includes an AI engineering internship at IT Strategix (ZUPdeCO assistant) and earlier data internships at Tunisie Telecom.

Looking for a **PFE internship** in AI/ML, computer vision, MLOps, RAG/LLM systems, or backend / data engineering.

Repositories here are academic or personal. Some are team projects or forks — those are labeled above.

<p align="center">
  <img src="assets/divider-neural.svg" alt="" width="100%">
</p>

## Contact and collaboration

Open to internships, student collaborations, and engineering conversations around retrieval systems, vision pipelines, and applied ML backends.

- Portfolio — [abderrahimneji.github.io/abderrahim-neji-portfolio](https://abderrahimneji.github.io/abderrahim-neji-portfolio/)
- LinkedIn — [linkedin.com/in/abderrahim-neji](https://www.linkedin.com/in/abderrahim-neji)
- GitHub — [github.com/AbderrahimNeji](https://github.com/AbderrahimNeji)
- Email — [nejiabderrahim@gmail.com](mailto:nejiabderrahim@gmail.com)
