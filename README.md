# Bird-Sightings-Nova-Scotia



## Overview
This project focuses on predicting bird species observed in Halifax County, Nova Scotia, using historical observation data. The model uses geographic coordinates and environmental features, such as weather data, to estimate which species are likely to be seen. The analysis supports biodiversity monitoring, conservation planning, and citizen science efforts.

## Files in this Repository
- `bird_sightings.ipynb` – Jupyter Notebook with data processing, visualization, and machine learning model training.
- `nova_scotia.geojson` – GeoJSON file with Nova Scotia boundaries for mapping bird observations.
- `data_bird.csv` – CSV file containing bird observations, including species, coordinates, and dates.
- `written_responses.pdf` – Written answers to project questions 1–3, including problem definition, approach, and reflections.

## Key Features
- Filters bird observations to Halifax County for now.
- Uses top 50 most observed species for ML modeling.
- Integrates historical weather data (temperature, precipitation, wind speed).
- Predicts bird species (`common_name`) using a Random Forest classifier.
- Includes reflections and future improvements for scaling the model to all of Nova Scotia and Canada.

## Future Work
- Expand to a 9 × 9 grid covering all of Nova Scotia.
- Include additional weather features such as wind direction, visibility, and migration patterns.
- Incorporate environmental variables like elevation, forest cover, and coastal proximity.
- Improve prediction accuracy from ~40% to at least 70%.
- Scale predictions to the Atlantic Provinces and eventually all of Canada.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Bird-Sightings-Nova-Scotia.git
