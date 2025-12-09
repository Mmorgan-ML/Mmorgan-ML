# Hi, I'm Michael Christian Morgan.

### Independent Machine Learning Researcher
📍 **South Korea** (Open to Remote Roles)

I am a researcher bridging the gap between **Linguistics**, **Complex Systems Biology**, and **Artificial Intelligence**.

With an academic foundation in East Asian Linguistics and Articulatory Phonetics from the University of Georgia, I approach Large Language Models not just as statistical predictors, but as dynamic systems akin to biological evolution and physical processes. My work focuses on escaping local minima in architectural design by applying principles from nature, physics, and "weird math" to deep learning.

---

### 🔬 Research Focus & Technical Stack

I specialize in **Python** and **PyTorch**. My work often requires going deeper than standard libraries, including writing **custom C++/CUDA kernels** for optimizing novel architectures like my Neuromodulatory Control Networks.

**My current research interests include:**
*   **Physics-Inspired Architectures:** Energy-based models, Hamiltonian dynamics, and thermodynamic approaches to loss landscapes.
*   **Biologically Plausible AI:** Neuromodulation, hypernetworks, and synaptic plasticity simulations.
*   **Evolutionary Computing:** Genetic algorithms applied to Transformer hyperparameter optimization and Artificial Life simulations.
*   **Linguistics:** Viewing tokenization through the lens of articulatory phonetics and continuous dynamic systems.

---

### ⚡ Featured Projects

#### [1. Evolutionary MicroTransformer Framework](https://github.com/Mmorgan-ML/Neural-Speciation)
*A massive-scale evolutionary simulator for hyperparameter optimization and artificial life.*

<img width="1919" height="1023" alt="evolution_lab" src="https://github.com/user-attachments/assets/5a126142-1443-4514-aa3e-ba6acb47b63b" />

<img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/5fb30865-b350-4277-ac23-fc9d2515985f" />

This project is a comprehensive framework that pits populations of "MicroTransformers" (10k parameters) against each other in a survival-of-the-fittest environment based on validation loss performance.
*   **The Genome:** Agents possess 17 "genes" representing initialization hyperparameters.
*   **Lifecycle:** Agents fight, breed, mutate, clone, and evolve over generations.
*   **Gene Forge:** A tool for manual gene editing and **Horizontal Gene Transfer** (stealing genes from other successful agents).
*   **Stress Chamber:** A rigorous testing module for collecting performance data on specific genomes across random seeds.
*   **Speciation Dashboard:** Uses **PCA** to map 17-dimensional gene data onto a 3D interactive graph. It utilizes clustering to automatically categorize agents into taxonomic ranks (Kingdom, Phylum, Class, etc.), visualizing how distinct survival strategies evolve divergently.

#### [2. Neuromodulatory Control Network (NCN)](https://github.com/Mmorgan-ML/Neuromodulatory-Control-Networks)
*A novel LLM architecture inspired by the human brain's neuromodulatory systems.*

Successfully trained 18M param model on 1 epoch of TinyStories, achieving 4.5 PPL.

<img width="1536" height="765" alt="Neuromodulation" src="https://github.com/user-attachments/assets/5c11139e-545f-47e3-8946-07e0fbdd5dea" />
(Fig 1) Token-Level Neuromodulatory Dynamics. Heatmaps display the NCN output values for Layer Gain (Top), Attention Precision (Middle), and FFN Gating (Bottom). X-axis represents the token sequence; Y-axis represents Layer Depth (0-5).

<img width="3600" height="2100" alt="perplexity_graph" src="https://github.com/user-attachments/assets/486b9f4f-084d-40a5-85dc-5fe1815409e9" />
(Fig 2) Training Convergence Analysis. The NCN model demonstrates rapid perplexity reduction, stabilizing significantly below standard baselines for this parameter class. The dark blue line represents the macro-trend (span=118), showing a smooth descent without the volatility typically associated with hypernetwork training.

<img width="4200" height="2400" alt="analysis_grammar_95" src="https://github.com/user-attachments/assets/761a71c0-eac5-4d7d-8d1d-6928fd3648ca" />
(Fig 3) Grammar/Syntax Convergence (95%). The dashed blue line indicates a steep power-law fit, suggesting rapid acquisition of surface-level statistics.

<img width="4200" height="2400" alt="analysis_intellectual_99" src="https://github.com/user-attachments/assets/952965fb-17e1-4a2d-b722-a934da90797b" />
(Fig 4) Intellectual Convergence (99%). The "Active Phase" (Red) tightly hugs the power law, indicating sustained learning of higher-order logic without premature plateaus.


This architecture moves beyond standard Transformers by implementing a global modulation mechanism.
*   **Mechanism:** Functions similarly to a hypernetwork but outputs modulation signals that dynamically adjust the **Temperature, Gain, and FFN Gating** of the main network blocks.
*   **Implicit Learning:** The network learns to contextually identify which modulation signals minimize loss without explicit supervision.
*   **Optimization:** Includes custom C++/CUDA kernels to handle the specific computational requirements of the modulation layers.
*   *(Paper currently in pre-print phase, includes preliminary empirical results).*

#### [3. Entropy-Based KV-Cache Sampler](https://github.com/Mmorgan-ML/Phase-Slip-Sampler)
*Available on PyPI.*

<img width="1080" height="757" alt="image" src="https://github.com/user-attachments/assets/77c7f9da-c018-43b2-b21b-39b7d06f4d8b" />


A novel inference sampler designed to prevent LLM looping and degradation.
*   **Method:** Monitors the entropy of the model's output in real-time.
*   **Intervention:** Injects non-destructive Gaussian noise directly into the Key-Value (KV) cache when entropy thresholds suggest loop formation, effectively "kicking" the model out of repetitive states without breaking coherence.

---

### 📜 Background & Experience

*   **Linguistics & Phonetics:** My background gives me a unique perspective on NLP. I view language processing as a constraint system rooted in physical production (articulatory phonetics) rather than purely symbolic manipulation.
*   **Patent Translation:** Extensive experience translating technical patents (English/Korean/Japanese), requiring extreme attention to detail and technical literacy.
*   **Global Business:** Experience in Duty Free Trade, connecting international suppliers to the Korean market.

---

### 📫 Connect

I am currently open to job offers and research collaborations (Remote preferred).

*   **Email:** [mmorgankorea@gmail.com](mailto:mmorgankorea@gmail.com)
*   **Twitter/X:** [@Mmorgan_ML](https://twitter.com/Mmorgan_ML) (DMs open)
