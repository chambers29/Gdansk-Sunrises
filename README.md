# Gdansk-Sunrises
Sunrise, civil and nautical twilight start times for Gdansk in 2025 based on public API data

## Project files
- `sunrises_datadownload.ipynb` – notebook for downloading data from the API
- `sunrises_2025.csv` – saved dataset with all dates and times  
- `sunrises.ipynb` – notebook for generating the final plot  
- `sunrises.png` – final chart

## Visualization
![Sunrise, civil, nautical twilights](sunrises.png)

## Technologies
- Python 3.12
- pandas
- matplotlib
- Jupyter Notebook

## How to run

### 1. Install required packages
```bash
pip install -r requirements.txt
```
### 2. Run the and visualization notebook
```bash
jupyter notebook sunrises.ipynb
```
### Note
The dataset sunrises_2025.csv is already included in this repository. If you want to generate a dataset from the API by yourself, run the sunrises_datadownload.ipynb notebook first.
```bash
jupyter notebook sunrises_datadownload.ipynb
```
