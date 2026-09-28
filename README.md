<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Courier+Prime&weight=700&size=20&pause=1100&color=F5C518&center=true&vCenter=true&width=680&lines=%E2%99%A0+Shuffling+up+and+dealing...;%E2%99%A5+Founder%27s+Associate+%40+AVARA;%E2%99%A6+Research+Engineer+%40+PolicySim+AI;%E2%99%A3+1M+agents+on+the+table.+Your+move." alt="Typing SVG" />
</a>

<p>
  <a href="https://linkedin.com/in/adityamenonn"><img src="https://img.shields.io/badge/%E2%99%A0%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:menonadityaaltis@gmail.com"><img src="https://img.shields.io/badge/%E2%99%A5%20Email-D62839?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/%E2%99%A6%20Seat-London%2C%20UK-0A4A2E?style=for-the-badge"/>
</p>

</div>

## 👑 Player Card

<div align="center">
<img src="./assets/player-hud.svg" width="100%" alt="King of Hearts player card. Aditya Menon, BSc Computer Science at UCL (expected First). Founder's Associate at AVARA and Research Engineer at PolicySim AI. Strongest in ML/AI, simulation and a perfect poker face. Away from the table: poker, Valorant, karting, running."/>
</div>

<img src="./assets/divider-lineclear.svg" width="100%"/>

## ♠ The Hand So Far

<div align="center">
<img src="./assets/hand-so-far.svg" width="100%" alt="A deck is shuffled and five board cards are dealt: A♠ UCL (BSc Computer Science), K♥ TCL Electronics (Data Science Intern), Q♦ PolicySim AI (Research Engineer), J♣ AVARA (Founder's Associate), and a face-up question mark on the river: looking for internships."/>
</div>

<img src="./assets/divider-lineclear.svg" width="100%"/>

## ♦ Showdown: Hand Rankings

> Six projects, ranked like poker hands. The best hand is at the top.

<table>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-1-royal-flush.svg" width="250"/><br/>
<b>👑 Royal Flush</b><br/><sub>the nuts</sub>
</td>
<td valign="top">

### [PolicySim: Labour-Market ABM at Scale](https://github.com/adityamenonnn/policysim-mesa)
`Python` `Mesa` `NumPy` `pandas`

Agent-based simulation of UK AI-driven job displacement. Each agent's `step()` is collapsed into one vectorised NumPy multiply with a row-wise softmax, and the model is calibrated on 8 merged UK labour datasets (a 255 × 166 quarterly panel). Includes scaling benchmarks, a feedback-loop analysis and a policy sweep.

**Scales to 1M agents · 17.57 ms mean tick at 100K · near-linear to 300K**

</td>
</tr>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-2-straight-flush.svg" width="250"/><br/>
<b>♦ Straight Flush</b><br/><sub>one card short of perfect</sub>
</td>
<td valign="top">

### [RAG with a Real Evaluation Harness](https://github.com/adityamenonnn/Requests-Library-RAG-With-Evaluation)
`Python` `ChromaDB` `sentence-transformers` `Groq / Llama 3.1`

A retrieval-augmented Q&amp;A system over the Python `requests` docs. Retrieval and generation are scored separately (Hit Rate@k, MRR, LLM-as-judge), trap questions test whether it refuses instead of hallucinating, and a chunk-size ablation comes with a written failure analysis.

**100% Hit Rate@3 · 0.931 MRR · 4.12/5 judge score · 0% hallucination on trap questions**

</td>
</tr>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-3-four-of-a-kind.svg" width="250"/><br/>
<b>♣ Four of a Kind</b><br/><sub>quads, and the blocks stack themselves</sub>
</td>
<td valign="top">

### [Tetris AI: Lookahead Search + Genetic Algorithm](https://github.com/adityamenonnn/tetris)
`Python` `Tkinter` `curses` `sockets`

An autonomous agent that scores placements on a multi-feature heuristic (holes, bumpiness, wells, transitions, danger zone) with two-piece lookahead, and uses bombs and discards tactically. A from-scratch GA with tournament selection, uniform crossover, Gaussian mutation and elitism evolves the weights. No ML libraries.

**Up to 1,600 board states per move · +34% average score over baseline across 700 seeds**

</td>
</tr>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-4-full-house.svg" width="250"/><br/>
<b>♥ Full House</b><br/><sub>hardware + firmware + cloud, all filled</sub>
</td>
<td valign="top">

### [Integrated Bioreactor for TB Vaccine Production](https://github.com/adityamenonnn/Integrated-Bioreactor)
`C/C++` `ESP32` `MQTT` `ThingsBoard` `scikit-learn`

A team-built modular ESP32 controller with independent pH, stirring and heating subsystems. It streams telemetry to ThingsBoard over MQTT and accepts remote setpoints through shared attributes and RPC. Anomaly detection runs on the sensor data.

**±0.4 °C stability · 500–1500 RPM held within ±20 · 98% single-fault detection (One-Class SVM)**

</td>
</tr>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-5-flush.svg" width="250"/><br/>
<b>♠ Flush</b><br/><sub>every card the same suit: clean OOP</sub>
</td>
<td valign="top">

### [Patient Data App](https://github.com/adityamenonnn/COMP0004-Patient-Data-App)
`Java` `OOP`

A patient-records application built for UCL's COMP0004 module, focused on object-oriented design: clean class structure, encapsulation, and separating data handling from presentation.

**UCL COMP0004 coursework**

</td>
</tr>
<tr>
<td width="260" align="center" valign="middle">
<img src="./assets/hand-6-straight.svg" width="250"/><br/>
<b>♣ Straight</b><br/><sub>where the run started</sub>
</td>
<td valign="top">

### [Facial Recognition](https://github.com/adityamenonnn/Facial-Recognition)
`Python` `OpenCV`

My first computer-vision project. It detects faces in a live video feed with Haar cascades, captures a personal face dataset, and recognises known faces in real time.

**The first card in the sequence**

</td>
</tr>
</table>

<img src="./assets/divider-lineclear.svg" width="100%"/>

## ♣ Chip Count

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=adityamenonnn&theme=github_dark&bg_color=0a4a2e" width="100%" alt="Profile details and contribution graph"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=adityamenonnn&theme=github_dark&bg_color=0a4a2e" height="170" alt="GitHub stats"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adityamenonnn&theme=github_dark&bg_color=0a4a2e" height="170" alt="Repos per language"/>

<img src="https://streak-stats.demolab.com?user=adityamenonnn&background=0A4A2E&border=F5C518&stroke=F5C518&ring=F5C518&fire=D62839&currStreakNum=FDF6E3&sideNums=F5C518&currStreakLabel=F5C518&sideLabels=FDF6E3&dates=9FC7B4&border_radius=10" alt="Contribution streak"/>

</div>
