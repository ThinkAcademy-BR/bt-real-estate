# Instructions

### **1. Install PostgreSQL and create a new database**
		 1.1 - https://www.postgresql.org/download/
		 1.2 - Create a new database

### **2. Create a 'secrets.json' file with your SECRET_KEY, DB_NAME, DB_USER, DB_PASSWORD and ALLOWED_HOSTS**
		 Example: https://ibb.co/df6rnb3		 

### **3. Create a virtualenv with Python 3.7 and install all the requirements**
		 3.1 - python3.7 -m venv .venv
		 3.2 - Linux/Mac
			 3.2.1 - source .venv/bin/activate
			 3.2.2 - pip install pip --upgrade
			 3.2.3 - pip install -r requirements.txt
		 3.3 - Windows
			 3.3.1 - source .venv/Scripts/activate
			 3.3.2 - pip install pip --user --upgrade
			 3.3.3 - pip install -r requirements.txt
		 

### **Make migrations**
		 python manage.py makemigrations && python manage.py migrate

### **Enjoy!**
		 python manage.py runserver
