# Discrete Event Simulation of Stochastic Client-Server Interactions**

---

### **Project Overview**
This project explores the modeling of queuing systems using discrete event simulation (DES) to analyze stochastic client-server interactions. Specifically, the focus is on understanding how different server configurations and service rate distributions affect system performance, such as waiting times and overall efficiency. The goal is to provide insights into optimizing system setups by examining key factors like server numbers, scheduling strategies (e.g., FIFO vs. SJF), and various service rate distributions (e.g., deterministic, exponential, hyperexponential). The simulation helps identify the impacts of these configurations on performance metrics in environments where demand may exceed available resources, necessitating effective queuing strategies.

---

### **Authors**  
- **Maarten Stork** - 15761770  
- **Paul Jungnickel** - 15716554  
- **Lucas Keijzer** - 14041073  

---

### **Files**  
- **`MaartenStork_15761770_PaulJungnickel_15716554_LucasKeijzer_14041073.ipynb`**  
  The main notebook containing the results and analysis.  
- **`stochasticQueueing.py`**  
  A Python script containing the Discrete Event Simulation (DES) implementation.  
- **`/plots`**  
  Directory containing all plots generated during the analysis.  

---

### **Dependencies**  
This project uses the following Python packages:  

- **`simpy`**: For simulating discrete event systems.  
- **`queue`**: For queue data structures and operations.  
- **`numpy`** (`np`): For numerical operations and random number generation.  
- **`matplotlib`** (`plt`): For creating visualizations and plots.  
- **`scipy.stats`**: Used for statistical tests (e.g., Mann-Whitney U test, Kruskal-Wallis test).

