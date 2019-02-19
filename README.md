# Generate-TV-Scripts
RNN Project [Udacity Deep Learning Nanodegree]

## Project Overview
### Project Description
Generate a new TV script for a scene at Moe's Tavern using Recurrent Neural Network(RNN).

### Project Procedure
- Preprocess the data
  - Transform words to ids
  - Tokenize punctuation
- Create lookup table
- Build RNN
- Train RNN
- Generate TV script

### Project Results
- Generated TV script for a scene at Moe's Tavern successfully.
- Need to get more data to train to get a better results.


## Getting Started
### Prerequisites
This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Tensorflow](https://www.tensorflow.org/install/pip)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


### Run
In a terminal or command window, run one of the following commands:

```bash
ipython notebook Your_first_neural_network.ipynb
```  
or
```bash
jupyter notebook Your_first_neural_network.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
```bash
data/simpsons/moes_tavern_lines.txt
```  
Part of the Simpsons dataset of scripts which consists of only the scenes in Moe's Tavern.
