<!-- ===================================================== -->
<!--                     HEADER                            -->
<!-- ===================================================== -->

<h1 align="center">IRIS Experiments</h1>

<p align="center">
  <strong>Structured Exploration. Real-World Learning.</strong>
</p>

<p align="center">
  Experiments designed to understand how computer vision models behave across conditions, domains, and problem definitions.
</p>

<p align="center">
  <a href="#featured-experiments">Explore Experiments</a> •
  <a href="#what-these-experiments-show">What We Learn</a> •
  <a href="#methodology">Methodology</a> •
  <a href="#how-this-fits-into-iris">Ecosystem</a>
</p>

---

<p align="center">
  <img src="assets/iris-experiments-hero.png" width="100%" />
</p>

---

<!-- ===================================================== -->
<!--                     BADGES                            -->
<!-- ===================================================== -->

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Behavior%20Exploration-black" />
  <img src="https://img.shields.io/badge/Approach-Structured%20Experiments-blue" />
  <img src="https://img.shields.io/badge/Scope-Cross--Condition%20%7C%20Cross--Domain%20%7C%20Ontology-green" />
  <img src="https://img.shields.io/badge/Status-Active%20Development-orange" />
</p>

---

<!-- ===================================================== -->
<!--                 WHAT THIS IS                          -->
<!-- ===================================================== -->

## What This Repository Is

This repository is the **learning layer** of IRIS.

It is where models are tested under changing conditions, domains, and assumptions to understand how they behave in the real world.

Experiments are not isolated training runs.

They are structured investigations designed to answer specific questions about model performance.

---

<!-- ===================================================== -->
<!--                 WHY IT EXISTS                         -->
<!-- ===================================================== -->

## Why This Exists

Most experimentation in computer vision focuses on improving a metric.

It does not answer:
- how models behave when environments change  
- how performance transfers across domains  
- how problem definition impacts results  

IRIS Experiments focuses on:

- **testing assumptions, not just tuning models**  
- **understanding behavior across conditions**  
- **evaluating how data and definitions shape outcomes**  

---

<!-- ===================================================== -->
<!--               FEATURED EXPERIMENTS                    -->
<!-- ===================================================== -->

## Featured Experiments

<table>
  <tr>
    <th>Experiment</th>
    <th>Focus</th>
    <th>Question</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>EO vs IR Detection</strong></td>
    <td>Cross-Condition</td>
    <td>Which modality produces more reliable detections?</td>
    <td><a href="#">View</a></td>
  </tr>
  <tr>
    <td><strong>Cross-Modal Transfer</strong></td>
    <td>Domain Shift</td>
    <td>How well does an EO-trained model perform on IR data?</td>
    <td><a href="#">View</a></td>
  </tr>
  <tr>
    <td><strong>Ontology Granularity</strong></td>
    <td>Problem Definition</td>
    <td>How does class specificity impact performance and generalization?</td>
    <td><a href="#">View</a></td>
  </tr>
</table>

---

<!-- ===================================================== -->
<!--                WHAT THESE EXPERIMENTS SHOW            -->
<!-- ===================================================== -->

## What These Experiments Show

Model performance is not fixed.

It changes based on:
- environment  
- data source  
- problem definition  

<p align="center">
  <img src="assets/iris-experiments-comparison.png" width="90%" />
</p>

The same model can:
- perform well in one modality and fail in another  
- generalize poorly across domains  
- behave differently depending on class definitions  

These are not edge cases.

They are expected outcomes when models interact with real-world variability.

---

<!-- ===================================================== -->
<!--                 METHODOLOGY                           -->
<!-- ===================================================== -->

## Methodology

Experiments in IRIS are designed to answer specific questions about model behavior.

Each experiment isolates a variable and evaluates its impact under controlled conditions.

---

### Experiment Types

**Cross-Condition**
- EO vs IR  
- lighting and visibility  
- distance and scale  

**Cross-Domain**
- training vs deployment domain mismatch  
- transfer across sensor types  

**Ontology and Definition**
- class granularity  
- contextual classes  
- class boundary design  

---

### Evaluation Approach

Experiments are evaluated using:

- standard metrics (mAP, mAR, IoU)  
- qualitative inspection of behavior  
- comparison against baseline conditions  

---

<details>
<summary><strong>Why This Matters</strong></summary>

Many performance issues do not originate from model architecture.

They emerge from:
- data mismatch  
- environmental change  
- poorly defined class structures  

Understanding these factors is critical to building reliable systems.

</details>

---

<!-- ===================================================== -->
<!--                HOW THIS FITS INTO IRIS                -->
<!-- ===================================================== -->

## How This Fits Into IRIS

IRIS is structured as a lifecycle for understanding and deploying computer vision systems.

**Flow:**

- **Benchmark** → compare model behavior under controlled conditions  
- **Experiments** → explore how models behave across changing conditions, domains, and definitions  
- **Model Zoo** → deploy models validated through this process  

<p align="center">
  <img src="assets/iris-experiments-ecosystem.png" width="100%" />
</p>

---

<!-- ===================================================== -->
<!--                RELATED REPOS                          -->
<!-- ===================================================== -->

## Related Repositories

- **IRIS Benchmark**  
  Structured comparison and evaluation  
  → [Benchmarks(https://github.com/iris-computer-vision/iris-benchmark)]

- **IRIS Model Zoo**  
  Deployment-ready models  
  → [ModelZoo(https://github.com/iris-computer-vision/iris-model-zoo/)]

---

<!-- ===================================================== -->
<!--                EXTERNAL LINKS                         -->
<!-- ===================================================== -->

## External Resources

- IRIS Platform → https://iriscomputervision.ai/  
- Hugging Face Models → [Link]  
- Case Studies → [Link]

---

<p align="center">
  <strong>IRIS is built for lifecycle-driven computer vision.</strong>
</p>
