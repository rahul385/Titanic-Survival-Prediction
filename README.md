# Titanic: Machine Learning

### Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*

## Project Motivation<a name="motivation"></a>

To train a mahcine learning model for prediction whether a person survived or not using the information provided in the dataset. For this project, I was also interested in using the dataset to better understand:

1. Were Females more like to survive?
2. Were people of higher socioeconomic class more likely to survive?
3. Were people with more siblings or spouses aboard less likely to survive?

## File Descriptions <a name="files"></a>

* `Titanic.ipynb` : The Jupyter notebook that includes data exploration, code and visualizations.
* `Titanic_Profile_Report.html` : Profiling report of training data set.
* Data: Includes dataset provided by Kaggle for the competition
    * `train.csv` : Training data
    * `test.csv` : Test data
* Visualizations: Includes all plots generated from the training data for data exploration and analysis
   * `AgeGroup-Survived.jpg` : Plot of AgeGroup vs. Survived features
   * `CabinBool-Survived.jpg` : Plot of CabinBool vs. Survived features
   * `Parch-Survived.jpg` : Plot of Parch vs. Survived features
   * `Pclass-Survived.jpg` : Plot of Pclass vs. Survived features
   * `Sex-Survived.jpg` : Plot of Sex vs. Survived features
   * `SibSp-Survived.jpg` : Plot of SibSp vs. Survived features

## Screenshots

***Screenshot 1: Females were more likely to survive***
![Screenshot 1](https://github.com/rahul385/Titanic-Survival-Prediction/tree/main/Visualizations/Sex-Survived.png)

***Screenshot 2: People with more siblings or spouse aboard were less likely to survive***
![Screenshot 2](https://github.com/rahul385/Titanic-Survival-Prediction/blob/master/Visualizations/SibSp-Survived.png)

***Screenshot 3: People with higher socioeconomic class were more likely to survive***
![Screenshot 2](https://github.com/rahul385/Titanic-Survival-Prediction/blob/master/Visualizations/Pclass-Survived.PNG)


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Author: Rahul Gupta Copyright 2020

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
