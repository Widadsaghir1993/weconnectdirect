   mkdir Projects
   cd Projects/
   mkdir smm
   cd ssm
pwd 
/home/mufaddal/Projects/smm
   mkdir djangoenv
   virtualenv djangoenv/
   source djangoenv/bin/activate
   unzip openeats.zip 
   cd openeats
   pip install -r requirements.txt 
   python manage.py runserver 0.0.0.0:7200 &
