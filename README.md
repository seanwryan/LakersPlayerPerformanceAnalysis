# Lakers Performance Analysis

## Overview
This project aims to analyze the performance of the Los Angeles Lakers during the 2023 regular season and playoffs. We focus on key metrics including Player Efficiency Rating (PER), True Shooting Percentage (TS%), Total Rebound Percentage (TRB%), Assist Percentage (AST%), and Usage Percentage (USG%). The analysis helps identify top contributors, compare regular season and playoff performances, and provides actionable insights for improvement.

## Data Source
The data used in this project is sourced from Basketball Reference. We have included both regular season and playoff statistics for the Los Angeles Lakers and other successful NBA teams in 2023.

## Project Structure
The project is structured as follows:

- `data/`: Contains the CSV files with regular season and playoff statistics.
- `notebooks/`: Jupyter notebooks used for data cleaning, analysis, and visualization.
- `output/`: Output files, including plots and comparison tables.
- `README.md`: Project overview and instructions.
- `LICENSE`: License information.

## Key Metrics Analyzed
- **Player Efficiency Rating (PER)**
- **True Shooting Percentage (TS%)**
- **Total Rebound Percentage (TRB%)**
- **Assist Percentage (AST%)**
- **Usage Percentage (USG%)**

## Analysis Steps
1. **Data Loading and Cleaning**: Load data from CSV files and clean it by removing unnecessary columns and filling missing values.
2. **Key Metrics Calculation**: Calculate average metrics for each team's regular season and playoff data.
3. **Top Contributors Identification**: Identify top contributors based on PER.
4. **Performance Comparison**: Compare regular season and playoff performances for the Lakers.
5. **Contextualizing Contributions**: Identify players with decreased performance in key areas during the playoffs and provide actionable insights.

## Usage
To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/lakers-performance-analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd lakers-performance-analysis
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook:
    ```bash
    jupyter notebook notebooks/analysis.ipynb
    ```

## Citing Basketball Reference
When using data from Basketball Reference, please cite it as follows:
> Data provided by Basketball Reference, a website that provides comprehensive basketball statistics. Available at: https://www.basketball-reference.com/

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements
We thank Basketball Reference for providing the data used in this analysis. We also acknowledge the contributions of all project members.

## Contributing
We welcome contributions to enhance this project. Please feel free to submit a pull request or open an issue on GitHub.
