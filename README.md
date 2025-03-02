# DSC640_final_project

## Data

The data used in this project is sourced from the National Database of Childcare Prices. The dataset includes information on childcare costs across different states and counties in the U.S. from various years.

## Notebooks

### [src/Schincke_final_project_EDA.ipynb](src/Schincke_final_project_EDA.ipynb)

This Jupyter notebook contains the exploratory data analysis (EDA) and visualizations for the project. Key sections include:

- **Data Import and Cleaning**: Reads and cleans the data from `data/nationaldatabaseofchildcareprices.xlsx`.
- **Exploration of Childcare Costs**: Analyzes how childcare costs have changed over time across different states and counties.
- **Economic and Labor Trends**: Examines trends in income, unemployment, and labor force participation.
- **Impact on Demographics**: Investigates the impact of high childcare costs on various demographics.
- **Relationships with Race**: Explores the relationships between childcare costs and racial demographics.

## Visualizations

The project includes various visualizations to illustrate the findings:

- **Bar Plot**: Median Household Income (MHI) by State.
- **Heatmap**: Correlation between Unemployment, Poverty Rates, Income, and Population.
- **Scatter Plot Matrix**: Economic and Labor Trends.
- **Bar Plot**: Sum of Race Counts.

## Final Materials

The `Final Materials` folder contains the final deliverables for the project, including:

- **Childcare Cost Analysis.twbx**: Tableau workbook with interactive visualizations.
- **schincke_final_project_childcare_costs_v3.pdf**: Final project report.
- **Schincke_final_project_EDA.ipynb**: Jupyter notebook with EDA.
- **Schincke_final_project_tableau_dashboard_export.pptx**: PowerPoint presentation with Tableau dashboard export.
- **Schincke_final_project_v5.docx.pdf**: Final project write-up.
- **The rising cost of childcare in the U.S.-2.pdf**: Additional report on childcare costs.

## How to Run

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd DSC640_final_project
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:
    ```sh
    jupyter notebook src/Schincke_final_project_EDA.ipynb
    ```

## Conclusion

This project provides a comprehensive analysis of childcare costs in the U.S. and their impact on various economic and demographic factors. The findings can help inform policy decisions and provide insights into the challenges faced by families in affording childcare.

## Author

Dexter Schincke

## License

This project is licensed under the MIT License.
