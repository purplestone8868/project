# Project Structure
This repository is organized to follow best practices for data science projects. Each folder has a clear purpose to keep code, data, and documentation easy to find and maintain.
project/
│── data/               # Raw and processed datasets
│    └── dataset.csv
│
│── images/             # Figures and plots generated during analysis
│    ├── dataset-image.png
│    └── predictions.png
│
│── src/                # Source code scripts
│    ├── 01_generate-data.py
│    ├── 02_visualize-data.py
│    └── 03_plot-predictions.py
│
│── docs/               # Reports and supporting documents
│    ├── Documents/
│    └── Report.pdf
│
│── reports/            # Jupyter notebooks and detailed analysis
│    └── Report.ipynb
│
│── weekly-meetings/    # Meeting notes and planning discussions
│
│── LICENSE             # License information
│── README.md           # Project overview (this file)
│── .gitignore          # Files and folders to ignore in version control
### Notes

data/: Always keep raw datasets unchanged. Any transformations should generate new files.

images/: Helps separate figures from code and data for easier reporting.

src/: Scripts are numbered (01_, 02_, 03_) to indicate execution order.

docs/: Central place for final project documents and PDFs.

reports/: Jupyter notebooks and reproducible analysis live here.

weekly-meetings/: Organized notes to track team progress and decisions.

This structure ensures the project is:
✔️ Reproducible
✔️ Easy to navigate
✔️ Ready for collaboration
