# Health-care-using-AI-and-ML
Artificial intelligence (AI) has the potential to revolutionize healthcare by improving  patient outcomes, reducing costs, and increasing efficiency. AI is already being used in  various healthcare applications, including disease diagnosis, drug discovery, medical  imaging, and patient monitoring. ML extracts patterns from raw data automatically.  

Dependencies:
asgiref==3.4.1
backports.zoneinfo==0.2.1
certifi==2016.9.26
Cython==0.29.14
Django==3.0.3
importlib-resources==5.4.0
joblib==0.14.1
numpy==1.19.5
psycopg==3.0
psycopg2==2.8.4
pytz==2023.3
scikit-learn==0.21.3
scipy==1.5.4
sqlparse==0.4.4
typing-extensions==4.1.1
zipp==3.6.0


# Disease Prediction based on symptoms provided by patient
# How To Use This
First make sure PostgreSQL and pgadmin is install in your system. then you have to manually create a DB instance on PostgreSQL named "predico", better use PgAdmin for that. make a new environment(recommended) and run...

Run pip install -r requirements.txt to install dependencies
Run python manage.py makemigrations
Run python manage.py migrate
Run python manage.py runserver
Navigate to http://127.0.0.1:8000/ in your browser

# Dataset used
https://www.kaggle.com/neelima98/disease-prediction-using-machine-learning
