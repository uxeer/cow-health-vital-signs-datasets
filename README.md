
# Cow Health Vital Signs Datasets

This repository contains synthetic datasets of vital signs (temperature, SpO2, and BPM) for adult female cows under different health conditions. These records are generated for use in machine learning, veterinary monitoring systems, or smart farming analytics.

## Datasets Overview

The following datasets are included, each with **22,000 unique records**:

- **pregnancy.csv**: Vital signs during pregnancy.
- **hunger.csv**: Vital signs when the cow is hungry or starving.
- **fever.csv**: Vital signs during fever.
- **salmonellosis.csv**: Vital signs when affected by salmonellosis.

Each record includes the following fields:
- **timestamp**: The timestamp of the record.
- **temperature**: The cow's body temperature (°C).
- **spo2**: The cow's blood oxygen saturation level (SpO2).
- **bpm**: The cow's heart rate (beats per minute).
- **condition**: The health condition of the cow (e.g., pregnancy, hunger, fever, salmonellosis).

## Purpose

These datasets simulate realistic health condition scenarios for cows and are useful for:
- **Machine Learning**: Training models to predict cow health states based on vital signs.
- **Veterinary Monitoring**: Analyzing trends and anomalies in cow health.
- **Smart Farming**: Integrating with IoT systems to monitor and manage livestock health in real-time.

## Data Generation

The records are randomly generated within specified ranges for each health condition:
- **Pregnancy**: Temperature: 38.5°C - 39.5°C, SpO2: 93% - 98%, BPM: 65 - 85
- **Hunger/Starvation**: Temperature: 37.8°C - 38.5°C, SpO2: 88% - 94%, BPM: 80 - 95
- **Fever**: Temperature: 40.0°C - 41.5°C, SpO2: 88% - 93%, BPM: 90 - 110
- **Salmonellosis**: Temperature: 39.0°C - 41.0°C, SpO2: 85% - 92%, BPM: 100 - 120

## How to Use

1. Clone or download this repository.
2. Access the CSV files in the `data` directory:
   - `pregnancy.csv`
   - `hunger.csv`
   - `fever.csv`
   - `salmonellosis.csv`
3. Use these files for analysis, training models, or testing algorithms related to livestock health management.

## Example of Record Structure

Each CSV file follows this structure:

| timestamp            | temperature | spo2 | bpm | condition   |
|----------------------|-------------|------|-----|-------------|
| 2025-04-19 12:00:00  | 38.7        | 95.5 | 72  | pregnancy   |
| 2025-04-19 12:01:00  | 38.6        | 94.3 | 74  | pregnancy   |
| ...                  | ...         | ...  | ... | ...         |

## License

This repository and data are provided under the MIT License. Feel free to use, modify, and share the data as needed.
