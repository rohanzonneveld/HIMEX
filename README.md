# HIMEX
Welcome to the implementation of my master thesis: **Interpretable Hierarchical Explanations for Time-Series Models Considering Specific Interactions**

Before you start:
1. Install all required packages by running
`pip install -r requirements.txt`
2. Download the model from bert/output/IMDB: https://drive.google.com/drive/folders/1_ME4CbVsDGt_UBqwu8Df7m9CsAut5IXZ?usp=sharing. Save in the model directory.

Possible usage:
- Create explanations for the test set from SST-2 with some method (HIMEX, HEDGE, TimeSHAP or GEM-FIX) by running the corresponding file
- Recreate experiments by creating explanations for some number of samples and run `evaluate.py`
    - results will be saved in a folder 'experiments', for closer analysis
- Create explanations for custom movie reviews
