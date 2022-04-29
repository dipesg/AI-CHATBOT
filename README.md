# AI-CHATBOT
[![BCH compliance](https://bettercodehub.com/edge/badge/dipesg/Movie-Recommendation-System?branch=main)](https://bettercodehub.com/)
# Megatron
![mega1](https://user-images.githubusercontent.com/75604769/165954550-c32c26ec-16d7-40a6-a9ed-0c39f7e63476.png)

### Table of Content
  
  * [Overview](#overview)
  * [Demo](#demo)
  * [Installation](#installation)
  * [Directory Tree](#directory-tree)

### Overview
Here at Ineuron massive amount of queries floods daily which is hard to handle. Among all queries 40% of them are general, so they can be automate and huge amount of time will be saved, with this motive this app is built.
### About this project:
This is a chatbot which will handle the general queries and technical queries which daily floods in Ineuron.

### Demo:
![mega2](https://user-images.githubusercontent.com/75604769/165954056-41863885-6d48-4116-b95d-1b531fc182db.gif)

### Installation
STEPS:

Clone the repository

```bash
https://github.com/dipesg/AI-CHATBOT.git
```
Create a conda environment after cloning the repository in a particular folder

```bash
conda create -n venv python=3.7 -y
```
Activate environment
```bash
conda activate venv
```

Install the requirements
```bash
pip install -r requirements.txt
```

run this file to open a chatbot.
```bash
python app.py
```


### Directory Tree
```

|   .gitignore
|   api_file.py
|   app.py
|   config.ini
|   config_reader.py
|   database.py
|   LICENSE
|   preprocessing.py
|   Procfile
|   README.md
|   requirements.txt
|   Resultant.txt
|   runtime.txt
|   run_model.py
|   run_model_distilbert.py
|   web_scraping.py
|   
+---email-templates
|       email-template-luggage.html
|       
+---load_intent_filter
|       community_form_filter.npy
|       form_filter.npy
|       general_intent.npy
|       intents_map.json
|       list_thumbnail.npy
|       scrape_data.npy
|       technical_intent.npy
|       ticket_gen.npy
|       
+---model
|   |   classes.npy
|   |   classes_v1.npy
|   |   elmo_intent_model.h5
|   |   elmo_intent_model_v1.h5
|   |   elmo_intent_model_v1_final_sample_data.h5
|   |   
|   \---distilbert_model_40Epochs
|           config.json
|           tf_model.h5
|           tf_model.preproc
|           
+---SendEmail
|   |   sendEmail.py
|   |   
|   \---__pycache__
|           sendEmail.cpython-36.pyc
|           
+---static
|   +---bootstrap
|   |   \---css
|   |           bootstrap.min.css
|   |           
|   +---css
|   |       styles.css
|   |       styles.min.css
|   |       
|   +---img
|   |   |   blank-icon.jpg
|   |   |   bot_icon.png
|   |   |   chat-background.png
|   |   |   chatbot.png
|   |   |   chatbot1.png
|   |   |   chatbot2.png
|   |   |   chatbot3.png
|   |   |   edu_chatbot_1.jpeg
|   |   |   edu_chatbot_1.png
|   |   |   lady_bot.png
|   |   |   lady_bot1.png
|   |   |   logo.jpg
|   |   |   logo.png
|   |   |   profile.png
|   |   |   send-button.svg
|   |   |   send_button.svg
|   |   |   
|   |   \---portfolio
|   |           cabin.png
|   |           cake.png
|   |           circus.png
|   |           game.png
|   |           img1.jpg
|   |           img2.jpg
|   |           img3.jpg
|   |           img4.jpeg
|   |           img5.png
|   |           img6.jpg
|   |           safe.png
|   |           submarine.png
|   |           
|   \---js
|           freelancer.js
|           freelancer.min.js
|           main.js
|           main.min.js
|           
\---templates
        index.html
        index.min.html
```

### Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)

### Contributors
- Whole Ineuron team
