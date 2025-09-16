# UBC Toolbox Project – Assignment 6

This repository contains the work for Assignment 6 of the UBC Data Toolbox course.  
It demonstrates Git branching, pull requests, and reproducible computational environments.

## Repository Structure
- `Report.ipynb` – Main Jupyter notebook report
- `environment.yaml` – Environment file to replicate the computational setup
- `gen-data.py` – Script to generate sample data
- `dataset-csv/` – Example dataset used in the report
- `Documents/`, `weekly meetings/` – Supporting project files

## Environment Setup
To recreate the environment, run:

```bash
conda env create -f environment.yaml
conda activate project-env
