# Dog Boot Sizing Predictor

Predict the right size of doggy boots based on the harness size using machine learning.

## Introduction

The Dog Boot Sizing Predictor is a simple machine-learning project designed to estimate the appropriate size of doggy boots based on the harness size of avalanche dogs. It utilizes a pre-trained machine learning model to provide recommendations for customers purchasing doggy boots.

## Features

- Predicts doggy boot size based on harness size.
- Easy integration with your application.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

- [Python](https://www.python.org/) (version 3.9.8)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/dog-boot-sizer.git
    cd dog-boot-sizer
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Integrate the Dog Boot Sizing Predictor into your application by following the example in `main.py`. The `check_size_of_boots` function takes the selected harness size and boot size as input and provides recommendations.

```python
from sizing_predictor import check_size_of_boots

result = check_size_of_boots(selected_harness_size=55, selected_boot_size=39)
print(result)
