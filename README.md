# Ford Car Price Prediction

Ford Car Price Prediction - Jupyter notebook implementing a Python workflow (pandas, scikit-learn Linear Regression, seaborn, matplotlib) to explore data and predict used Ford prices from features like `year`, `mileage`, `engineSize`, `tax`, `mpg`, `model`, `transmission`, `fuelType`.

## Contents
- `model.ipynb` - notebook with EDA, preprocessing, and modeling
- `Dataset/ford.csv` - dataset used for training (included)
- `requirements.txt` - Python dependencies
- `.gitignore`, `.gitattributes` - repository configuration

## Setup
1. Create a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open `model.ipynb` in Jupyter or VS Code and run the cells.

## Notes
- The `Dataset/` folder is tracked; if you prefer to keep large data out of Git, remove it from the repo and add it to `.gitignore`.
- A basic GitHub Actions workflow is included at `.github/workflows/python-app.yml` to validate imports on push.

## License
This repository uses the MIT License. See `LICENSE` for details.
