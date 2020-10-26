# Car-prediction-ML-Flask

Create Virtual Environment in "Anaconda Command prompt" :-

a. Open Anaconda Command prompt
b. type the command:- ( conda create -n carprediction python=3.7 )
c. Now Run the Command :- ( conda activate carprediction )

d. Download the "car data.csv" Dataset from link:-
https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

e. Place the "car data.csv" Dataset into a "Car Prediction Project" folder in a directory.

f. In Anaconda Command prompt, Go to the Project directory where dataset is present.....

  (carprediction) C:\Users\Car Prediction Project>

g.  Now Run the command below:-

  (carprediction) C:\Users\Car Prediction Project>python app.py

h. Now open the URL: http://127.0.0.1:5000 to run the Deployment Model.

  
  
..............................Procfile ...........................................
web: gunicorn app:app

..............................requirements.........................................

certifi==2020.6.20
chardet==3.0.4
click==7.1.2
Flask==1.1.2
idna==2.10
itsdangerous==1.1.0
Jinja2==2.11.2
joblib==0.15.1
jsonify==0.5
MarkupSafe==1.1.1
numpy==1.19.0
requests==2.24.0
scikit-learn==0.23.1
scipy==1.5.0
sklearn==0.0
threadpoolctl==2.1.0
urllib3==1.25.9
Werkzeug==1.0.1
wincertstore==0.2
gunicorn
