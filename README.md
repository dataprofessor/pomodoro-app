# pomodoro-app

# Watch the tutorial video

[Let's Build a Pomodoro Web App for Data Science | Streamlit #15](https://youtu.be/9a234-OvbIQ)

<a href="https://youtu.be/9a234-OvbIQ"><img src="http://img.youtube.com/vi/9a234-OvbIQ/0.jpg" alt="Let's Build a Pomodoro Web App for Data Science | Streamlit #15" title="Let's Build a Pomodoro Web App for Data Science | Streamlit #15" width="400" /></a>

:star:

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/pomodoro-app/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *pomodoro*
```
conda create -n pomodoro python=3.7.9
```
Secondly, we will login to the *pomodoro* environement
```
conda activate pomodoro
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/pomodoro-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```
###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/pomodoro-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
