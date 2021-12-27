# E-commerce-store
A demo E-commerce store with 10 pages as well as a fully functional cart.

# Installation :

follow these steps to clone and get this app running :

NOTE : you need to change the settings for the secret-key and database in config/settings.py for the app to run succesfully as well as making DEBUG=True .
 
 - First clone this repo :

            $ git clone https://github.com/ouhadjilyes/E-commerce-store.git
            $ cd E-commerce-store

 - then you need to create a virtual environment and install the required dependencies :
            
            $ pipenv install -r requirements.txt
            $ pipenv shell 
            $ python3 manage.py runserver 
           
 - then visit -> http://127.0.0.1:8000/
