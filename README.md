# ict3104-team09-2023

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher installed
- Anaconda or Miniconda installed
- Jupyter Notebook installed
- Git (optional, for cloning the repository)

## Installation

1. Clone the repository:
    git clone https://github.com/mayuelala/FollowYourPose.git

2. Create and activate a virtual environment (if using conda):
    conda create -n fupose python=3.8
    conda activate fupose

3. Install ipykernel to use virtual environment in Jupyter Notebook:
    pip install ipykernel

3. Install the required packages from requirements.txt:
    pip install -r requirements.txt

## Usage

1. Activate your virtual environment:
    conda activate fupose

2. Start Jupyter Notebook:
    jupyter notebook

3. Open the provided .ipynb notebook in Jupyter Notebook and run the cells to execute your project.

4. If you make changes to the environment or packages, remember to update the requirements.txt file by running:
    pip freeze > requirements.txt

5. Deactivate the virtual environment when you are done:
    conda deactivate
