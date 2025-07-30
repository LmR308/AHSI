# Optimizing Aesthetic Perception through Human-AI Teaming for Subtle Dimension Identification in Art Annotation

This repository provides a PyTorch implementation of the Optimizing Aesthetic Perception through Human-AI Teaming for Subtle Dimension Identification in Art Annotation presented in our AAAI 2026 paper.

## Get Started

### Requirements and Installation

The require environments are in **environment.yaml**,you can run below command to install the environment:

```python
conda env create -f environment.yaml
```

## Usage

Train the model by running the main.py directly. Remember to set the chosen dataset, model backbone and hyper-parameters in the script.Please use the following command to load demo data for testing whether the environment is successfully installed.

```python
python main.py --data_path ./data
```

optional arguments:  
```--help``` show this help message and exit  
```--data_path``` show the the path of data  

## Note

The data used in this experiment is anonymous and temporarily not publicly available, so encrypted data (data.json, reflect.json) is used.
