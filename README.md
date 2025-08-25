# Logistics ETA Prediction

An intelligent logistics system that predicts Estimated Time of Arrival (ETA) for shipments using machine learning models.

## Overview

This project uses machine learning to provide accurate ETA predictions for logistics operations by analyzing historical shipping data, real-time traffic conditions and various other factors that impact delivery times.

## Features

- **Smart ETA Prediction**: Machine learning-powered delivery time estimation.
- **Traffic Analysis**: Incorporates traffic congestion data to improve ETA accuracy.
- **Distance Calculation** – Computes distances between pickup and drop-off points.
- **Time-based Features** – Considers hour, weekday, and month for rush-hour effects.
- **Weather Impact Analysis** – Adjusts predictions based on weather severity.
- **Driver Behavior Insights** – Uses driver behavior scores to enhance ETA predictions.

## Getting Started
Follow these instructions to set up the project environment and run the code on your local machine.

### Prerequisites

This project uses [uv](https://github.com/astral-sh/uv) for fast Python package management and environment handling. You'll need to install `uv` before proceeding.

#### Installing uv

##### On macOS and Linux:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

##### On Windows:
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

##### Alternative installation methods:
```bash
# Using pip
pip install uv

# Using pipx
pipx install uv

# Using Homebrew (macOS)
brew install uv

# Using conda/mamba
conda install -c conda-forge uv
```

### Setup And Installation

#### 1- Clone the Repository

#### 2- Sync Dependencies 

##### Sync the library dependencies:
```bash
uv sync
```

## Data Sources

https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset

