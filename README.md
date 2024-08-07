
# NYC Public School Test Result Scores Analysis

This project explores and analyzes the test result scores of public schools in New York City. The analysis includes data cleaning, summary statistics, visualizations, and correlation analysis to understand the performance of schools across different boroughs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/xatren/ExploringNYCPublicSchoolTestResultScores
   ```
2. Navigate to the project directory:
   ```sh
   cd nyc-school-test-scores
   ```

## Usage

To start the analysis, open the Jupyter Notebook file in your preferred environment (e.g., Jupyter Notebook, JupyterLab, VSCode):

1. Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Open the `Exploring NYC Public School Test Result Scores.ipynb` notebook.
3. Run the cells sequentially to perform data cleaning, analysis, and visualizations.

## Data

The dataset used in this project is `schools.csv`, which contains the following columns:

- `school_name`: Name of the school
- `borough`: Borough where the school is located
- `building_code`: Code of the school building
- `average_math`: Average math test scores
- `average_reading`: Average reading test scores
- `average_writing`: Average writing test scores
- `percent_tested`: Percentage of students tested

## Analysis

The analysis includes the following steps:

1. **Data Cleaning**:
   - Handling missing values
   - Checking for duplicate entries

2. **Data Exploration**:
   - Summary statistics for each column
   - Distribution plots for test scores
   - Correlation analysis between different test scores

3. **Visualization**:
   - Histograms and boxplots for test scores
   - Bar plots showing average scores by borough
   - Scatter plots to visualize relationships between different scores

## Results

Key findings from the analysis include:

- The correlation between math, reading, and writing scores.
- Distribution of test scores across different boroughs.
- Insights into the performance of schools based on the percentage of students tested.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
