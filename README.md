# Gender Payment Disparity Analysis

This repository contains the project files for the analysis of gender payment disparities in the biotech industry conducted as part of the INT6940 XN Project. **This project addresses critical issues of equity and fairness in the workplace by uncovering systemic disparities in payment practices. By shedding light on these imbalances, the analysis aims to drive actionable change and contribute to a more inclusive professional environment.**

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Results and Insights](#results-and-insights)
- [Visualizations](#visualizations)
- [How to Use](#how-to-use)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

---

## Overview

The project explored gender disparities in high-value payment categories such as consulting fees and acquisitions. By leveraging advanced data analytics techniques, the analysis uncovered significant opportunity gaps for females in payment roles exceeding \$3,480. This project also highlighted systemic inequities and offered evidence-based recommendations to promote fairness.

## Features

- **Data Cleaning**: Automated cleaning and preprocessing of datasets spanning three years.
- **Gender Identification**: Integration of the REA_GenderIdentification model to classify gender with 80-90% accuracy.
- **Visualization**: Interactive visualizations showcasing payment gaps, trends, and systemic inequities.
- **Analysis**: Comprehensive analysis of payment categories and their respective gender disparities.

## Data Sources

The data for this project was sourced from the Centers for Medicare & Medicaid Services (CMS) General Payments Dataset (2021-2023). This dataset includes:

- Nature of Payments
- Total Amount of Payments (in USD)
- Covered Recipient Type
- Gender Information

## Technologies Used

- **Languages**: Python (Pandas, Plotly, Seaborn)
- **Visualization Tools**: Tableau, Plotly
- **Frameworks**: Agile methodology for project management
- **Models**: REA_GenderIdentification (Hugging Face)

## Results and Insights

- Identified a **41:100 female-to-male ratio** in high-value payment categories.
- Highlighted the systemic opportunity gap for women in roles with payments exceeding \$3,480.
- Proposed actionable recommendations, including annual monitoring programs and targeted interventions to ensure equitable payment practices.

## Visualizations

Key visualizations include:

1. **Payment Trends Over Time**: Highlighting gender-specific payment trends.
2. **Payment Gaps by Category**: Interactive charts showcasing disparities in consulting fees, acquisitions, and other high-value roles.
3. **Opportunity Gap Analysis**: Visualizations emphasizing the imbalance in payment opportunities above \$3,480.

## How to Use

### Prerequisites

1. Install Python 3.8 or later.
2. Install the required Python packages:

```bash
pip install pandas plotly seaborn
```

3. Access Tableau for advanced visualizations.

### Running the Analysis

1. Clone the repository:

```bash
git clone https://github.com/nikhil-doye/gender-payment-disparity-analysis.git
```

2. Navigate to the project directory:

```bash
cd gender-payment-disparity-analysis
```

3. Run the analysis scripts:

```bash
python analysis.py
```

4. View visualizations in Tableau or using Python Plotly scripts.

## Future Enhancements

- **Predictive Modeling**: Implement machine learning models to forecast gender disparities over time.
- **Automation**: Automate the data cleaning and visualization pipeline.
- **Expanded Analysis**: Include additional factors such as geography and role-specific disparities.

## Contributors

- **Nikhil Doye**: Data Analysis, Visualization, Report Writing
- **Team Members**: Collaboration on analysis and presentations

---

This project was conducted as part of the INT6940 XN Project at Northeastern University. Feel free to explore the repository and contribute to future iterations!
