# bioactivity-prediction-app



[Bioinformatics Project from Scratch - Drug Discovery #6 (Deploy Model as Web App) | Streamlit 

<a href="https://youtu.be/m0sePkuyTKs"><img src="http://img.youtube.com/vi/m0sePkuyTKs/0.jpg" alt="Bioinformatics Project from Scratch - Drug Discovery #6 (Deploy Model as Web App) | Streamlit #22" title="Bioinformatics Project from Scratch - Drug Discovery #6 (Deploy Model as Web App) | Streamlit #22" width="400" /></a>

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *bioactivity*
```
conda create -n bioactivity python=3.7.9
```
Secondly, we will login to the *bioactivity* environement
```
conda activate bioactivity
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/bioactivity-prediction-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```
### Generating the PKL file

The machine learning model used in this web app will firstly have to be generated by successfully running the included Jupyter notebook [bioactivity_prediction_app.ipynb]
. Upon successfully running all code cells, a pickled model called acetylcholinesterase_model.pkl will be generated.

###  Launch the app

```
streamlit run app.py
```
