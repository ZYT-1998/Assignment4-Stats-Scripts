# Assignment 4: Python Statistics Scripts

This repository contains a manual statistics walkthrough and an AI-assisted version using Python. The analyses use brain-size, iris, and wage datasets to demonstrate descriptive statistics, hypothesis testing, regression, visualization, and interaction analysis.

## Repository Structure

- `notebooks/stats_python.ipynb`: Manual walkthrough based mainly on the provided tutorial code
- `ai/stats_python.ipynb`: AI-generated statistics walkthrough
- `ai/stats_extension.ipynb`: AI-generated bootstrap confidence interval extension
- `ai/PROMPTS.md`: Prompts used to generate the AI analyses
- `examples/`: Data files used in the notebooks
- `REFLECTION.md`: Comparison and evaluation of the manual and AI work
- `environment.yml`: Conda environment information

## Installation

Create and activate the environment:

conda env create -f environment.yml  
conda activate stats-env

Then start JupyterLab:

jupyter lab

## Usage

Open each notebook and run all cells from top to bottom. The notebooks expect the datasets to be stored in the `examples` folder.

## Acknowledgments

The manual walkthrough was based on the statistics section of the SciPy Lecture Notes. AI was used to generate the assisted analysis, statistical extension, explanations, and code organization.

This repository was created for educational purposes.
