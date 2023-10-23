# Antibiotic Finder
The ensemble based gradient boosting algorithm trained on chemoinformatics descriptors of beta-lactam antibiotics to repurpose the anti-infectious FDA approved beta-lactam alternatives.

## Introduction
Antibiotic resistance is a major global health threat. It occurs when bacteria develop the ability to defeat the drugs designed to kill them. This can happen because of the overuse and misuse of antibiotics. There is a need for new and innovative antibiotics to combat the growing threat of antibiotic resistance. One way to develop new antibiotics is to repurpose existing drugs for new uses.

This repository contains an antibiotic finder that was trained on a dataset of 25 ATP-dependent Clp protease proteolytic (clpp) inhibitors and 85 random decoy chemical compounds. The finder achieved the following evaluation metrics:

* Accuracy: 97%
* Precision: 100%
* Recall: 96%
* F1 Score: 98%

The finder was used to screen 297 FDA approved infectious drugs to repurpose 2 antiviral drugs including Oseltamivir and Valganciclovir as potential and safe drug alternatives for beta-lactams.

## Installation

To run the Jupyter Notebook file in this repository, you will need to have the following software installed:

* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-Learn

You can install these dependencies using the following command:

`pip install jupyter numpy pandas scikit-learn`

Once the dependencies are installed, you can clone the repository using the following command:

`git clone https://github.com/aysanraza/antibiotic_finder.git`

## Usage

Once the dependencies are installed, you can run the Jupyter Notebook file by typing the following command in a terminal:

`jupyter notebook antibiotic_finder.ipynb`


## Version History
* 0.1
  * Initial Release

## License
This project is licensed under the  MIT license - see the LICENSE.md file for details

## Authors
* Ahsan Raza
  * aysanraza@gmail.com
  * [Linkedin](https://www.linkedin.com/in/ahsan-raza-0510b1128/)
