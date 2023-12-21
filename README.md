# Air Quality Data ☁☁

## Setup environment
```
pipenv install
pipenv shell
pip install numpy pandas matplotlib streamlit
```

## Download beijing_climateData.csv

in **notebook.ipynb** run:
```
all_df.to_csv('./dashboard/newbeijing_climateData.csv', index= False)
```
## Run steamlit app

in terminal run:
```
streamlit run .\dashboard\dashboard.py
```

## Dashboard Result

https://air-quality-dataset-2-artsam.streamlit.app/
