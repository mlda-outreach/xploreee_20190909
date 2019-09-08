# MLDA-Enthuse-V2 (09-Sep-2019)

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [MLDA-Enthuse-V2](#mlda-enthuse-v2)
	- [Steps to follow:](#steps-to-follow)
		- [Step 1 - Logging into Google Colab](#step-1-logging-into-google-colab)
		- [Step 2 - Opening a notebook](#step-2-opening-a-notebook)
		- [Step 3 - .csv file URL](#step-3-csv-file-url) 
	- [Topics Covered](#topics-covered) 

<!-- /TOC -->
## Steps to follow:
### Step 1a - Logging into Google Colab
** If you don't have a google account, skip to Step 1b **

- Go to [https://colab.research.google.com](https://colab.research.google.com)
- Sign in to your google account
- If you are new to google colab notebook, watch this Youtube video -  [Get started with Google Colaboratory (Coding TensorFlow)](https://youtu.be/inN8seMm7UI) 

### Step 2 - Opening a notebook
- Click `File > New Python 3 Notebook` to create a new `.ipynb` file online
- Wondering what's a notebook?
    - Think of it like a word document where you can write your python code, run and see the outputs, add comments and notes, insert images, etc. in one place.

### Step 3 - .csv file URL
- To directly load the .csv file into your current python program, right-click and copy the corresponding url shown below and paste it inside the `pd.read_csv` command
    ```python
    import pandas as pd
    pd.read_csv(###DATA_URL_HERE###)
    ```


#### csv data
- Titanic.csv - [CSV Link](https://raw.githubusercontent.com/prasanth-ntu/MLDA-Enthuse-V2/master/Part%201%20-%20Intro%20to%20Python%20and%20Python%20Libraries/data/Titanic.csv) 

- 50_Startups.csv - [CSV Link](https://raw.githubusercontent.com/prasanth-ntu/MLDA-Enthuse-V2/master/Part%202%20-%20Intro%20to%20Data%20Science%20and%20Hands-on%20Mini%20Projects/Supervised%20Learning/50_Startups.csv) 




## Topics Covered
1. What is Data Science - [PPT](Part%202%20-%20Intro%20to%20Data%20Science%20and%20Hands-on%20Mini%20Projects/What%20is%20Data%20Science.pptx)
2. Introduction to Python Basics - [PPT](Part%201%20-%20Intro%20to%20Python%20and%20Python%20Libraries/Basic%20python_MLDA_w_ans.pptx) [ipynb code](to come)
3. Introduction to Python Libraries - [ipynb code](Part%201%20-%20Intro%20to%20Python%20and%20Python%20Libraries/Introduction%20to%20Python%20Libraries.ipynb) 
4. Linear Regression - [ipynb code](Part%202%20-%20Intro%20to%20Data%20Science%20and%20Hands-on%20Mini%20Projects/Supervised%20Learning/Linear%20Regression.ipynb) 



-----
