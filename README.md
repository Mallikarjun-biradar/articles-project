
This application is developed for publishing articles

Project Setup
Creating environment

pip install virtualenv
virtualenv env

activating env
source env/bin/activate    # for linux
Scripts\bin\activate    #for windows


installing projects requirements 
pip install -r requirements.txt

running projects

python manage.py createsuperuser
python manage.py collectstatic
python manage.py runserver
 
visit this link.
http://127.0.0.1:8000/articles/



