## MACHINE LEARNING PROJECT
## Diamond Price Prediction

## Problem Statement
A diamond distributor has recently decided to exit the market and has put up a set of 3,000 diamonds up for auction. Seeing this as a great opportunity to expand its inventory, a jewelry company has shown interest in making a bid. To decide how much to bid, you will use a large database of diamond prices to build a model to predict the price of a diamond based on its attributes. Then you will use the results of that model to make a recommendation for how much the company should bid.

The diamond price that the model predicts represents the final retail price the consumer will pay. The company generally purchases diamonds from distributors at 70% of the that price, so your recommended bid price should represent that.

## Data Understanding
We will be predicting prices for the gemstone.csv dataset.

Carat represents the weight of the diamond, and is a numerical variable.
Cut represents the quality of the cut of the diamond, and falls into 5 categories: fair, good, very good, ideal, and premium. In project zero, these categories were represented by an ordinal variable, 1-5. You can decide to use the ordinal or categorical variable.
Clarity represents the internal purity of the diamond, and falls into 8 categories: I1, SI2, SI1, VS2, VS1, VVS2, VVS1, and IF (in order from least to most pure). In project zero, these categories were represented by an ordinal variable, 1-8. You can decide to use the ordinal or categorical variable.
Color represents the color of the diamond, and is rated D through J, with D being the most colorless (and valuable) and J being the most yellow.

# STEPS to run this project:


## STEP 01: 
Create an environment


```bash
conda create -n Diamond  python=3.7 -y
```

To activate the environment

```bash

 conda activate Diamond
```

## STEP 02: 
Install the requirements


```bash
pip install -r requirements.txt
```


## STEP 03: 
Just execute this command & wait, it may take some time


```bash
python application.py
```

## STEP 04: 
after run application.py 

```bash
Example :
(Diamond) D:\Diamond Price Prediction>python application.py
 * Serving Flask app 'application'
 * Debug mode: on

```
## STEP 05: 
Go to the Log folder Let's check latest log file

```bash
Example :
[ 2024-04-10 04:08:31,708 ] 96 werkzeug - INFO - [31m[1mWARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.[0m
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://192.168.81.28:5000
[ 2024-04-10 04:08:31,708 ] 96 werkzeug - INFO - [33mPress CTRL+C to quit[0m
[ 2024-04-10 04:08:31,709 ] 96 werkzeug - INFO -  * Restarting with stat

```
## STEP 05: 

```bash
Example :
click on  http://127.0.0.1:5000 then the output window will open 
```



## Home Page

<img width="960" alt="image" src="https://github.com/anil-rupnar/crack-Dream-Data-Science-Job/blob/main/120Dayschallenge/Day61/Diamond%20Price%20Prediction%201/notebooks/Screenshot%20(161).png">


## Result

<img width="960" alt="image" src="https://github.com/anil-rupnar/crack-Dream-Data-Science-Job/blob/main/120Dayschallenge/Day61/Diamond%20Price%20Prediction%201/notebooks/Screenshot%20(162).png">



# Authors:
```bash
Author: Vaibhavi Kinnake
College : Goverment College Of Engineering Chandrapur.
Email: vaibhavikinnake12@gmail.com
```
