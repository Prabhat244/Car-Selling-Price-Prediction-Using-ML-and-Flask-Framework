# Car-prediction-ML-Flask

https://car-price-prediction-flask.herokuapp.com/

############# ...................Create Virtual Environment in "Anaconda Command prompt" ................................................
.....................................................................................................................................................................................................
a. Open Anaconda Command prompt
b. type the command:- ( conda create -n carprediction python=3.7 )
c. Now Run the Command :- ( conda activate carprediction )

d. Download the "car data.csv" Dataset from link:-
https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

e. Place the "car data.csv" Dataset into a "Car Prediction Project" folder in a directory.

f. In Anaconda Command prompt, Go to the Project directory where dataset is present.....
  (carprediction) C:\Users\Car Prediction Project>

g. Now Run the command below:-
  (carprediction) C:\Users\Car Prediction Project>python app.py

h. Now open the URL: http://127.0.0.1:5000 to run and see the Deployment Model.

.....................................................................................................................................................................................................
############# ...................Steps to Create the Requirement File ...........................................................................................
.....................................................................................................................................................................................................

1.   Go to the Project directory where Project files are present.....
      C:\Users\Car Prediction Project>

2.  Activate the the Virtual environment...."carprediction "
     C:\Users\Car Prediction Project>activate carprediction 

3. To Automatically create the "requirement.txt" file......type the command below:-
   (carprediction) C:\Users\Car Prediction Project>pip freeze > requirements.txt

4 Now You will get the "requirement.txt" file in the current project directory ....which contains:-

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

