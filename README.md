
# Aditya Menon

CS @ UCL · Founder's Associate @ AVARA

Building and thinking about agents, simulation and ML systems.

---

### Latest

**[Sonarity](https://github.com/shashankdurgad/sonarity)** · Agentverse 2026, Robotics track

Autonomous underwater robot that surveys the seabed for unexploded ordnance, and imagines what a contact looks like before moving closer.

- YOLOv8 sonar detection, keep-out zones and A* re-planning, all computed on board from its own sensors
- NumPy sonar model renders bomb vs rock from 4 sides (16 views in ~0.4 s) to pick the most informative inspection angle
- Gemma 4 multimodal classification on camera + sonar, with an on-board rule fallback



https://github.com/user-attachments/assets/55bb5afe-d776-43cc-884a-7bb2143677e9



`Python · Isaac Sim · OceanSim · YOLOv8 · Gemma · Modal`

---

### Projects

**[Should Arteta Be Worried?](https://github.com/adityamenonnn/should-arteta-be-worried)** · Arsenal fan sentiment tracker + squad chemistry optimiser

- Scrapes r/Gunners every 6h; TF-IDF + LogReg classifier with football-specific label correction beats VADER by 18% F1
- Squad modelled as a 4-3-3 chemistry graph; Branch and Bound finds optimal signings with ~10x fewer nodes than brute force, plus Monte Carlo over stat uncertainty

`Python · FastAPI · scikit-learn · SQLite · GitHub Actions`

**[PolicySim](https://github.com/adityamenonnn/policysim-mesa)** · Agent-based model of UK AI-driven job displacement

- Agent `step()` vectorised into one NumPy multiply + row-wise softmax; scales to 1M agents
- Calibrated on 8 merged UK labour datasets; 17.57 ms mean tick at 100K agents

`Python · Mesa · NumPy · pandas`

**[RAG Evaluation Harness](https://github.com/adityamenonnn/Requests-Library-RAG-With-Evaluation)** · Q&A over the `requests` docs

- Retrieval and generation scored separately: Hit Rate@k, MRR, LLM-as-judge, trap questions
- 100% Hit Rate@3 · 0.931 MRR · 0% hallucination on traps

`Python · ChromaDB · sentence-transformers · Llama 3.1`

**[Tetris AI](https://github.com/adityamenonnn/tetris)** · Lookahead search + genetic algorithm

- Two-piece lookahead over up to 1,600 board states per move; weights evolved by a from-scratch GA
- +34% average score over baseline across 700 seeds

`Python`

**[Integrated Bioreactor](https://github.com/adityamenonnn/Integrated-Bioreactor)** · ESP32 controller for TB vaccine production

- pH, stirring and heating subsystems streaming telemetry over MQTT
- ±0.4 °C stability · 98% fault detection with a One-Class SVM

`C++ · ESP32 · MQTT · scikit-learn`

---

### Stack

`Python` `TypeScript` `Java` `C++` `SQL` · `PyTorch` `scikit-learn` `NumPy` `pandas` · `Next.js` `React Native` `Spring Boot` `Supabase` `PostgreSQL`

---

[Email](mailto:menonadityaaltis@gmail.com) · [LinkedIn](https://linkedin.com/in/adityamenonn)
