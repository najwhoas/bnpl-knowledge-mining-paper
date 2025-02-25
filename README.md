# Supporting Materials for BNPL Knowledge Mining Research Submission

## Repository Description
This repository contains the dataset and notebook code used in the research manuscript currently under submission to CommIT journal. The purpose of this repository is to enable **reviewers** to cross-check the analyses and results presented in the manuscript.

## Repository Structure
```
📁 bnpl-knowledge-mining-paper/
├── 📁 data/                # Contains the dataset used in the study
│   ├── 📄 BNPL--Original-Dataset.csv       # Dataset for topic modeling in CSV format
│   ├── 📄 BNPL--Labeled-Dataset.csv       # Dataset for sentiment analysis in CSV format
│   └── 📄 metadata.txt        # Description of the dataset's metadata
├── 📁 notebooks/              # Contains Jupyter Notebooks for analysis
│   ├── 📄 data-preparation.ipynb # Notebook for data preparation (cleaning and preprocessing)
│   ├── 📄 topic-modeling.ipynb      # Notebook for topic modeling
│   └── 📄 sentiment-analysis.ipynb # Notebook for sentiment analysis
├── 📄 LICENSE                 # License file for the repository
└── 📄 README.md               # This file
```

## Data
The data provided in this repository includes:
- **Original Dataset**: The file `BNPL--Original-Dataset.csv` contains the data used for topic modeling in the study.
- **Labeled Dataset**: The file `BNPL--Labeled-Dataset.csv` contains the data used for sentiment analysis in the study.
- **Metadata**: The file `metadata.txt` provides a detailed description of the dataset's structure, variables, and sources.

## Notebook Code
The notebooks included in this repository are as follows:
1. **Data Preparation**: This notebook covers data cleaning and preprocessing steps.
2. **Topic Modeling**: This notebook contains the implementation of topic modeling techniques used in the study.
3. **Sentiment Analysis**: This notebook contains the implementation of sentiment analysis techniques used in the study.

## Instructions for Reviewers
To facilitate the review process, please follow these steps:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/najwhoas/bnpl-knowledge-mining-paper.git
   ```
2. Open the notebooks using Jupyter Notebook or Google Colab.
3. Compare the results obtained from the notebooks with those reported in the manuscript.

## License
This repository is licensed under the [MIT License](LICENSE). Please refer to the `LICENSE` file for more details.
