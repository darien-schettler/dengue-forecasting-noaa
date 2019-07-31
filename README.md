# A Jupyter Notebook For Investigating and Creating Baseline Models For Participation in the Dengue Forecasting NOAA Challenge

As the title suggests. This is a jupyter notebook that utilizes basic machine learning and data exploration techniques to both explore, and create a baseline model for, the dataset/competition *'Dengue Forecasting NOAA Challenge'*

## Getting Started

```
1. Clone this repository
2. Create an environment (and activate it) and install the requirements.txt file
3. Download the dataset from [here](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)
4. To match how I stored my data. Create a Data folder and nest within it input, output, and other folders (and populate accordingly)
5. Launch jupyter
6. Open the file from the cloned repositry
7. Enjoy
```

## Prerequisites

```
absl-py==0.7.1
astor==0.8.0
cycler==0.10.0
gast==0.2.2
google-pasta==0.1.7
grpcio==1.22.0
h5py==2.9.0
joblib==0.13.2
Keras==2.2.4
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0
kiwisolver==1.1.0
Markdown==3.1.1
matplotlib==3.1.1
numpy==1.17.0
pandas==0.25.0
protobuf==3.9.0
pyparsing==2.4.2
python-dateutil==2.8.0
pytz==2019.1
PyYAML==5.1.1
scikit-learn==0.21.3
scipy==1.3.0
seaborn==0.9.0
six==1.12.0
sklearn==0.0
tensorboard==1.14.0
tensorflow==1.14.0
tensorflow-estimator==1.14.0
termcolor==1.1.0
Werkzeug==0.15.5
wrapt==1.11.2
```

## Installation
**NOTE: all shell commands are via the windows command line... you can find alternatives for linux fairly easily**

1. Clone this repository and navigate into it within the command line

2. Create and activate an environment (if you wish)<br>
` python -m venv env `<br>
` env\scripts\activate `<br>
` python -m pip install --upgrade pip `<br>

3. Execute the following commands to install all the requiremets<br>
` pip install -r requirements.txt`<br>

4. Join this competition to be able to download the dataset (or find it directly via NOAA) and create the following folder structure<br>
```
dengue-forecasting-noaa
|---- dengue-noaa.ipynb
|---- requirements.txt
|---- data
|\
| \
|  \
|   |---- input
|   |   |---- dengue_features_test.csv
|   |   |---- dengue_features_train.csv
|   |   '---- dengue_labels_train.csv
|   |---- output
|   |---- other
|   |   '---- submission_format.csv
|  /
| /
|/
|---- README.md
|---- LICENSE.md
|---- CONTRIBUTING.md
```
4. To open the jupyter environment run the following<br>
` jupyter notebook --port=8888`<br>

5. Navigate to the cloned directory and open the .ipynb file<br><br>
***See deployment for notes on how to deploy the project on a live system.***

## Deployment

To deploy this on a system and leave it running, you will need to attach the jupyter instance to a seperate 'screen' in the terminal/cmd prompt. There are different ways of doing this but you should be able to find the appropriate documentation easily. <br>
As this is a learning tool, there is no further information regarding deployment via docker, etc.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## Authors

**Darien Schettler** -- [Portfolio](http://darienschettler.ca/) -- [Github](https://github.com/darien-schettler)


## Licensing

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
