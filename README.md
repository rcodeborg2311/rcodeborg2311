<h1 align="center">Hi 👋, I'm Ridham</h1>
<h3 align="center">CS @ Arizona State University · Quant & Systems Engineer · GPA 3.89 · Dean's List</h3>

<p align="center">
  I build low-latency trading systems, quantitative research tools, and full-stack AI applications.
  Currently exploring reinforcement learning for market microstructure and high-performance C++ systems.
</p>

<br/>
<h3 align="left">🔗 Connect with me</h3>
<p align="left">
  <a href="mailto:ridhamap@gmail.com">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" />
  </a>
  <a href="https://www.linkedin.com/in/ridham-patel-2003as12/">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo" />
  </a>
  <a href="https://www.ridhamcodes.com">
    <img src="https://img.shields.io/static/v1?message=Portfolio&logo=google-chrome&label=&color=000000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="portfolio" />
  </a>
</p>

<br/>

---

<h3 align="left">🚀 Featured Projects</h3>

**[HF Market Microstructure Signal Platform](https://high-frequency-microstructure-sig.vercel.app/)** · Python, FastAPI, React, WebSocket
> Real-time high-frequency signal platform ingesting Coinbase Advanced Trade WebSocket feed to compute microstructure signals — order flow imbalance, trade intensity, bid-ask spread dynamics, and volume-weighted price impact. Streams live signals to a React dashboard with sub-100ms latency and REST endpoints for historical signal replay and regime analysis.


**[Heston Stochastic Volatility Calibration Engine](https://heston-calibration-engine.vercel.app/)** · C++20, Python, FastAPI
> Production-grade options pricing and calibration engine implementing the Heston model via Carr-Madan FFT (N=4096, FFTW3), two-phase Differential Evolution + Levenberg-Marquardt calibration, and a Craig-Sneyd ADI PDE solver. Achieves sub-basis-point RMSE with 139/139 Catch2 tests passing, deployed as a live interactive dashboard.

**[Lock-Free Limit Order Book](https://lob-engine-lock-free.vercel.app/)** · C++20, React, TypeScript
> Price-time priority matching engine processing 2.6M+ orders/sec via lock-free MPSC/SPSC queues with sub-microsecond P99 latency. Parses NASDAQ TotalView-ITCH 5.0 protocol and streams live order book data at 60Hz to a React dashboard over a self-implemented WebSocket server.

**[Statistical Arbitrage Research Platform](https://statistical-arbitrage-research-platform-dzkhyve2i625wwbzlrknbz.streamlit.app/)** · Python, Streamlit
> Production-grade pairs trading backtester using Engle-Granger & Johansen cointegration, Kalman filter hedge ratio estimation, and a risk-parity portfolio engine with CVaR, HAC Sharpe, and 2,000-path Monte Carlo simulation. 163/163 pytest tests passing.

**[RL Market-Making Agent](https://rlmarketmaker-7yho3khdjxpcsppuwappuas.streamlit.app/)** · Python, PyTorch, Plotly Dash
> PPO-trained agent quoting BTC-USD bid/ask spreads from Coinbase Advanced Trade REST API data. Implements Avellaneda-Stoikov reward shaping with a 20-dimensional microstructure state vector — achieves 2.4× higher PnL vs. TWAP baseline across 100 out-of-sample episodes.

**[Snap2Plan](https://snap-2-plan.vercel.app/)** · Next.js 16, TypeScript, Supabase
> AI-powered SaaS task manager using Claude (Anthropic) and Gemini Vision APIs to extract structured tasks from handwritten notes, photos, and voice input. Features real-time Kanban sync, Google Calendar OAuth 2.0, and automated email reminders via Vercel cron.

---

<h3 align="left">🛠 Languages & Tools</h3>

<div style="display: flex; gap: 10px; flex-wrap: wrap; align-items: center;">
  <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/></a>
  <a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/></a>
  <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
  <a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>
  <a href="https://pytorch.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/></a>
  <a href="https://www.tensorflow.org" target="_blank"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/></a>
  <a href="https://scikit-learn.org/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/></a>
  <a href="https://opencv.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/></a>
  <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="nextjs" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
  <a href="https://www.djangoproject.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" alt="django" width="40" height="40"/></a>
  <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>
  <a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
  <a href="https://kubernetes.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
  <a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>
  <a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/></a>
</div>

<br/>

---

<h3 align="left">📬 Reach Me</h3>

- 📧 ridham412work@gmail.com
- 💼 [linkedin.com/in/ridham-patel-2003as12](https://www.linkedin.com/in/ridham-patel-2003as12/)
- 💻 [github.com/rcodeborg2311](https://github.com/rcodeborg2311)

<br/>

<div align="left">
  <img height="180" src="https://media1.tenor.com/m/bxe8Qsx3UusAAAAC/cat.gif" alt="cat gif" />
</div>

<br/>

<div align="center">
  <h1 style="font-family: 'Brush Script MT', cursive; font-size: 48px; color: #FF4500;">Carpe Diem.</h1>
</div>
