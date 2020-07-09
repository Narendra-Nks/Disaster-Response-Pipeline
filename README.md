#README.md
Disaster response pipeline project

Author = [Narendra Sai Bathula](https://github.com/Narendrasai-Bathula)
Motivation for the project
In this project, I apply the skills I learned in the Data Engineering section to analyze the disaster data in Figure 8 to create a model for an API that classifies messages about disasters.

Instructions: (Run run.py directly if DisasterResponse.db and classifier.pkl already exist).
Run the following commands in the project root directory to configure the model and database.

Use the following command to run the ETL pipeline which cleans the data and stores it in the python database data / process_data.py data / disaster_messages.csv data / disaster_categories.csv data / DisasterResponse.db
Use the following command to run the ML pipeline that forms the classifier and save the python / train_classifier.py data / DisasterResponse.db models / classifier.pkl models
Finally, run the following command in the application directory to run the web application. Python run.py

Go to http://0.0.0.0:3001/

Screenshot

Example
Write: We have many problems on Delma 75 Avenue Albert Jode, these people need food and water.
