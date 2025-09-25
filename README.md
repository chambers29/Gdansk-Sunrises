# Gdansk-Sunrises
Sunrise, civil and nautical twilight start times for Gdansk in 2025 based on public API data

## Project files
- `sunrises_datadownload.ipynb` – notebook for downloading data from the API  
- `sunrises.ipynb` – notebook for generating the final plot  
- `sunrises_2025.csv` – saved dataset with all dates and times  
- `sunrises.png` – final chart

## Visualization
![Sunrise, civil, nautical twilights](sunrises.png)

## Technologies
- Python 3.12
- pandas
- matplotlib
- Jupyter Notebook

## How to run
```bash
pip install -r requirements.txt
jupyter notebook plot_twilight.ipynb
