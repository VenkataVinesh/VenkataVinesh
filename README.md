<h1 align="center">Venkata Vinesh Kumar Reddy Atluri</h1>

<p align="center">
  <b>ML engineering: time series, signal processing and LLM applications, evaluated honestly.</b><br>
  Python-first, mathematically grounded. I build the model <i>and</i> the service around it.
</p>

<p align="center">
  <a href="https://venkatavinesh.github.io/PortFolio_Build_Gem/">Portfolio</a> ·
  <a href="https://github.com/VenkataVinesh">GitHub</a> ·
  <a href="https://www.linkedin.com/in/venkat-vinesh">LinkedIn</a><br>
  <a href="mailto:venkata-vinesh-kumar-reddy.atluri@etu.ec-lyon.fr">venkata-vinesh-kumar-reddy.atluri@etu.ec-lyon.fr</a>
</p>

---

CS undergrad at **Mahindra University** (CGPA 7.96), now at **École Centrale de Lyon** in Écully
on the **Lyon Centrale Digital Lab 2026-2027** programme. Looking for a **6-month ML / AI
engineering internship from March 2027** (LLM applications, ML engineering, applied deep learning)
in **France, Switzerland or Germany**.

My work clusters around one theme: **modelling noisy, real-world signals** and being straight about
how well the model works. If a number can't be traced back to real data, or isn't labelled as
simulated, it doesn't ship.

---

### Selected work

**[TriageMate](https://github.com/DaPres/SwissAiWeeks_Team_8)** — Hackathon project, Swiss {ai} Weeks Zurich 2026
A triage co-pilot for operational service desks, built for the Swiss Life challenge as a team. It screens an
incoming ticket or email for PII and prompt injection, classifies and routes it, assigns a priority
with a written reason, retrieves similar past cases, and drafts a response an analyst can approve,
edit or reject.
- Found the 20,000-ticket dataset was only 173 unique descriptions with effectively random priority labels: a trained classifier did no better than always guessing the majority class
- Computed priority with an explicit ITIL urgency × impact matrix instead, and used the tickets as a retrieval library rather than training data
- Used the LLM only where judgment was genuinely needed, keeping the pipeline testable
- My part: the classification and retrieval logic and the LLM prompting pipeline
`Python` · `FastAPI` · `React` · `TypeScript` · `Azure AI Foundry` · `SQLite` · `Docker` · `Azure Container Apps`

<p>
  <img src="assets/triagemate/intake.jpg" width="32%" alt="TriageMate intake screen" />
  <img src="assets/triagemate/priority.jpg" width="32%" alt="TriageMate priority result with ITIL matrix" />
  <img src="assets/triagemate/draft-reply.jpg" width="32%" alt="TriageMate draft reply with citations" />
</p>

**PRECITEC confocal sensor: peak detection** — LTDS lab, École Centrale de Lyon, Oct 2026 · *private lab code*
Team of 4. The lab wanted live surface-height measurement from a PRECITEC CHRocodile CLS 2 confocal
line sensor (1,200 channels, one colour spectrum per point) using its own Python software. When two
surfaces are very close their peaks overlap and the vendor software reports one wrong height. My part:
planning, a peak detector that finds every surface even when close, a simulator and fixed benchmark,
lab tests on the real sensor, retraining a neural network, and integrating it into the team's app.
(Acquisition and the viewer were my teammates' work.)
- Lab tests showed the first Gaussian detectors found 4-11 surfaces where there were 2, because real peaks are not Gaussian. The robust detector fits a measured peak template with per-peak width and skew, and chooses the number of peaks with a quasi-BIC rule
- **Real data:** exactly 2 surfaces on 120/120 glass-slide channels (the old Gaussian method found 4); closest pair resolved on a live frame: 0.77 peak widths (4.7 px)
- **Simulated benchmark:** 93% of close pairs found at 0.75 peak widths and 47% at 0.5; 97% of single surfaces and 100% of triples counted correctly
- Derived the theoretical limit (resolvability, Cramér-Rao bound); the detector reaches the limit set by the current 5.6% peak-shape knowledge. Still in progress: calibration at several sensor heights, and a combined robust-plus-network approach
- Code is private (lab project); details on request

`Python` · `NumPy/SciPy` · `PyTorch` · `Qt` · `pytest`

**[Asset Price Prediction Platform](https://github.com/VenkataVinesh/Asset-Price-Prediction-Platform)** — Sequence Models vs Classical Baselines
Puts a stacked LSTM and an ARIMA baseline on the same series so the trade-off is
visible rather than assumed. Index-aligned windowing to prevent leakage; scaler state persisted
with the model so inference reproduces training-time normalization. An async FastAPI service
serves multi-step forecasts with confidence intervals.
`Python` · `PyTorch` · `Statsmodels` · `FastAPI` · `React`

**[Veltrix](https://github.com/VenkataVinesh/Veltrix)** — Market analytics terminal. An example of honest evaluation: GARCH(1,1) intervals measured at 94.75% coverage against a 95% band, and a 50.2% directional hit-rate over 1,500 walk-forward calls reported as no edge.

Also: [Reinforcement Learning Lab](https://github.com/VenkataVinesh/Reinforcement-Learning-Lab) (Q-Learning and SARSA from scratch) · [Portfolio Optimization](https://github.com/VenkataVinesh/Portfolio-Optimization-Dashboard) (Markowitz, SciPy SLSQP) · [Weather Time-Series Forecasting](https://github.com/VenkataVinesh/Weather-Time-Series-Forecasting) (LSTM vs ARIMA/SARIMA)

---

### Next up

**Maintenance Copilot** — *in progress, public when there are results.* An agent for industrial
compressor maintenance: anomaly detection on real compressor telemetry (MetroPT-3), retrieval over
equipment manuals in English, French and German, and cited diagnoses, evaluated on a strict time
split. No results yet.

---

### Skills

- **Languages:** Python, TypeScript
- **ML / DL:** PyTorch, Statsmodels, LSTM, 1-D U-Net, time-series forecasting, signal processing
- **LLM & data:** LLM prompting pipelines, retrieval, NumPy / SciPy (least squares), Pandas
- **Engineering:** FastAPI, React, Docker, Qt, multiprocessing, pytest, Git

### Languages spoken

English (fluent) · Telugu (native) · Hindi (conversational) · French (A1, in progress)
