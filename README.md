# surface_tension

This repo comprises an exploration of a vol surface model, completed during my free time in 2026.

I started from the Black-Sholes assumptions and reconstructred the entire volatility surface from market option prices. Once I observed the volatility 'smile', I implemented a Heston stochastic volatility model and calibrated it to marked data.

surface-tension/
│
├── data/
│   └── options_loader.py
├── models/
│   ├── black_scholes.py
│   └── heston.py
├── calibration/
│   └── calibrate.py
├── visualisation/
│   └── vol_surface.py
├── notebooks/
│   └── walkthrough.ipynb
└── README.md
