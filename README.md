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

## Assignment Process

The manual notebook follows the statistics examples from the SciPy Lecture Notes. The AI notebooks were created separately from natural-language prompts describing the datasets and statistical questions. The lecture notes were not provided to the AI. The complete AI prompt log is available in `ai/PROMPTS.md`.
