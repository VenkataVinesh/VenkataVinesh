<h1 align="center">Venkata Vinesh Kumar Reddy Atluri</h1>

<p align="center">
  <b>ML / Deep Learning Engineering</b> — time-series forecasting, optimization, and reinforcement learning.<br>
  Python-first, mathematically grounded. I build the model <i>and</i> the service around it.
</p>

<p align="center">
  <a href="https://venkatavinesh.github.io/PortFolio_Build_Gem/">Portfolio</a> ·
  <a href="https://github.com/VenkataVinesh">GitHub</a> ·
  <a href="https://www.linkedin.com/in/venkat-vinesh">LinkedIn</a><br>
  <a href="mailto:venkata-vinesh-kumar-reddy.atluri@etu.ec-lyon.fr">venkata-vinesh-kumar-reddy.atluri@etu.ec-lyon.fr</a> ·
  <a href="mailto:venkatvinesh46@gmail.com">venkatvinesh46@gmail.com</a>
</p>

---

CS undergrad at **Mahindra University** (CGPA 7.96), now at **École Centrale de Lyon** in Écully
on the **Lyon Centrale Digital Lab 2026-2027** programme. Seeking a compulsory 6-month
**ML / Deep Learning** internship, **March to August 2027**. Open to Switzerland, Germany, the
Netherlands, Sweden and France. University internship agreement provided.

My work clusters around one theme: **modelling sequential, noisy real-world data** — forecasting
it, optimizing decisions on top of it, and learning policies that act on it. I care about the
math being right, not just the code running — and about **not overclaiming**. If a number can't
be traced back to real data, it doesn't ship.

---

### Selected work

**[Veltrix](https://github.com/VenkataVinesh/Veltrix)** — Market Analytics and Forecasting Terminal
An analytics terminal built so every call can be audited: each recommendation exposes the indicator
votes and weights behind it. Forecast intervals are measured rather than tuned — GARCH(1,1) delivers
94.75% coverage against a 95% nominal band, up from 91.67% under EWMA. Directional accuracy is
reported at 50.2% over 1,500 walk-forward calls, which is a coin flip, and the terminal says so.
`TypeScript` · `Next.js` · `Supabase` · `lightweight-charts`

**[TriageMate](https://github.com/DaPres/SwissAiWeeks_Team_8)** — Hackathon project, Swiss {ai} Weeks Zurich 2026
A triage co-pilot for operational service desks, built for the Swiss Life challenge at the Swiss
{ai} Weeks Zurich Hackathon. It screens an incoming ticket or email for PII and prompt injection,
classifies and routes it, assigns a priority with a written reason, retrieves similar past cases,
and drafts a response an analyst can approve, edit or reject.
- Found the 20,000-ticket dataset was only 173 unique descriptions with effectively random priority labels: a trained classifier did no better than always guessing the majority class
- Computed priority with an explicit ITIL urgency × impact matrix instead, and used the tickets as a retrieval library rather than training data
- Used the LLM only where judgment was genuinely needed, keeping the pipeline testable
- Built the classification/retrieval logic and the LLM prompting and pipeline
`Python` · `FastAPI` · `React` · `TypeScript` · `Azure AI Foundry` · `SQLite` · `Docker` · `Azure Container Apps`

**[Asset Price Prediction Platform](https://github.com/VenkataVinesh/Asset-Price-Prediction-Platform)** — Sequence Models vs Classical Baselines
Puts a deep sequence model and a classical baseline on the same series so the trade-off is
visible rather than assumed. Index-aligned windowing to prevent leakage; scaler state persisted
with the model so inference reproduces training-time normalization. An async FastAPI service
serves multi-step forecasts with confidence intervals.
`Python` · `PyTorch` · `Statsmodels` · `FastAPI` · `React`

**[Reinforcement Learning Lab](https://github.com/VenkataVinesh/Reinforcement-Learning-Lab)** — Tabular RL from scratch
Q-Learning and SARSA with the temporal-difference updates written by hand in NumPy on a custom
Gym-style GridWorld. Epsilon-greedy exploration decays from 1.0 to 0.05. Built to understand on-policy vs off-policy
properly, not to call a library.
`Python` · `NumPy` · `Matplotlib`

**[Portfolio Optimization](https://github.com/VenkataVinesh/Portfolio-Optimization-Dashboard)** — Markowitz mean-variance
Maximum-Sharpe weights via SciPy SLSQP under long-only constraints, tracing the efficient
frontier from the covariance structure of returns.
`Python` · `SciPy` · `NumPy` · `Matplotlib`

**[Weather Time-Series Forecasting](https://github.com/VenkataVinesh/Weather-Time-Series-Forecasting)** — Deep Learning, Sequence Models
Stacked two-layer LSTM (64 units, dropout 0.2) benchmarked against ARIMA/SARIMA, with trend/seasonality/residual
decomposition. Runs on a reproducible synthetic series — no dataset download needed.
`Python` · `PyTorch` · `Statsmodels` · `Matplotlib`

---

### Next up

In progress: an EU AI Act / GDPR RAG assistant built around an evaluation harness (retrieval
quality, faithfulness, hallucination rate).

---

### Skills

- **Languages:** Python, C++, SQL, TypeScript, MATLAB
- **ML / DL:** PyTorch, Scikit-Learn, LSTM / GRU, Statsmodels
- **Familiar with:** TensorFlow, Keras.
- **Data:** NumPy, Pandas, Matplotlib, time-series
- **Systems:** FastAPI, Next.js, React, Supabase, PostgreSQL, Docker, Git

### Languages spoken

English (fluent) · Telugu (native) · Hindi (conversational) · French (A1, in progress)
