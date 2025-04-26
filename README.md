🌿 OEMC Hackathon - Global FAPAR Modeling
This repository contains the complete solution and research pipeline for the OEMC Hackathon challenge focused on global modeling of FAPAR (Fraction of Absorbed Photosynthetically Active Radiation). 
FAPAR is a crucial biophysical parameter that quantifies the portion of incoming solar radiation absorbed by vegetation for photosynthesis. 
It plays a central role in monitoring ecosystem productivity, modeling carbon cycles, evaluating agricultural health, and supporting climate change mitigation strategies.

The goal of this project is to develop robust machine learning and data-driven models that can accurately predict FAPAR values across various geographic and climatic regions using remote sensing data, environmental variables, and geospatial context. 
The challenge aims to improve global vegetation monitoring using accessible and scalable techniques.

🌍 Project Objectives
Develop accurate and scalable models to estimate FAPAR globally.

Leverage Earth Observation data, such as satellite reflectance and vegetation indices.

Integrate temporal and spatial context using advanced modeling techniques.

Support environmental decision-making, land management, and climate research.

📦 Key Features
✅ End-to-End ML Pipeline: From raw satellite data to final model predictions.

🛰️ Remote Sensing Data Processing: Feature extraction from Sentinel, MODIS, and other EO sources.

🌾 Vegetation Index Integration: Use of NDVI, EVI, and other indices to enhance FAPAR estimation.

🧠 Machine Learning Models: Includes traditional ML models (e.g., LightGBM, XGBoost) and deep learning approaches (e.g., CNNs, LSTMs, Transformers).

🌐 Spatial & Temporal Awareness: Incorporation of geolocation, seasonality, and time-series signals.

📈 Evaluation & Metrics: RMSE, MAE, R² used to benchmark performance across regions and seasons.

📊 Visualization & Insights: Plotting FAPAR trends, predictions, and spatial distributions.

🗂️ Data Sources
Satellite Imagery (e.g., Sentinel-2, MODIS)

Vegetation Indices (NDVI, EVI, LAI)

Environmental Data (temperature, precipitation, humidity)

Ground Truth Measurements (when available for model validation)

Geospatial Data (land cover, topography, region labels)

🛠️ Tech Stack
Python 3.x

pandas, numpy, geopandas, xarray, rasterio

scikit-learn, LightGBM, CatBoost, XGBoost

TensorFlow / PyTorch for deep learning

Matplotlib, Seaborn, Plotly for visualizations

SHAP, LIME for explainable machine learning

QGIS, Google Earth Engine (for geospatial processing, optional)

🚀 Use Cases
Precision Agriculture: Optimize irrigation, monitor crop growth and yield.

Climate Change Research: Track vegetation productivity and carbon sinks over time.

Land Use Management: Monitor deforestation, urban expansion, and ecosystem health.

Environmental Policy: Provide reliable data for government and NGO reporting tools.

🔮 Future Work
Integrate near real-time data feeds for continuous monitoring.

Expand modeling to include multi-source sensor fusion (e.g., radar + optical).

Develop global FAPAR anomaly detection for drought and disaster early warning systems.

Create an interactive web dashboard to visualize predicted FAPAR maps.
