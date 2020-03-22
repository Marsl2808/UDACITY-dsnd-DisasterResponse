# Disaster Response Pipeline 

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Instructions](#instructions)

## 1. Installation <a name="installation"></a>
Needed libraries:
- NumPy
- Pandas

## 2. Project Motivation <a name="motivation"></a>
The Project is part of the UDACITY Datascientist Nanodgree program.

## 3. File Descriptions <a name="files"></a>  
- process_data.py: ETL pipeline
- train_classifier.py: ML pipeline
- run.py: Web-App

## 4. Instructions <a name="instructions"></a>
a) Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

b) Run the following command in the app's directory to run your web app.
    `python run.py`

c) Go to http://0.0.0.0:3001/





