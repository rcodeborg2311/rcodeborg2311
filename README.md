````markdown
<h1 align="center">Hi, I'm Ridham Patel 👋</h1>

<h3 align="center">
  M.S. Computer Science @ USC · ML Systems · High-Performance C++ · Quantitative Engineering
</h3>

<p align="center">
  B.S. Computer Science @ Arizona State University · GPA 3.89/4.00 · Dean's List
</p>

<p align="center">
  I build performance-critical systems across machine learning, quantitative finance, and distributed software.
  My current interests include deep learning systems, GPU inference, low-latency C++, market microstructure,
  and open-source infrastructure.
</p>

<p align="center">
  <a href="https://www.ridhamcodes.com"><strong>Portfolio</strong></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/rcodeborg2311"><strong>GitHub</strong></a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/ridham-patel-2003as12/"><strong>LinkedIn</strong></a>
  &nbsp;•&nbsp;
  <a href="mailto:ridhamap@gmail.com"><strong>Email</strong></a>
</p>

---

## About Me

- 🎓 **M.S. Computer Science @ University of Southern California** — Expected May 2028
- 🎓 **B.S. Computer Science @ Arizona State University** — May 2026
- ⚙️ Interested in **ML systems, GPU computing, compilers, distributed systems, and low-latency C++**
- 📈 Building quantitative systems around **market microstructure, execution, and stochastic modeling**
- 🔬 Experience in **research engineering, machine learning, simulation systems, and GPU-backed infrastructure**
- 🌱 Currently going deeper into **PyTorch internals, Triton/CUDA, LLM inference, and open-source systems work**

---

## Featured Engineering Work

### ⚡ [Lock-Free Limit Order Book](https://lob-engine-lock-free.vercel.app/)

**C++20 · Concurrency · Systems Performance · React**

Price-time-priority matching engine built around lock-free MPSC/SPSC queues, cache-line isolation, preallocated data structures, and zero heap allocation on the matching hot path.

- Sustains **2.6M+ orders/sec**
- Measures **sub-microsecond P99 matching latency**
- Parses **NASDAQ TotalView-ITCH 5.0**
- Implements pre-trade risk controls and exchange order semantics
- Streams live book state to a React/TypeScript visualization

> Focus: concurrency, cache behavior, latency, data structures, and reproducible systems benchmarking.

---

### 📊 [HF Market Microstructure Signal Platform](https://high-frequency-microstructure-sig.vercel.app/)

**C++20 · Python · FastAPI · WebSockets · React**

Real-time market microstructure research and analytics platform built around live order-book data.

- C++ feature engine benchmarked at **1M LOB snapshots/sec**
- Computes **order-flow imbalance, VPIN, Kyle's λ, realized volatility, and Hawkes-process intensity**
- Streams analytics through FastAPI/WebSockets
- Includes Avellaneda–Stoikov and Cartea–Jaimungal market-making models
- Numerical components validated with Python and Catch2 tests

> Focus: high-throughput data processing, quantitative research, numerical validation, and real-time systems.

---

### 🧮 [Heston Stochastic Volatility Calibration Engine](https://heston-calibration-engine.vercel.app/)

**C++20 · Numerical Methods · Python · FastAPI**

Options pricing and calibration engine implementing the Heston stochastic-volatility model.

- Carr–Madan FFT pricing with **N=4096**
- Differential Evolution + Levenberg–Marquardt calibration
- Craig–Sneyd ADI PDE solver for independent validation
- **139/139 Catch2 tests passing**
- Interactive web interface for calibration and parameter exploration

> Focus: numerical computing, optimization, stochastic models, validation, and C++ performance.

---

### 🤖 [Snap2Plan](https://snap-2-plan.vercel.app/)

**Next.js · TypeScript · Supabase · PostgreSQL · AI APIs**

Multimodal task-management application that converts unstructured input into structured workflows.

- Extracts tasks from handwritten notes, images, and voice
- Real-time Kanban synchronization
- PostgreSQL + Supabase Row-Level Security
- Google Calendar OAuth 2.0 integration
- Scheduled reminders and automated deployment through Vercel

> Focus: product engineering, multimodal AI integration, distributed application state, and full-stack deployment.

---

## Quantitative Research

### [Statistical Arbitrage Research Platform](https://statistical-arbitrage-research-platform-dzkhyve2i625wwbzlrknbz.streamlit.app/)

Research framework for evaluating pairs-trading hypotheses using:

- Engle–Granger and Johansen cointegration
- Kalman-filter hedge-ratio estimation
- CVaR and risk-parity portfolio construction
- HAC-adjusted Sharpe ratios
- Monte Carlo simulation
- Out-of-sample validation

The project emphasizes **rejecting strategies that fail out-of-sample**, rather than optimizing solely for attractive backtest results.

---

### [RL Market-Making Agent](https://rlmarketmaker-7yho3khdjxpcsppuwappuas.streamlit.app/)

PPO-based market-making agent operating on BTC-USD microstructure state.

- 20-dimensional market-state representation
- Inventory-aware reward formulation
- Avellaneda–Stoikov-inspired objective
- Out-of-sample evaluation across 100 episodes
- Compared against baseline execution strategies

> Current interest: making the evaluation framework more rigorous with stronger market-making baselines and statistical confidence intervals.

---

## Current Technical Focus

```text
Deep Learning Systems
├── PyTorch internals
├── Triton / CUDA kernels
├── Transformer inference
├── KV-cache optimization
├── torch.compile / TorchInductor
└── GPU performance profiling

High-Performance Systems
├── C++20
├── Lock-free concurrency
├── Cache-aware design
├── Linux performance
├── Networking
└── Latency benchmarking

Quantitative Systems
├── Market microstructure
├── Execution systems
├── Stochastic modeling
├── Time-series analysis
└── Real-time market data
````

---

## Technical Stack

**Languages**

`C++20` · `Python` · `Rust` · `C` · `Java` · `TypeScript` · `JavaScript` · `SQL`

**ML / Numerical**

`PyTorch` · `TensorFlow` · `NumPy` · `SciPy` · `Pandas` · `Scikit-learn` · `OpenCV`

**Systems / Infrastructure**

`Linux` · `Docker` · `Kubernetes` · `AWS` · `Git` · `PostgreSQL` · `WebSockets`

**Currently Learning**

`CUDA` · `Triton` · `torch.compile` · `GPU Profiling` · `LLM Inference Systems`

---

## Research & Engineering Experience

**Research Aide — ASU School of Computing and Augmented Intelligence**

Worked on computer-vision and LLM-based methods for biomedical imaging, including architecture benchmarking, failure-mode analysis, and experimental evaluation.

**Research Assistant — ASU Biodesign**

Developed Rust–Python interfaces for high-performance simulation components and extended simulation tooling with spatial modeling and real-time visualization.

**Machine Learning Intern — WDWIL / Magik Kraft**

Built TensorFlow/PyTorch defect-detection pipelines and deployed GPU-backed training and inference workloads on AWS using Docker and Kubernetes.

---

## What I'm Looking For

I'm particularly interested in internship and research opportunities involving:

* **ML Systems / AI Infrastructure**
* **GPU / Inference Performance**
* **C++ Systems Engineering**
* **Quantitative Development**
* **Distributed Systems**
* **Open-Source Infrastructure**

If you're working on difficult performance, ML infrastructure, or quantitative systems problems, I'd love to connect.

---

<p align="center">
  <a href="mailto:ridhamap@gmail.com">Email</a>
  ·
  <a href="https://www.linkedin.com/in/ridham-patel-2003as12/">LinkedIn</a>
  ·
  <a href="https://www.ridhamcodes.com">Portfolio</a>
</p>

<h3 align="center"><i>Carpe Diem.</i></h3>
```

The biggest upgrades are the **USC status**, a much clearer engineering identity, fewer decorative icons, no duplicated contact section, no giant logo wall, and project descriptions that emphasize **engineering evidence instead of “production-grade” marketing language**.

I also surfaced your professional research/internship experience directly on the profile, because recruiters visiting GitHub should not have to infer that you have real experience from projects alone.

I’ve surfaced the GitHub connection option as well. If you connect it, I can work with the repository directly rather than you having to paste the README manually.
