# Lovecraft_Generation

A Fined Tuned LLM for generating stories based on Lovecraft's work.

## Overview

H. P. Lovecraft was an American writer from the 20th century who brought a new horror to literature: the unknown.

Since his works are now public domain, it is possible to use the collective of his literature to fine tune a model
to write as he did.

For this project, the GPT-2 model is fine tuned using Lovecraft's collection

## Installation

This project was coded on a local machine using Python 3.11.4 and the packages described in the included requirements.txt. To mimic this environment, simply clone this repository on a local machine and run the following python command in your desired location.

```
pip install -r requirements.txt
```

This project used a virtual environment.

As a Jupyter Notebook, web applications such as Google Colab will be a servicable alternative, and the project should work fine as long as the data is loaded in appropriately.

## Data

The data used for the project is located here: https://www.kaggle.com/datasets/bennijesus/lovecraft-fiction

The contents need simply be unzipped and the concat.txt file placed into a /data folder.
