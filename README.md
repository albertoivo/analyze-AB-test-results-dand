# Analyze A/B Test Results

This project analyzes the results of an A/B experiment conducted by an e-commerce website. The goal is to determine, through statistical analysis and hypothesis testing, whether the proposed new page generates more conversions than the old page. The notebook includes data cleaning, exploratory analysis, statistical tests, and regression modeling.

## How to Install and Run the Project

### 1. Clone the repository (if needed)
```bash
git clone git@github.com:albertoivo/analyze-AB-test-results-dand.git
cd analyze-ab-test-result
```

### 2. Create a virtual environment with conda
```bash
conda create -n abtest python=3.10
conda activate abtest
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook
```bash
jupyter notebook
```

Open the file `Analyze_ab_test_results_notebook.ipynb` and follow the instructions in the notebook to perform the analysis.

## Project Structure
- `Analyze_ab_test_results_notebook.ipynb`: Main notebook with all analysis steps.
- `ab_data.csv`: A/B experiment dataset.
- `countries.csv`: User country data.
- `requirements.txt`: Project dependencies list.

## Notes
- Make sure you have Anaconda or Miniconda installed.
- All necessary data files are included in the repository.
