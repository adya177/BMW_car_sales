# BMW Car Sales Analysis

This repository contains the two Jupyter notebooks reconstructed from the supplied Colab PDF exports:

- `ML_Project_Demo.ipynb` compares Random Forest, Logistic Regression, SVM, KNN, and Gradient Boosting classifiers.
- `Analysis_Forecasting_BMW_Sales_Trends.ipynb` reproduces the Random Forest sales classification analysis shown in its export. Although the export title mentions forecasting, it contains no time-series forecasting code.

## Run the notebooks

The source CSV (`content.csv`) was not included in the notebook exports or this repository. Obtain the dataset used in the Colab notebooks, then upload or copy it into the repository root with the exact name `content.csv`.

Install the Python packages and start Jupyter:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Open either notebook and run its cells from top to bottom. To use Binder, click a launch link below, wait for the temporary JupyterLab session to start, upload `content.csv` through the file browser, and then run the notebook. Binder sessions are temporary, so uploaded data and generated outputs are cleared when the session ends.

[Launch the model comparison notebook on Binder](https://mybinder.org/v2/gh/adya177/BMW_car_sales/HEAD?labpath=ML_Project_Demo.ipynb)

[Launch the BMW sales analysis notebook on Binder](https://mybinder.org/v2/gh/adya177/BMW_car_sales/HEAD?labpath=Analysis_Forecasting_BMW_Sales_Trends.ipynb)

## Dataset columns

The exports show a 50,000-row CSV with these columns: `Model`, `Year`, `Region`, `Color`, `Fuel_Type`, `Transmission`, `Engine_Size_L`, `Mileage_KM`, `Price_USD`, `Sales_Volume`, and `Sales_Classification`.

The notebook PDFs are exports of executed Colab notebooks, not the original `.ipynb` source files. Notebook code and cell organization were reconstructed from the readable PDF content; saved cell outputs were not copied.
