# Business Intelligence and Analytics Lab Work

A collection of practical Business Intelligence and Analytics experiments completed with
Python notebooks and Tableau. The work uses real-world-style datasets to demonstrate data
cleaning, exploration, visualization, statistical analysis, machine learning, forecasting,
and business decision-making.

## Experiments

| Experiment | Focus |
| --- | --- |
| [EXP1](./EXP1/) | Tableau-based business data visualization and dashboarding |
| [EXP2](./EXP2/) | Cleaning and exploratory analysis of Superstore orders |
| [EXP3](./EXP3/) | Airline tweet sentiment analysis and comparison with VADER sentiment |
| [EXP4](./EXP4/) | Customer/order segmentation using K-Means clustering |
| [EXP5](./EXP5/) | Market basket analysis with Apriori association rules |
| [EXP6](./EXP6/) | Superstore sales prediction with linear regression |
| [EXP7](./EXP7/) | Monthly sales forecasting with Holt-Winters exponential smoothing |
| [EXP8](./EXP8/) | Detecting unusual orders with Isolation Forest |
| [EXP9](./EXP9/) | Customer Lifetime Value (CLV) analysis and customer tiering |
| [EXP10](./EXP10/) | A/B testing of advertisement and public service announcement conversion rates |

## Tools and techniques

- **Python:** pandas, NumPy, Matplotlib, and Seaborn
- **Machine learning:** scikit-learn
- **Statistics and forecasting:** SciPy and Statsmodels
- **Association mining:** mlxtend
- **Business visualization:** Tableau
- **Notebook environment:** Jupyter Notebook

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/aryanguptacsvtu/BIA-LabWork.git
cd BIA-LabWork
```

### 2. Create an environment

```bash
python -m venv .venv
```

Activate it:

**Windows PowerShell**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS/Linux**

```bash
source .venv/bin/activate
```

### 3. Install the dependencies

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn scipy statsmodels mlxtend nltk openpyxl
```

### 4. Run a notebook

Start Jupyter from the repository root:

```bash
jupyter notebook
```

Then open the `Code.ipynb` file inside the experiment you want to explore. Run each
notebook from its own experiment folder so relative dataset paths such as
`superstore_orders.csv` resolve correctly.

## Repository structure

```text
BIA-LabWork/
├── EXP1/                    # Tableau visualization
├── EXP2/                    # Data cleaning and EDA
├── EXP3/                    # Sentiment analysis
├── EXP4/                    # K-Means clustering
├── EXP5/                    # Association rule mining
├── EXP6/                    # Linear regression
├── EXP7/                    # Time-series forecasting
├── EXP8/                    # Anomaly detection
├── EXP9/                    # Customer lifetime value
├── EXP10/                   # A/B testing
└── README.md
```

## Notes

- The notebooks are self-contained demonstrations; outputs may vary slightly with library
  versions.
- Some notebooks reuse the Superstore orders dataset for different analytical objectives.
- `EXP1` requires Tableau to open and edit the `.twb` workbook.
- If a notebook contains a machine-specific file path, replace it with the corresponding
  dataset path in this repository before running it.
