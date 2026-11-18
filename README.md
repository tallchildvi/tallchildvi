### Hi, I'm Andrii Levashov

3rd-year **Software Engineering** student at **Taras Shevchenko National University of Kyiv** (Faculty of Computer Science and Cybernetics), currently focusing on **GeoAI, Multi-Sensor Earth Observation, and Self-Supervised Learning**.

I enjoy building end-to-end machine learning pipelines where software engineering rigour meets scientific validation — particularly avoiding target leakage, designing proper spatial cross-validation, and testing learned models against domain baselines.

- **Current focus:** Multi-sensor remote sensing (`Sentinel-1 SAR` + `Sentinel-2`), contrastive representation learning, and reproducible data pipelines
- **Also:** Participant at *EPAM Systems (Data Science for Engineering Practice)* & Deputy Head of Science Department at KNU FCSC Student Parliament
- **Contact:** [levashovandrii@gmail.com](mailto:levashovandrii@gmail.com)

---

### Featured Projects

| Project | Focus & Highlights | Links |
| :--- | :--- | :--- |
| **PreemptFire** | Next-day wildfire ignition risk forecasting across Iberia (3,186 scene-dates, 2017–2025). Co-registered 22-channel 100 m scenes (`Sentinel-1/2`, `DEM`, `OSM`, `ERA5-Land`) with decoupled `NASA FIRMS VIIRS` labels; `0.77` vs. `0.71` persistence ROC-AUC under 25-block spatial CV. | [GitHub](https://github.com/tallchildvi/PreemptFire) · [Zenodo DOI](https://doi.org/10.5281/zenodo.24061983) · [Kaggle](https://www.kaggle.com/datasets/hollyfrogvi/wildfire-iberia-100m) · [Live Demo](https://huggingface.co/spaces/tallchildvi/PreemptFire) |
| **Spotify-SimCLR** | *Team course project (ML lead, team of 3).* Adapted SimCLR contrastive learning to tabular audio features; resolved representation collapse via feature masking, Gaussian noise augmentations, and NT-Xent temperature tuning. | [GitHub](https://github.com/tallchildvi/Music-Embed-SSL) |
| **FocusFlow-CV** | Real-time attention monitoring using MediaPipe Face Mesh (468 facial landmarks), gaze vector estimation, and a lightweight CPU-optimized SVM classifier. | [GitHub](https://github.com/tallchildvi/FocusFlow-CV) |
| **Spell** | Modular C# / .NET NLP CLI engine featuring hybrid intent classification, confidence-based entity extraction, and automated unit tests under SOLID principles. | [GitHub](https://github.com/tallchildvi/spell) |

---

### Technical Stack

- **ML & Deep Learning:** Python, PyTorch, scikit-learn, CatBoost, Self-Supervised (Contrastive) Learning, Time-Series Models (GRU)
- **Geospatial & Data:** GDAL, Rasterio, Sentinel-1/2, Copernicus DEM, ERA5-Land, NASA FIRMS, pandas, NumPy, SciPy
- **Engineering & Tools:** C# / .NET, GitHub Actions (CI/CD), Unit Testing, OpenCV, MediaPipe, Gradio, Hugging Face Spaces
