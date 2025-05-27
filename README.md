# An Innovative Approach to Short-Term Load Forecasting Using Sequential Modeling and Advanced Feature Engineering

This repository contains code, datasets, and the full research paper for a study on short-term load forecasting using sequential deep learning models and advanced feature engineering.

## Project Overview

Short-term load forecasting (STLF) is essential for efficient and reliable power system operations. This project replicates and extends the DeepDeFF framework, evaluating multiple sequential deep learning models—including RNN, LSTM, GRU and their bidirectional variants—with feature fusion techniques.

Models are evaluated on three real-world electricity consumption datasets:
- **ERCOT:** Texas electricity load data for 2019.
- **PRECON:** Pakistan residential electricity consumption data.
- **RTE:** French national electricity demand data.

Forecasting is performed for 2, 6, and 12 timestep horizons, covering short-, medium-, and long-term predictions.

## Repository Contents

| File                                                         | Description                                  |
|--------------------------------------------------------------|----------------------------------------------|
| `Anomaly_detection_in_load_forecasting_using_ARIMA_and_Autoencoder copy.pdf` | Full research paper titled "An Innovative Approach to Short-Term Load Forecasting Using Sequential Modeling and Advanced Feature Engineering" |
| `ercot_1.ipynb`                                              | Jupyter notebook for ERCOT dataset           |
| `precon_1.ipynb`                                             | Jupyter notebook for PRECON dataset          |
| `rte_1.ipynb`                                                | Jupyter notebook for RTE dataset              |
| `ercot_2019_dataset.csv`                                     | ERCOT hourly load data for 2019               |
| `precon_dataset.csv`                                         | PRECON minute-level residential data          |
| `rte_dataset.csv`                                            | RTE original data                             |
| `resampled_rte_dataset.csv`                                  | RTE data resampled to hourly intervals        |

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
