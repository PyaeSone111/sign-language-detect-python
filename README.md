# sign-language-detector-python

Step by Step Guide

-- reminder -> most suitable with python version 3.10.*

under sign-language-detector-python folder run 

-- SETUP --
-> python -m venv venv
-> .\venv\Scripts\activate
-> pip install -r requirements.txt

-- to collect alphabet data --
run command to train (A - Z)
->python collect_imgs.py 

-- create dataset --
run command to create data.pickle file
->python create_dataset.py

-- to train alphabet data--
run command to train (model.p file will create)
->python train_classifier.py

--use for detect--
->python inference_classifier.py

if want to retain -> can delete all file under data, data.pickle and model.p to avoid conflict

