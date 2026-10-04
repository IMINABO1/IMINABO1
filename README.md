# Hi there, I'm Iminabo Roberts! 👋

### 🚀 Software Engineer | Machine Learning Engineer | Hardware & Systems

I'm a Computer Science **and** Electrical Engineering student at Grambling State University (GPA 3.88, graduating May 2028). I like the layer where software meets the metal — packet pipelines that have to close timing, CUDA kernels that have to beat the CPU, agents that have to price their own uncertainty. I build it, then I try to break it and write down what actually happened. The `problems_encountered.md` in my repos is usually the most interesting file.

🌐 **[Portfolio](https://react-portfolio-tau-dun.vercel.app/)** | 💼 **[LinkedIn](https://www.linkedin.com/in/iminabo-roberts/)** | 📧 **iminaboroberts@gmail.com**

---

## Toolbox

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python, C++, C, Java, JavaScript/TypeScript, SystemVerilog, CUDA C++, Swift, Kotlin, OCaml, R, HTML/CSS |
| **ML & Data** | PyTorch, TensorFlow, HuggingFace, SageMaker, NumPy, Pandas, Scikit-learn, Apache Spark, Tableau |
| **Systems & Hardware** | Xilinx Vivado, cocotb, Arduino, Raspberry Pi, ROS2, Fusion 360 / Onshape CAD, NI Multisim, I2C, Kali Linux |
| **Backend & Infra** | Node.js, FastAPI, Flask, gRPC, Kafka, Docker/Kubernetes, AWS (EKS, S3, SageMaker), GCP, MySQL, MongoDB, Grafana |

---

## 💼 Experience

### 🍎 Apple — Machine Learning Engineering Intern, *Xcode Intelligence*
*May 2026 – Aug 2026*
*   Built a recursive self-improving loop for Xcode coding agents that consolidates and replays their own history.
*   Designed a heartbeat that continuously updates and merges stored context to steer generation.
*   Built an evaluation harness benchmarking agent performance — **measured a 69% gain at lower cost.**

### 🔵 Google — Open Source Contributor, *[TestRun](https://github.com/google/testrun)*
*April 2026*
*   Added **static IP support** to Google TestRun, which previously handled only DHCP assignment.
*   Investigated and resolved test-execution inconsistencies by debugging across distributed workflows.
*   Collaborated with maintainers through issue discussions and code reviews to align fixes with project architecture.

### 🎮 GotGames — Machine Learning Engineering Intern, *AI Integration Team*
*Aug 2025 – Dec 2025*
*   Scaled backend throughput **30%** by running PyTorch/HuggingFace inference on EKS with gRPC and S3-backed services.
*   Automated retraining on AWS SageMaker with datasets in S3, ensuring continuous model updates.
*   Reduced downtime by implementing monitoring with Grafana.

### 🔬 Grambling State University & LaSPACE — Physics Research Assistant
*Sep 2025 – Present*
*   Investigating temperature and surfactant effects on nanoparticle size measurement via Dynamic Light Scattering.
*   Statistical validation and modeling in Python (NumPy/Pandas), improving nanoparticle characterization accuracy for laser-ablation research.

### 📈 IMC Trading — Prosperity Challenge, *Global Algorithmic Trading Competition*
*Mar 2025 – Apr 2025*
*   Applied game theory and decision theory to price auction bids under strategic uncertainty.
*   Ranked strategies by probability-weighted expected value on z-scored surfaces in pandas.
*   **Placed in the top 10% of 12,000+ teams.**

### 🤖 Grambling State University — Robotics / Hardware Engineering Intern
*Jan 2025 – Apr 2025*
*   Built a chest-worn heartbeat monitor in C++ on Arduino, streaming live waveforms to a display.
*   Detected arrhythmias via real-time signal analysis using I2C and oscilloscope diagnostics.

### 🦾 AI & Robotics Lab (MIT / MTN sponsored) — Robotics Engineer Intern
*Sep 2023 – May 2024*
*   Earned a spot in a competitive program with a **21% acceptance rate**.
*   Enhanced robot mobility **75%** developing in Java on Ubuntu with Raspberry Pi.
*   Mentored a Nigerian FIRST Robotics team on low-level concepts, Android Studio, the FTC SDK, and Onshape CAD.

<details>
<summary><b>Earlier roles</b></summary>

**💡 Intel — Student Ambassador** *(Feb 2025 – Sep 2025)* · Invitation-only program recognizing top student leaders in AI and software development. Led workshops and peer sessions on Intel technologies including oneAPI and OpenVINO.

**🏢 Super Original Corps — Software Development Intern, Backend Team** *(Jun 2023 – Sep 2024)* · Automated real-time data collection for 70 clients, boosting analytics 50% (Python, Pandas, Scikit-learn). Led a 5-member team building a scalable UI in JS/Node/Next/React.

**🧩 Fladov — Software Engineer Intern, Machine Learning Team** *(Aug 2023 – Sep 2024)* · Boosted service speed 30% scaling backend systems with Kubernetes and PHP. Engineered a TensorFlow/HuggingFace model for business analytics. Ran Agile Scrum workflows.

**✍️ The WAAS Project — Technical Writing & SWE Tutor Intern** *(Dec 2022 – May 2023)* · Early-stage edtech startup delivering Web3 and software education across Africa. Produced onboarding documentation and tutored students on backend systems and crypto fundamentals.

</details>

---

## 🔬 Selected Projects

### ⚡ [fluxNIC](https://github.com/IMINABO1/fluxNIC) — Programmable FPGA Network Data Plane
*SystemVerilog*
*   A SystemVerilog pipeline parsing Ethernet / IPv4 / UDP to drop, forward, timestamp, or rewrite.
*   Pipelined a **4-stage datapath on 64-bit AXI-Stream at one word per cycle**, loading flow tables over AXI-Lite.
*   Verified with randomized cocotb testbenches, **targeting 250 MHz** while trading pipeline depth against latency and LUTs.

### 🐝 [FractalHive](https://github.com/IMINABO1/fractal_hive) — Compute-Auction Mandelbrot Renderer
*OCaml & Unix sockets*
*   An OCaml tile server where image tiles **bid for compute**, so high-detail boundary regions render first.
*   Parallelized across N Domain workers pulling from a bid-sorted queue via a **lock-free atomic cursor**.
*   **Cut render time 2.44×** by letting drained workers steal across markets — utilization went from 35% to 88%.

### 📊 [SynthFlow](https://github.com/IMINABO1/SynthFlow) — Generative Models for Limit Order Books
*Python & C++*
*   Built a WGAN-GP *and* a diffusion model in PyTorch on FI-2010 limit order books.
*   **Raised generated book validity from 0% to 100%** with a cumulative-softplus gap generator — validity by construction, not by penalty.
*   Evaluated on spread, depth, and order imbalance against real market data.

### 🎴 [Pokémon TCG AI Agent](https://github.com/IMINABO1/Pokemon_tcg_ai_battle) — Search Under Imperfect Information
*Python & C++*
*   Shipped a heuristic agent to a live Kaggle ladder of roughly **5,000 competing teams**.
*   Built **Perfect Information Monte Carlo** search over the competition's C++ forward model, averaging over sampled hands.
*   Modeled hidden opponent hands via determinization sampling, weighting guesses by observed play patterns.

### 📉 [BidBeam](https://github.com/IMINABO1/BidBeam) — Order Book Engine & Market Data Pipeline
*C++ & Python*
*   A C++ order book engine publishing trades to Kafka with asynchronous librdkafka callbacks.
*   Handled concurrency with one thread per instrument bridged into an asyncio event loop.
*   Streamed real-time market data over gRPC and WebSocket with backpressure on a 100 ms timeout.

### 🎥 [CudaCornerTracker](https://github.com/RBelex-007/Cuda_CornerTrack) — Real-Time GPU Vision Pipeline
*C++ & CUDA*
*   Shi–Tomasi corner detection on CUDA using GpuMat, `cudaimgproc`, and `cudaarithm`.
*   **60 FPS on an RTX 3050 — 4× faster than the CPU baseline** via optimized memory transfers.

### 🧠 [Project ATHENA](https://github.com/IMINABO1/A.T.H.E.N.A.) — Natural Language Desktop Agent
*Python & Java*
*   A multimodal assistant combining screen vision, LLM parsing, and voice commands to automate app workflows.
*   Semantic search across the device file system using embeddings to contextualize prompts.
*   Streamed audio output before model completion for **sub-150 ms time-to-first-response**. Extending to Android via Appium.

### 👻 AutoMCP — Automated MCP Tool Generation *(IBM Dev Days)*
*Python*
*   A Playwright agent deriving read **and** write MCP tools from a URL via the accessibility tree.
*   Parallelized network analyzer generating async Python tools, **filtering 70% of noise**.
*   Self-healing auth for CSRF and cookies, eliminating manual agent re-login.

### 🦵 [SmartKnee](https://github.com/TonAldo48/devdays-healthtech) — Wearable Injury-Risk Sensing · *[dashboard](https://smartsleevedashboard.vercel.app/)*
*C++ & Python*
*   Bilateral knee sensors in C++ on Arduino Nano BLE streaming IMU data over Bluetooth.
*   Trained an **LSTM risk model** on movement time series to flag injury risk against baseline patterns.
*   Computed 5 movement metrics from raw IMU samples **at 200 Hz on device**, streamed to a Vercel dashboard over WebSockets.

### 🧩 [Prisma](https://github.com/IMINABO1/HackMIT-_2025_Prisma) — Context-Aware Study Extension *(HackMIT 2025)*
*JavaScript & Python*
*   A Chrome extension injecting AI nudges via Node.js, Tailwind, and the OpenAI/Claude APIs.
*   Supabase memory with embedding search, recalling past interactions to personalize guidance.
*   **Sub-200 ms hint latency and 65% distraction reduction.**

<details>
<summary><b>More projects</b></summary>

*   **[Matrix Multiplier](https://github.com/IMINABO1/Matrix_Multiplier)** — naive and tiled matmul kernels in CUDA C++ and Numba; optimized shared-memory tiling and block scheduling, benchmarked to find the crossover.
*   **[ClassSync](https://github.com/AdrDube/Classync)** *(Apple HBCU C2)* — native iOS attendance automation via real-time presence detection; Nearby Share + Firebase + MVVM, **75% check-in latency reduction**.
*   **[MissDiagnosis AI](https://github.com/IMINABO1/MissDiagnosis)** *(Notion Hackathon '24 — 3rd place)* — team lead; microservices AI chatbot for real-time diagnostic suggestions using GPT-4, VGG19, and RL on medical imaging. **92% accuracy.**
*   **[TheraPlane](https://theraplane-hlu6.onrender.com/)** *(HackHarvard '24)* — an AI therapist with RAG over ChromaDB, guided by HCI principles for emotional accessibility.
*   **Project CODY** *(UNILAG AIRLAB)* — hardware lead & PM on an autonomous tour-guide robot; navigation via Arduino + Raspberry Pi, **+75% mobility, +70% speed**.
*   **SwiftScan** — offline-first QR scanner; Core Data, AVFoundation, SwiftUI/UIKit.
*   **[Image2Sound](https://github.com/IMINABO1/Image2Sound)** — RGB→HSV, hue mapped to pitch across three octaves; 64× pixel reduction via average pooling, two-voice polyphony.
*   **[Portfolio Optimization](https://github.com/RBelex-007/Optimal_Portfolio)** — Modern Portfolio Theory to maximize Sharpe ratio; YFinance, Pandas, Matplotlib, Seaborn.

</details>

---

## 🏆 Honors & Awards

*   **FIRST Tech Robotics Challenge** — National Winners · **Inspire Award**
*   **National Informatics Olympiad** — Finalist
*   **Putnam** competitor
*   **Microsoft Imagine Cup** — Pre-Semifinalist
*   **Notion Hackathon** — 3rd place · **GDSC Coding Competition** — 2nd place
*   **Nexus Louisiana DevDays ClimateTech** — Finalist · **BeSmart Hackathon** — Finalist

---

## 🌟 Heart & Leadership

I believe in lifting others as I climb. Technology is empty without community, and these are the spaces where I pour my energy outside of building software:

*   **ColorStack @ Grambling State — Academic Chair** *(Jan 2025 – Present)*: Supporting Black & Latinx computer science students throughout their college careers; organizing workshops and helping members work through hard technical problems.
*   **NSBE @ Grambling State — Community Service Chair** *(Feb 2025 – Present)*: Coordinating STEM outreach events and mobilizing members to mentor local students.
*   **Grambling Robotics Club — Vice President** *(Aug 2025 – Present)*: Leading weekly design-and-prototyping sessions; training peers in Arduino IDE, ROS2, Fusion 360, Onshape CAD, and TinkerCAD.
*   **Competitive Programming Club — Head**: Built **[CF:ICPC](https://github.com/IMINABO1/GramblingXICPC)**, a training platform for our 8-person ICPC team — ~220 Codeforces problems in a prerequisite-gated skill tree, per-member progress tracking, and a 10,700-problem similarity graph. A "Codeforces 220" built for ICPC's mathematical breadth rather than interview pattern-matching.
*   **Programs & fellowships**: Bloomberg Accelerator Fellow · Intel Student Ambassador · NVIDIA Summer Bridge · eBay Pathways · LS-LAMP Research Intern · Brilliant Black Minds (Karat) · Earl Lester Honors College · ACM · Lantern Network · General Assembly Immersive

---

### 📚 What I'm Up To Outside of Code

*   **Teaching models to play games for fun:** [Super Mario Bros](https://github.com/IMINABO1/SuperMario-AI), [Sonic 2](https://github.com/IMINABO1/Sonic-AI), and the [Google Dino game](https://github.com/IMINABO1/Google-Dino-AI) — all reinforcement learning, all slightly cursed.
*   **Writing things down:** every serious repo of mine ships a `journal.md` and a `problems_encountered.md`. The failures are the useful part, and I'd rather publish them than pretend the first approach worked.
*   **Robotics for its own sake** — FIRST alum, and I still like putting sensors on things that don't strictly need sensors.
