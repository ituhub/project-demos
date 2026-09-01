# 🎬 Project Demos

Video walkthroughs of my production AI/ML platforms — built solo, end-to-end.

---

## MarketLensPro

**Production SaaS Trading Analytics Platform**

🔗 [Live Platform](https://marketlenspro.app) · 📂 [Source Code](https://github.com/ituhub/TradeAnalytics)

https://github.com/ituhub/project-demos/raw/main/MarketLensPro_project_demo.mp4

**What it does:**
- 8-model ML ensemble (Transformer, CNN-LSTM, TCN, Informer, N-BEATS, LSTM-GRU, XGBoost, Stacking) for trade signal generation across 19 financial instruments
- Signal quality gate with 5-filter validation: confidence band-pass, regime detection, momentum alignment, volatility check, multi-timeframe consensus
- Autonomous paper trading engine with dynamic position sizing, volatility-scaled stop-loss, and 3 graduated profit targets
- Historical analogue retrieval via vector similarity matching against resolved signal history
- RAG-powered AI chatbot for platform insights
- CI/CD via GitHub Actions, deployed on GCP Cloud Run

**Tech Stack:** Python · Dash/FastAPI · React · Firestore · GCS · Firebase Auth · Stripe · GCP Cloud Run

---

## EnergyLens

**Nordic Electricity Price Forecasting Platform**

📂 [Source Code](https://github.com/ituhub/EnergyLens)

https://github.com/ituhub/project-demos/raw/main/EnergyLens_project_demo.mp4

**What it does:**
- 7-model ensemble forecasting DK1 Nordic electricity spot prices with ~200 engineered features
- Ingests real-time data from Energi Data Service, Open-Meteo, and ENTSO-E across spot prices, weather, generation mix, wind/solar forecasts, and cross-border flows
- Forecast accountability system with rolling accuracy metrics, calibration analysis, and automated alerts
- Backtest engine for trading strategy evaluation (direction-follow and threshold strategies)
- Bitemporal timestamps for honest backtesting
- CI/CD via GitHub Actions, deployed on GCP Cloud Run (europe-north1)

**Tech Stack:** Python · FastAPI · React · PostgreSQL (Neon) · GCS · GCP Cloud Run





---

*Both platforms are designed, built, and maintained entirely by me — from data pipelines and ML training to frontend UI and cloud deployment.*
