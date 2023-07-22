# Real-Time-Speech-Recognition

``
A Real-Time Transcription Web App in Python using AssemblyAI and Streamlit.
``


![](https://github.com/Anas436/Real-Time-Speech-Recognition/blob/main/demo.png)



# 1. Obtain the AssemblyAI API key

Obtain your free [AssemblyAI API key](https://www.assemblyai.com/?utm_source=youtube&utm_medium=social&utm_campaign=dataprofessor_realtime).

# 2. Running the real-time transcription web app
To recreate this web app on your own computer, do the following.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *transcription*
```bash
conda create -n transcription python=3.9
```
Secondly, we will login to the *transcription* environment
```bash
conda activate transcription
```

###  Download GitHub repo

```bash
git clone https://github.com/Anas436/Real-Time-Speech-Recognition
```

###  Pip install libraries
```bash
pip install -r requirements.txt
```

###  Launch the app

```bash
streamlit run app.py
```
