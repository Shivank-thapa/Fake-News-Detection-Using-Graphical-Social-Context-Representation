# Factual News Graph (FANG)
This is the implementation of FANG - a graph representation learning framework for fake news detection. 

## Installation
```bash
conda env create -f environment.yml 
```

## Requirements
### Packages
* conda 4.8.2
* python 3.7.7
* torch 1.5.1
* tensorboard 1.15.0

### Hardware
* CPU: Intel i7
* Memory: 16GB total memory

## Run Path
Base Code Run-> FinalSubmission/Original Code/FANG-master/run_graph.py
Updated Code Run-> FinalSubmission/Updated Code/FANG-master/run_graph.py

## Run GraphSage model
Training FANG for `30` epochs at `90%` data with `temporality`, `stance loss` and `proximity loss`.
# Command:

```
python run_graph.py -t fang -m graph_sage -p data/news_graph --percent 90 --epochs=30 --attention --use-stance --use-proximity --temporal
```

## "FinalSubmission" folder consists of 
"Original Code Run Log" contains Log file of Base Code Run
"Updated Code Run Log" contains Log file of Updated Code Run
"noofsteps vs newsloss" and "Clusters determined by K Means" Screenshots for respective graphs. 
"FinalPresentation.pptx" contains Presentation.



