<h1 align="center">Venkata Vinesh Kumar Reddy Atluri</h1>

<p align="center">
  <b>Machine Learning Engineer</b> — time-series forecasting, optimization, and reinforcement learning.<br>
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
on the **Lyon Centrale Digital Lab 2026-2027** programme, looking for a six-month
**ML / Deep Learning** internship in France from **February 2027**.

My work clusters around one theme: **modelling sequential, noisy real-world data** — forecasting
it, optimizing decisions on top of it, and learning policies that act on it. I care about the
math being right, not just the code running — and about **not overclaiming**. If a number can't
be traced back to real data, it doesn't ship.

---

### Selected work

**[Veltrix](https://github.com/VenkataVinesh/Veltrix)** — Market Analytics and Forecasting Terminal
An analytics terminal built so every call can be audited: each recommendation exposes the indicator
votes and weights behind it. Forecast intervals are measured rather than tuned — GARCH(1,1) delivers
94.75% coverage against a 95% nominal band, up from 91.7% under EWMA. Directional accuracy is
reported at 50.2% over 1,500 walk-forward calls, which is a coin flip, and the terminal says so.
`TypeScript` · `Next.js` · `Supabase` · `lightweight-charts`

**[Asset Price Prediction Platform](https://github.com/VenkataVinesh/Asset-Price-Prediction-Platform)** — LSTM vs ARIMA, head to head
Puts a deep sequence model and a classical baseline on the same series so the trade-off is
visible rather than assumed. Index-aligned windowing to prevent leakage; scaler state persisted
with the model so inference reproduces training-time normalization.
`Python` · `PyTorch` · `Statsmodels` · `FastAPI` · `React`

**[Weather Time-Series Forecasting](https://github.com/VenkataVinesh/Weather-Time-Series-Forecasting)** — Sequence models on seasonal data
Stacked 2-layer LSTM benchmarked against ARIMA/SARIMA, with trend/seasonality/residual
decomposition. Runs on a reproducible synthetic series — no dataset download needed.
`Python` · `PyTorch` · `Statsmodels` · `Matplotlib`

**[Reinforcement Learning Lab](https://github.com/VenkataVinesh/Reinforcement-Learning-Lab)** — Tabular RL from scratch
Q-Learning and SARSA with the temporal-difference updates written by hand in NumPy on a custom
Gym-style GridWorld. Built to understand on-policy vs off-policy properly, not to call a library.
`Python` · `NumPy` · `Matplotlib`

**[Portfolio Optimization](https://github.com/VenkataVinesh/Portfolio-Optimization-Dashboard)** — Markowitz mean-variance
Maximum-Sharpe weights via SciPy SLSQP under long-only constraints, tracing the efficient
frontier from the covariance structure of returns.
`Python` · `SciPy` · `NumPy` · `Matplotlib`

---

### Next up

- **EU AI Act / GDPR RAG assistant** — retrieval over regulatory text, built around an evaluation
  harness measuring hallucination rate and retrieval quality.
- **Industrial visual defect detection** — anomaly detection treated as a production service, with
  experiment tracking and drift monitoring.

*Planned, not started. Repositories appear here when there is code in them.*

---

<p align="center"><sub>
Python · PyTorch · TensorFlow · Scikit-Learn · Statsmodels · NumPy/Pandas ·
FastAPI · Next.js · TypeScript · PostgreSQL · Docker · Git
</sub></p>
