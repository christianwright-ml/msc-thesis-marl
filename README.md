# Cooperative Multi-Agent Reinforcement Learning (MARL) – Efficiency Enhancement

This project explores strategies to improve **training efficiency in cooperative multi-agent reinforcement learning (MARL)**. Cooperative MARL is widely applicable to complex multi-agent systems, including autonomous vehicles, robotic swarms, distributed networks, and energy systems.

---

## Motivation

- Cooperative MARL models and analyses complex systems with multiple decision-makers.  
- Key challenges in MARL: high training time, large data requirements, and computational costs.  
- Cooperative settings add complexity due to **non-stationarity, credit assignment, and scalability**.  
- Efficient learning is critical for practical deployment in real-world cooperative systems.

---

## Objectives

1. Investigate **factors influencing efficiency** in cooperative MARL, including:  
   - Modelling strategies  
   - Reward structures  
   - Decision-making frameworks

2. Develop theoretical insights to guide design of efficient learning algorithms.  

3. Conduct **experimental evaluations** to test efficiency-enhancing methods in cooperative MARL environments.  

4. Bridge **conceptual understanding with empirical evidence** to advance practical applicability of MARL.

---

## Methodology

- **Theoretical Analysis**: Identify strategies to improve learning efficiency and formulate hypotheses.  
- **Experimental Investigation**: Evaluate efficiency-enhancing techniques both individually and in combination.  
- **Composite Method**: Combines three key strategies:  
  - **Reward shaping** via artificial potential fields  
  - **Shared state-space history**  
  - **Curiosity-driven / intrinsic motivation mechanisms**  

- Performance metrics: learning speed, convergence stability, and coordination efficiency among agents.

---

## Visualizations

### Training Phase – Exploration

![Exploration Phase](assets/exploration.gif)  
*Agents exploring the environment during training, learning cooperative strategies.*

### Execution Phase – Exploitation

![Exploitation Phase](assets/exploitation.gif)  
*Agents executing learned policies, demonstrating coordinated behavior in the environment.*

---

## Contributions

- Synthesizes prior work on efficiency in cooperative MARL into a structured perspective.  
- Introduces a **novel composite approach** that unifies reward shaping, shared state-space, and intrinsic motivation for efficiency.  
- Provides experimental evidence on how these combined methods improve learning efficiency in cooperative multi-agent systems.  
- Advances both **theoretical understanding** and **practical application** of cooperative MARL.

---

## Potential Applications

- Autonomous driving coordination  
- Robotic swarms and collaborative robotics  
- Distributed telecommunications and networked systems  
- Energy grid optimization and distributed control

---

## Tools & Technologies

- Python 3.x  
- PyTorch / TensorFlow for RL environments  
- Multi-agent simulation frameworks  
- NumPy, pandas, Matplotlib for data handling and visualization

---

## Notes

This project is primarily **research-focused** and explores efficiency enhancement in cooperative MARL rather than deployment-ready software.
