#  HydroTune

> RL-powered leak identification and repair prioritization

HydroTune is a reinforcement learning-driven system that identifies water leaks and optimizes repair prioritization using pressure, flow rate, and spatial data.



## ⚙️ How It Works

HydroTune uses a Deep Q-Network (DQN) to learn patterns in water network behavior and make data-driven decisions.

- Processes key inputs: Pressure, Flow Rate, Latitude, Longitude  
- Learns to distinguish leak vs non-leak conditions  
- Evaluates severity of identified locations  
- Generates a prioritized repair sequence  



## ✨ Key Highlights

- Intelligent leak identification using reinforcement learning  
- Severity-based prioritization of repair actions  
- Designed for real-world water network optimization  
- Focuses on decision-making, not just detection  
- Produces actionable repair insights  



## 📌 Repair Insights

HydroTune identifies leak-prone locations and prioritizes them based on severity and repair impact.

![Leak Locations](./results/leak_map.png)

The system further highlights critical locations along with severity levels and estimated repair effort to guide repair decisions.

![Output](./results/repair_planning_summary.png)



## 🧩 Applications

- Smart water distribution systems  
- Urban infrastructure monitoring  
- Utility maintenance planning  
- Smart city resource management  



##  Tech Stack

Python · PyTorch · Deep Reinforcement Learning (DQN) · NumPy · Pandas · Scikit-learn  


## 📂 Project Structure

- `src/` — implementation  
- `results/` — outputs  
