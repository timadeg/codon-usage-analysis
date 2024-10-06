# Codon Usage Analysis with Machine Learning

## Project Overview
This project involves the analysis of codon usage patterns across various species using machine learning techniques. The dataset provides codon frequency data for multiple species, aiming to explore and identify patterns that may offer insights into species classification and evolutionary relationships.

## Data Source
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/577/codon+usage).

**Citation:**  
Hallee, L. & Khomtchouk, B. (2020). Codon usage [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C5KP6B](https://doi.org/10.24432/C5KP6B).

## Project Description
The analysis uses clustering algorithms to identify patterns in codon usage. This project includes data preprocessing, dimensionality reduction, clustering, and visualization.

### Key Features
- **Data Preprocessing:** Scaling of data using `StandardScaler` and `MinMaxScaler`.
- **Machine Learning:** 
  - Clustering using K-Means and Agglomerative Clustering.
  - Dimensionality reduction using PCA.
  - Evaluation of clustering performance using silhouette scores.
- **Visualization:** Data exploration and clustering results using `matplotlib` and `seaborn`.

## File Structure
- `codon_usage.csv`: The dataset containing codon usage frequencies.
- `MLDM_TASK_2.ipynb`: The Jupyter Notebook with code for data analysis and visualization.

## How to Run
1. Clone the repository:
    ```
    git clone https://github.com/timadeg/codon-usage-analysis.git
    ```
2. Open the Jupyter Notebook (`MLDM_TASK_2.ipynb`) in your environment (e.g., Jupyter Notebook, Google Colab).
3. Run the cells to preprocess data, perform clustering, and visualize results.

## Requirements
Install the required Python libraries using:


pip install pandas numpy matplotlib seaborn scikit-learn

## License
This project is licensed under the MIT License.
