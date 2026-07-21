# GoogleTrendArchive Tutorial 

This repository contains a tutorial-style Jupyter notebook for working with Google Trend / trending-query data. 

> Urman, A., Hannák, A., & Baumann, J. (2026). *GoogleTrendArchive: A Year-Long Archive of Real-Time Web Search Trends Worldwide*. Proceedings of the International AAAI Conference on Web and Social Media, 20(1), 2936–2948. https://doi.org/10.1609/icwsm.v20i1.42793

Paper link: https://ojs.aaai.org/index.php/ICWSM/article/view/42793/50353

## What this notebook covers

- loading and preparing the data
- quick exploratory statistics at the beginning of the workflow
- keyword and regex-based filtering of trend records
- examples for working with names, entities, and multi-keyword filters
- notes on multilingual use cases and country lists
- practical guidance for Wikipedia-style keyword inputs
- examples that can be adapted by changing parameters

## How to use it

Open the notebook in JupyterLab, VS Code, or any environment that supports `.ipynb` files, then run the cells top to bottom.

The notebook is written as a tutorial, so the markdown cells explain the purpose of each step and the code cells show the implementation.

## Tips while exploring

- Try changing keyword filters and parameters in the examples to see how the output changes.
- Multi-word queries can often be chained as filters, effectively combining conditions with an AND-style logic.
- The language examples are intentionally limited, but the same workflow can be extended to additional languages and countries.
- Some regex-based operations may take a while on larger data.
- For Wikipedia-style inputs, spacing in the keyword can matter, so check the argument settings carefully.

## Project structure

- `load_data copy 2(1).ipynb`: main notebook version with tutorial improvements
- `data/country-code.csv`: list of countries and their standart codes

