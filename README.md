# COVID-19-Global-Data-Tracker


This project analyzes COVID-19 trends globally, focusing on cases, deaths, and vaccinations in **South Africa**, **United States**, and **China**.

## Objectives

- Explore trends in COVID-19 cases, deaths, and vaccinations
- Clean and prepare real-world data
- Visualize key insights using Python

## Tools Used

| Tool | Purpose |
|------|---------|
| Python | Main programming language |
| Jupyter Notebook | For structured analysis |
| pandas | Data cleaning and manipulation |
| matplotlib / seaborn | Charts and graphs |
| plotly (optional) | Interactive choropleth map |
| GitHub | Version control and project sharing |

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YandaDev/library-management-api.git
   cd library-management-api
   ```
2. **Create & Activate a Virtual Environment**:
   ```bash
   python -m venv venv
   source .venv/Scripts/activate
   ```
3. **Install the required libraries**:

    ```bash
    pip install pandas matplotlib seaborn plotly
    ```
4. Download the dataset from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv) 

5. Open the notebook: `covid_tracker.ipynb`in Jupyter Notebook (or VS Code with Jupyter extension)

4. Run each cell in order.


### Key Insights

- **The United States** had the highest number of total cases and deaths.
- **South Africa**’s death rate was higher during early waves compared to **China**.
- **China** shows slower case growth, possibly due to strict containment.
- Vaccination progress varied, with the **United States** leading early in rollout.
