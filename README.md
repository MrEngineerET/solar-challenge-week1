# Solar Data Discovery

## Overview
Cross-country solar farm analysis for MoonLight Energy Solutions, analyzing environmental measurement data from Benin, Sierra Leone, and Togo to identify high-potential regions for solar installation.

## Business Objective
Perform quick analysis of environmental measurements and translate observations into a strategy report focusing on identifying key trends and valuable insights that support data-driven recommendations for solar investments aligned with long-term sustainability goals.

## Dataset
The data includes measurements for:
- Solar radiation (GHI, DNI, DHI)
- Temperature and humidity
- Wind conditions
- Sensor readings (ModA, ModB)
- Cleaning events

## Setup

### Environment
```bash
# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Project Structure
```
├── data/                 # Solar radiation datasets
├── notebooks/           # Jupyter notebooks for analysis
├── tests/              # Unit tests
└── requirements.txt    # Python dependencies
```

