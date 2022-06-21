## Problem Statement
A TinyML approach to prevent Electric grid overload.

![](https://www.mobilesmspk.net/user/images/screensaver_images/2013/05/29/www.mobilesmspk.net_electric-shock_68.gif)

## Description
There are various challenges when it comes to applying AI to smart Electric Grids like Insufficient data accumulation, Reliability, Infrastructure, Lack of power insdustry-specific algorithms, etc. In this project, we predict the grid stability using Neuton TinyML and an integrated IoT platform, Particle IoT, an approach where we combine the knowledge of AI and IoT. The dataset for this prediction mechanism contains 10,000 observations with 12 predictive and a dependent variable. The data set can be found [here](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+). With this data set, we train the model to be able to predict the stable/unstable nature of the electric grid. Upon testing the model, the accuracy is found to be around 92%. We opt the Patricle Argon borad for this project, which is a Wi-Fi based development kit with Nordic nRF52840 and ESP32 processors. Particle Build web IDE and Neuton are used as programming environment and workbench respectively. 
### Hardware components
    Particle Argon
### Software requirements
    Neuton TinyML Neuton
    Particle Build Web IDE
The link to the whole project explanatory can be found at https://www.hackster.io/alexmiller11/detecting-unstable-electrical-grid-with-tinyml-927963


