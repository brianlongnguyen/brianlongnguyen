<h1 align="center">Brian Nguyen</h1>
<h3 align="center">Optimization • Simulation • AI-Enabled Decision Systems</h3>
<p align="center"><strong>MBA Candidate | Management Analytics | Autonomous Vehicles | Robotics | Reinforcement Learning | Decision Optimization</strong></p>

> *Decision science leader specializing in optimization, simulation, and reinforcement learning for safety-critical and high-stakes systems.*

---

# 🌐 About Me

I design decision systems where tradeoffs, risk, and safety matter more than point predictions. With a professional background in autonomous vehicles and robotics, I specialize in prescriptive analytics and reinforcement learning to support executive decision-making in safety-critical and capital-intensive domains.

---

# 🧠 How I Think

- 🎯 **Decision-First, Model-Second** — analytics exists to improve decisions, not to showcase models  
- ⚖️ **Explicit Tradeoffs & Constraints** — real systems operate under safety, regulatory, and resource limits  
- 🎲 **Uncertainty Is Central** — risk, variance, and tail outcomes matter as much as expected value  
- 🧭 **Governable & Interpretable Systems** — preference for solutions executives can understand, trust, and scale  
- 🚦 **Safety-Critical Mindset** — experience designing analytics where failure carries real-world consequences  

> *My goal is to design analytics and AI systems that improve decision quality while remaining robust, interpretable, and accountable.*

---

# 🧩 My Work Spans

- 🔢 **Optimization (LP/MIP)** — optimal resource allocation under business rules  
- 🎲 **Monte Carlo Simulation** — modeling uncertainty & financial risk  
- 🤖 **Reinforcement Learning (Multi-Armed Bandits)** — systems that learn in real time  
- 📊 **Business & Operational Strategy** — translating analytics into managerial action

> *My long-term career trajectory is toward becoming a **hybrid executive** — a leader fluent in business, analytics, and AI — positioned for U.S.-remote roles at the intersection of strategy and technology.*

---

# 🛠️ Technical Stack

### **Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### **Optimization & OR**
![PuLP](https://img.shields.io/badge/PuLP-00457C?style=for-the-badge)
![OR-Tools](https://img.shields.io/badge/OR--Tools-4285F4?style=for-the-badge&logo=google)
![SciPy](https://img.shields.io/badge/SciPy-blue?style=for-the-badge&logo=scipy)

### **Simulation**
![Numpy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)

### **Reinforcement Learning**
![RL](https://img.shields.io/badge/Reinforcement%20Learning-FFD700?style=for-the-badge)
![MAB](https://img.shields.io/badge/Multi--Armed%20Bandits-FA7343?style=for-the-badge)

### **Visualization**
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge)

### **Productivity**
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter)

---

# 📁 Featured Projects

### 🚗 Prescriptive Analytics for Pedestrian Collision Avoidance  
**Multi-Armed Bandit Optimization for Autonomous Vehicle Safety Testing**

- **Decision problem:** Autonomous systems must choose evasive maneuvers under asymmetric risk and incomplete information. The problem is not merely computing collision probabilities — it is deciding which action minimizes expected harm when uncertainty is high and failure is irreversible.
- **Approach:** Formulated as a multi-armed bandit with epsilon-greedy exploration. Simulated heterogeneous pedestrian–vehicle encounters across velocity differentials and safety penalties. Compared rewards under alternative policies to examine how risk preferences shift optimal maneuver selection.  
- **Impact:** Formulated as a multi-armed bandit with epsilon-greedy exploration. Simulated heterogeneous pedestrian–vehicle encounters across velocity differentials and safety penalties. Compared rewards under alternative policies to examine how risk preferences shift optimal maneuver selection.  

➡ **Repository:** https://github.com/brianlongnguyen/analytics-ai-portfolio/tree/main/reinforcement_learning/av_pedestrian_avoidance_bandit

### ⚠️ NDA & Confidentiality Notice

This project is an independent, academic-style simulation based on publicly discussed autonomous vehicle safety challenges and standard reinforcement learning techniques.  

No proprietary data, internal testing results, source code, sensor logs, simulation environments, or confidential materials from Zoox, Cruise, Google, or any other organization were used or referenced.  

All data, scenarios, and results shown are synthetic and intended solely to demonstrate analytical methodology and decision-system design.

---

### 🍇 Landhills Winery — Optimal Blending Plan (LP/MIP)
**Prescriptive Analytics Using Linear & Mixed-Integer Optimization**

- **Decision problem:** Blending choices must satisfy regulatory, quality, and capacity constraints while maximizing profitability. This creates a multi-criteria resource allocation problem where feasible space is narrow and non-intuitive.  
- **Approach:** Linear and mixed-integer programming formulation with quality, volume, and regulatory constraints. Solved via LP/MIP with explicit variable interpretation for managerial transparency. Conducted sensitivity to evaluate how minor shifts in composition parameters influence feasible region and optimal blends.  
- **Impact:** Illustrates how constrained optimization outperforms heuristic or intuition-driven blending. Generalizes to chemicals, energy, supply chains, food & beverage, and any domain where physical composition, capacity, or compliance constraints shape feasible decisions.  

➡ **Repository:** https://github.com/brianlongnguyen/analytics-ai-portfolio/tree/main/optimization/landhills-winery-optimal-blending

---

### 📦 Konys Inc. — Procurement Risk Monte Carlo Simulation
**Monte Carlo Simulation for Contract Design and Risk Transfer**

- **Decision problem:** Procurement decisions must balance cost, uncertainty, and downside exposure. Contract structure (purchase vs option vs spot) changes the distribution of outcomes, not just expected value. The key decision variable is therefore not price minimization, but risk transfer under volatility.  
- **Approach:** Modeled demand and spot price uncertainty via Monte Carlo simulation. Compared purchase and option contracts using expected profit, percentile outcomes, and risk metrics. Evaluated flexibility premiums and tail risk to determine which policies create economic resilience under high volatility. 
- **Impact:** Shows how simulation can make contract design and risk management tractable for executives. Extends to commodities, supply chain, energy, semiconductors, and regulated industries where volatility and supply constraints drive procurement decisions.  

➡ **Repository:** https://github.com/brianlongnguyen/analytics-ai-portfolio/tree/main/simulation/konys-procurement-risk-monte-carlo

---

### 🚚 Capacity-Constrained Network Flow Optimization (LP)
**Decision system for routing flow across multi-node networks under capacity and cost constraints**

- **Decision problem:** How should flow be routed through a constrained network to meet demand at minimum cost, recognizing that system-wide performance depends on bottlenecks, interdependencies, and binding constraints rather than isolated path decisions?
- **Approach:** Linear programming formulation with capacity, cost, and conservation constraints. Solved using PuLP with explicit shadow-price interpretation to identify binding capacity and marginal value of additional throughput.  
- **Impact:** Demonstrates how systems thinking + optimization can diagnose where interventions matter. Generalizes to supply chain logistics networks, transportation routing, energy infrastructure, and other resource allocation problems governed by constraints rather than heuristics.

➡ **Repository:** https://github.com/brianlongnguyen/analytics-ai-portfolio/tree/main/optimization/network-flow-min-cost-routing

---

### 💊 Moore Pharmaceuticals (Monte Carlo NPV Under Regulatory & Market Uncertainty)
**Decision system for routing flow across multi-node networks under capacity and cost constraints**

- **Decision problem:** Drug portfolio decisions involve market, regulatory, and timing uncertainty. Conventional NPV undervalues option-like payoffs and overstates certainty, leading to suboptimal investment choices in later-stage development.
- **Approach:** Monte Carlo simulation with multi-dimensional uncertainty (market size, pricing, delay risk, regulatory probability). Compared deterministic vs stochastic NPVs and examined how volatility shifts optimal investment choices. Highlighted the managerial value of time and optionality under regulatory timelines. 
- **Impact:** Demonstrates how simulation improves capital allocation in high-uncertainty environments. Applies to life sciences, biotech, energy infrastructure, and other long-cycle industries where decision quality hinges on probabilistic economic outcomes rather than point estimates.

➡ **Repository:** https://github.com/brianlongnguyen/analytics-ai-portfolio/tree/main/simulation/simulation/moore-pharmaceuticals-monte-carlo

# 🧭 Professional Focus

### **Building toward roles such as:**
- Chief Data & Analytics Officer (CDAO)  
- Chief Operating Officer (COO)  
- VP of Analytics / Strategy / Operations  
- Director of Decision Science / Optimization / AI  

### **Core strengths:**
- Translating business problems into mathematical models  
- Quantifying uncertainty for better strategic decisions  
- Designing AI-enabled operational systems  
- Communicating technical findings to executive stakeholders  

---

# U.S.-Remote Career Alignment

Originally from the **San Francisco Bay Area**, I maintain strong ties to U.S. markets and am targeting **U.S.-based remote roles** in:

- Analytics  
- AI/ML decision systems  
- Operations & strategy  
- Data-driven leadership  

I aim to bridge Canadian residency with U.S. compensation and leadership opportunities.

---

# 📫 Connect With Me

- **LinkedIn:** _[https://www.linkedin.com/in/brianlongnguyen/]_  
- **Email:** _[brianlongnguyen@gmail.com]_  

I’m always open to discussing optimization, simulation, AI systems, or leadership opportunities anywhere in North America.

---

<p align="center"><strong>"Always learning. Always optimizing. Always building."</strong></p>
