# Nucleus SDK
Nucleus SDK with instructions and examples on how to use Nucleus APIs

## Overview
Nucleus SDK is a suite of high-performance text-analytics APIs developed by SumUp Analytics, Inc and subject to Terms of Services available at www.sumup.ai. Copyright SumUp Analytics Inc, 2018.

Those APIs enable end-users to perform the following tasks:
1. Analytics
* Topic modeling
* Summarization at the Topic and Document level
* Sentiment analysis at the Topic level
* Consensus analysis at the Topic level
* Content recommendation at the Topic level
* Historical analysis of prevalence, sentiment and consensus at the Topic level
* Author connectivity analysis
* Topic exposure variation, as building block for time-series predictive modeling

2. Dataset Management
* Dataset creation (whole pre-processing pipeline)
* Retrieval of documents metadata
* Document display
* Selective documents deletion
* Dataset deletion

10 languages are currently supported by those APIs: English, Mandarin, Japanese, Portuguese, Spanish, German, Russian, Italian, French, Farsi.

The core task, topic modeling, has been benchmarked against Scikit-Learn, Gensim and AWS Comprehend topic models and delivers 100x speed-up with 2x accuracy. More details can be found at www.sumup.ai in Nucleus Solution Brief (https://www.sumup.ai/SumUp%20Real-Time%20Text%20Analytics%20Solution%20Brief.pdf)

## Python SDK
### Prerequisites
1. Python 3.5 or 3.6 is set up in a virtual environment. More details: https://docs.python.org/3/tutorial/venv.html . All commands in this documents assume running python from the virtual environment.

### Install Nucleus API Package
```
pip install nucleus-api --upgrade
```

### Documentation
The documentation on all available APIs can be found in python/docs/README.md

A [Guideline for Calibration](python/examples/Guidelines%20for%20Calibrating%20Nucleus%20APIs.pdf) is available in examples/ directory.

### Examples using Nucleus APIs
1. Go to the examples directory `cd python/examples`
1. An example using all APIs is provided in a Jupyter Notebook (all-api-examples.ipynb) and a Python script all-api-examples.py 
1. Open the example in Jupyter Notebook or a text editor and update the lines below with provided host name and API key  
    ```
    configuration.host = 'API_HOST_HERE'
    configuration.api_key['x-api-key'] = 'API_KEY_HERE'
    ```
1. Execute the example in Jupyter Notebook or using the command line: 'python3 all-api-examples.py'

