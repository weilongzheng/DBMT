# DBMT
Dynamic Bayesian Multi Taper Estimation algorithms 
This repository contains implementations of the algorithms developed in Dynamic Bayesian Multi Taper estimation paradigm.
Contents:
  1. Main.m: Master script.
  2. TSpectrogram: genrates single taper sSpectrogram estimates.
  2. MTSpectrogram: genrates overlapped multi taper spectrogram estimates.
  3. DBMTSpectrogram: genrates DBMT estimates.
  4. log_DBMTSpectrogram: genrates log_DBMT estimates.
  5. DBMT_EM: EM step for DBMT algorithm.
  6. log_DBMT_EM: EM step for log-DBMT algorithm.
  7. Window_then_Taper: Segments the data and then multiplyes by taper (Used in DBMTSpectrogram).
