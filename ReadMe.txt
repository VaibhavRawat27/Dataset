# README – ISS Real-Time Tracker (10s Interval Dataset)

## Title
ISS Real-Time Tracker – 10s Interval Dataset
Detailed Tracking of the International Space Station’s (ISS) Orbit on June 7, 2025

## Dataset Overview
This dataset provides high-resolution real-time tracking logs of the International Space Station (ISS), recorded at 10-second intervals for a continuous 24-hour period on June 7, 2025. The data captures the ISS’s geospatial position and orbital motion, enriched with hemisphere and regional geolocation context for better interpretability.

It is ideal for:
- Space Science & Orbital Mechanics – analyzing orbital paths and speed variations
- Geospatial Visualization – plotting ISS trajectories on maps or 3D Earth models
- Educational Purposes – teaching satellite motion and real-time tracking
- Data Science Projects – time-series analysis, clustering, and anomaly detection

## Key Highlights
✔ 8,641 records (10-second intervals for 24 hours)
✔ Latitude, longitude, altitude, speed, hemisphere, and region included
✔ Covers approximately 16 complete ISS orbits (each ~90 minutes)
✔ Geolocation enrichment: region/ocean name beneath the ISS
✔ Released under CC0 (Public Domain) – free for any use

## File Description
### iss_data.csv
| Column Name      | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| timestamp         | UTC timestamp (`YYYY-MM-DDTHH:MM:SSZ`) representing the exact capture time. |
| latitude          | Latitude in decimal degrees (-90 to +90). Negative = Southern Hemisphere.  |
| longitude         | Longitude in decimal degrees (-180 to +180). Negative = West.              |
| altitude_km       | ISS altitude in kilometers above Earth’s surface.                          |
| speed_kmph        | Orbital speed in kilometers per hour.                                      |
| Hemisphere        | Northern or Southern, based on latitude.                                   |
| region            | Geographical area or ocean below the ISS at that moment.                   |

## Sample Data (First 3 Records)
| timestamp           | latitude     | longitude     | altitude_km | speed_kmph | Hemisphere | region        |
|----------------------|--------------|---------------|-------------|------------|------------|---------------|
| 2025-06-07T00:00:00Z | -10.45905964 | 133.05146841  | 368.18      | 27687.89   | Southern   | Pacific Ocean |
| 2025-06-07T00:00:10Z | -9.94882725  | 133.42790939  | 368.06      | 27688.23   | Southern   | Pacific Ocean |
| 2025-06-07T00:00:20Z | -9.43804552  | 133.80306774  | 367.94      | 27688.50   | Southern   | Pacific Ocean |

## Suggested Citation
If you use this dataset, please cite it as:

Rawat, V. (2025). ISS Real-Time Tracker – 10s Interval Dataset (June 7, 2025) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.16266649

## License
CC0 1.0 – Public Domain
You may copy, modify, distribute, and use the data for any purpose, even commercially, without asking permission.

## Acknowledgements
The dataset is based on publicly available ISS tracking sources and processed for educational and research purposes.

## Recommended Usage
1. Visualization – Plot latitude & longitude on a world map or 3D Earth.
2. Orbital Analysis – Calculate orbit periods and altitude variations.
3. Machine Learning – Train models to predict future ISS positions.

## Find Dataset here
1. Kaggle: https://www.kaggle.com/datasets/vaibhavrawat277/iss-real-time-tracker-10s-interval-dataset
2. ResearchGate: https://www.researchgate.net/publication/393861852_ISS_Real-Time_Tracker_10s_Interval_Dataset
3. Zenodo: https://zenodo.org/records/16266649