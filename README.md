# Uber Supply-Demand Gap Analysis

This project explores and analyzes Uber ride request data to understand patterns in ride requests and identify key issues around supply-demand mismatch. The aim is to gain insights into why some ride requests are not fulfilled and propose data-driven solutions.

##  Dataset

- **File**: `Uber Request Data.csv`
- **Description**: This dataset contains Uber ride request data including:
  - Request and drop timestamps
  - Pickup points (airport or city)
  - Status of the ride (`Trip Completed`, `Cancelled`, `No Cars Available`)
  - Driver ID and request ID

##  Notebook

- **File**: `uber_supply_demand_gap_analysis.ipynb`
- **What it does**:
  - Loads and cleans the data
  - Performs exploratory data analysis (EDA)
  - Visualizes trends in requests by time and location
  - Identifies peak hours and service availability
  - Highlights the demand-supply gap and reasons behind unfulfilled requests

##  Key Insights

- High number of cancellations and "No Cars Available" statuses during peak hours.
- Airport pickup point faces a major shortage of cars, especially during early morning hours.
- City pickup point sees more cancellations, often during evening hours.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/snehakp1/uber-demand-supply-gap-analysis.git
   cd uber-demand-supply-gap-analysis
