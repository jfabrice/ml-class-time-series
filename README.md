# Time Series specificities

## Data analyst classroom trainings

This repository contains course materials for my Machine Learning class on the topic of Time Series specificities:
- <em>time_series_class.pdf</em> : course presentation with teaching content
- <em>time_series_class.ipynb</em> : Python notebook illustrating the course notions
- <em>time_series_class-empty.ipynb</em> : same Python notebook to follow with students during class


### Option 1: Working with Google Colab

To follow the notebooks with Google Colab, simply go to https://colab.research.google.com/. Import a new notebook from GitHub, search for "jfabrice" and open one of the notebooks of this class (ml-class-time-series), for example time_series_class-empty.ipynb. Then click on "Copy to Drive" to be able to execute it. The first section of the notebook is there to initialize the environment from Google Colab.


### Option 2: Working locally - Setting up Anaconda environment

To setup the Anaconda environment with required dependencies, execute the following instructions in Anaconda prompt or Linux shell.

```shell
# Clone this github repository on your machine
git clone https://github.com/jfabrice/ml-class-time-series.git

# Change working directory inside the repo
cd ml-class-time-series

# Create a new virtual environment
conda create -n timeseriesenv python==3.6

# Activate the environment
## For Linux / MAC
source activate timeseriesenv
## For Windows
activate timeseriesenv

# Install the requirements
pip install -r requirements.txt
```
