# Clean Energy Data Analysis and Machine Learning Models

## Overview

This project analyzes clean energy data from multiple countries and applies machine learning techniques such as regression and clustering. The dataset, `cleanenergy1985.xlsx`, is processed to extract insights and evaluate models using various metrics.

## Features

- Data preprocessing and exploration
- Linear regression for predictive modeling
- K-Means clustering for data segmentation
- Performance evaluation using multiple metrics
- Data visualization with matplotlib and seaborn

## Technologies Used

- Python
- Pandas, NumPy (Data Handling)
- Scikit-learn (Machine Learning Models & Metrics)
- Matplotlib, Seaborn (Visualization)

## Dataset

The dataset used in this project is `cleanenergy1985.xlsx`. It includes energy consumption and production data for countries such as:

- Congo
- Turkey
- Russia
- China
- United States

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Ensure the dataset (`cleanenergy1985.xlsx`) is available in the project directory.

## Usage

Run the Jupyter Notebook:

```sh
jupyter notebook final_project_models.ipynb
```

Follow the steps in the notebook to load data, preprocess, train models, and visualize results.

## Model Evaluation

- **Linear Regression**: Evaluated using Mean Squared Error (MSE)
- **K-Means Clustering**: Evaluated using Silhouette Score and Davies-Bouldin Score

## Results

- Predictive performance for energy trends
- Clustering insights into energy consumption patterns

## Future Improvements

- Include more machine learning models
- Optimize hyperparameters
- Expand dataset for more countries

## License

This project is licensed under the MIT License. See [LICENSE](https://github.com/Abdelrahman-7z7/clean-energy-model/blob/main/LICENSE) for details.

## Author

Abdelrahman-7z7 (https://github.com/Abdelrahman-7z7)
