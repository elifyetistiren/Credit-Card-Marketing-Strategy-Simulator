
# Credit Card Marketing Campaign Simulation

This project simulates and evaluates a targeted marketing campaign aimed at acquiring new customers for credit card or loan products. It encompasses customer segmentation, A/B testing, and campaign performance analysis, including ROI calculations.

## Table of Contents

- [Objective](#objective)
- [Dataset](#dataset)
- [Project Components](#project-components)
  - [1. Customer Segmentation](#1-customer-segmentation)
  - [2. A/B Test Simulation](#2-ab-test-simulation)
  - [3. Campaign Performance Analysis](#3-campaign-performance-analysis)
- [Results](#results)
  - [Group Summary](#group-summary)
  - [ROI Analysis](#roi-analysis)
- [Tools and Technologies](#tools-and-technologies)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Objective

To simulate and evaluate a targeted marketing campaign for acquiring new customers for credit card or loan products by:

- Identifying high-value customer segments using clustering techniques.
- Creating an A/B test simulator to evaluate campaign performance.
- Analyzing campaign lift and ROI.

## Dataset

The project utilizes the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing), which contains data related to direct marketing campaigns of a Portuguese banking institution.

## Project Components

### 1. Customer Segmentation

Performed K-Means clustering on selected features (`age`, `balance`, `duration`, `campaign`) to identify distinct customer segments.

### 2. A/B Test Simulation

Simulated an A/B testing scenario:

- **Group A (Control):** Did not receive the marketing campaign.
- **Group B (Treatment):** Received the marketing campaign.

Conversion rates and spend were simulated for both groups to assess the impact of the campaign.

### 3. Campaign Performance Analysis

Calculated key performance metrics including conversion lift, revenue lift, campaign cost, incremental revenue, and ROI to evaluate the effectiveness of the marketing campaign.

## Results

### Group Summary

| Group      | Conversion Rate | Average Spend | Total Conversions | Total Revenue |
|------------|-----------------|---------------|-------------------|---------------|
| **Control** (A)  | 2.01%           | $975.44       | 100               | $97,544       |
| **Treatment** (B)| 4.86%           | $1,012.11     | 243               | $246,947      |

### ROI Analysis

| Metric                 | Value             |
|------------------------|-------------------|
| Conversion Lift        | 2.85%             |
| Revenue Lift           | $149,403          |
| Campaign Cost          | $15,000           |
| Incremental Revenue    | $143,403          |
| **ROI**                | 9.56              |

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib
- **Visualization:** Power BI
- **Others:** Jupyter Notebook

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-card-marketing-simulation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd credit-card-marketing-simulation
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Credit_Card_Campaign_Simulation.ipynb
   ```

5. Follow the steps in the notebook to run the simulation and analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
