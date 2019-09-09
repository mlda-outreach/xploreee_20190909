# XplorEEE (09-Sep-2019)

## (Update) Solutions
Thanks for attending the workshop today! The notebook solutions are now uploaded in the `solutions/` folder.

## Steps to follow:
### Step 1a - Logging into Google Colab

- Go to [https://colab.research.google.com](https://colab.research.google.com)
- Sign in to your google account
- If you are new to google colab notebook, watch this Youtube video -  [Get started with Google Colaboratory (Coding TensorFlow)](https://youtu.be/inN8seMm7UI) 

### Step 2 - Opening a notebook
#### Importing from GitHub
- Copy notebook link from this repository
- Paste into Github URL field when you enter [Colab](https://colab.research.google.com) and press `Enter`
- Once the notebook is loaded, click `File > Save a copy in Drive`
- An editable copy will be available to you in your `My Drive/Colab Notebooks`

#### Starting new notebook
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
- Titanic.csv - [CSV Link](https://raw.githubusercontent.com/mlda-outreach/xploreee_20190909/master/data/Titanic.csv) 

- 50_Startups.csv - [CSV Link](https://raw.githubusercontent.com/mlda-outreach/xploreee_20190909/master/data/50_Startups.csv) 




## Topics Covered
1. Introduction to Data Science - [[slides](https://github.com/mlda-outreach/xploreee_20190909/blob/master/1-what_is_data_science.pdf)]
2. Introduction to Python Basics - [[slides](https://github.com/mlda-outreach/xploreee_20190909/blob/master/2-intro_python.pdf)] [[notebook](https://github.com/mlda-outreach/xploreee_20190909/blob/master/2-intro_python.ipynb)]
3. Introduction to Python Libraries - [[notebook](https://github.com/mlda-outreach/xploreee_20190909/blob/master/3-python_library.ipynb)]
4. Linear Regression - [[slides](https://github.com/mlda-outreach/xploreee_20190909/blob/master/4-linear_regression.pdf)] [[notebook](https://github.com/mlda-outreach/xploreee_20190909/blob/master/4-linear_regression.ipynb)]



-----
