# Pancreatic cancer drugs analysis

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/tossingdata.svg?style=social&label=Follow%20%40tossingdata)](https://twitter.com/tossingdata)
[![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MSI17819)

### General information
Pancreatic cancer drug analysis showed a list of FDA-approved drugs for pancreatic cancer. After preprocessing the dataset and visualising the molecules, we learn a better mechanism of action. What molecule the drug acts on.

### Dataset
The dataset contains a list of FDA-approved pancreatic cancer drugs with a smile format updated from the CheMBL database. Each molecule was displayed in a visual format from RDKit. Each molecule was then linked to a mechanism of action. The mechanism of action allows us to better understand the relationship of which molecule is exactly the target of our anticancer drugs. For example, the molecule CHEMBL481 (Irinotecan) targets CHEMBL1781, which is a single DNA topoisomerase I protein.

## Technology stack

### Computing platform
- [Miniconda environment](https://docs.conda.io/en/latest/miniconda.html)
- [Jupyter Notebook](https://jupyter.org/)
- [Visual Code Studio](https://code.visualstudio.com/)

### Packages for data pre-processing
- [Numpy](https://numpy.org/)
- [Pandas](https://numpy.org/)
- [RDkit](https://www.rdkit.org/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [ChEMBL webresource client]([https://github.com/znstrider/highlight_text](https://github.com/chembl/chembl_webresource_client))

### Data visualisation library
- [RDkit](https://www.rdkit.org/)

## Status

Project is: _in progress_

## Room for Improvement

What's next.

- using the ML technique to better understand which group of drugs could potentially be new drug candidates for pancreatic cancer
