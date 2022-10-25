# Alcohol-Forecasting-PyTorch-RNN
A PyTorch recurrent neural network that forecasts sales of alcohol

## [Notebook Here](https://github.com/SZun/Alcohol-Forecasting-PyTorch-RNN/blob/main/Alcohol-Forecasting-PyTorch-RNN.ipynb)

## Images from Notebook

![](./assets/original-data.png)
![](./assets/train-forecast.png)
![](./assets/train-forecast-close.png)
![](./assets/test-forecast.png)
![](./assets/test-forecast-close.png)

## Getting Started

### Prerequisites

You must have anaconda and conda installed

```
$ anaconda --version
```
*# OUTPUT: "anaconda Command line client (version 1.11.0)"*
```
$ conda --verison
```
*# OUTPUT: "conda 22.9.0"*


### Installing

**Clone** the repo using SSH

```
$ git clone git@github.com:SZun/Alcohol-Forecasting-PyTorch-RNN
```

Then **cd** into the directory

```
$ cd Alcohol-Forecasting-PyTorch-RNN
```

Create the environment, add it to jupyter and launch jupyter lab

```
$ conda env create -f pytorch_env.yml
$ jupyter kernelspec remove ENVIRONMENT_1_NAME ENVIRONMENT_2_NAME
$ conda install -c conda-forge nb_conda_kernels -y
$ jupyter lab
```

## Built With

- [Torch](https://pytorch.org/docs/stable/torch.html)
- [Scikit-Learn](https://scikit-learn.org/stable/#)
- [Pandas](https://pandas.pydata.org/docs/#)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Warnings](https://docs.python.org/3/library/warnings.html)

## Author

**Samuel Zun** 
- [LinkedIn](https://www.linkedin.com/in/szun/) | [Github](https://github.com/SZun)