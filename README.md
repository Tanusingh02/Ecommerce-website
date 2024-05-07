This is the dynamic Website for Django

To run this project in your computer, follow the steps below
-------------------------------------------------------------
Step 1. Make and activate virtual Environment in your computer
    In windows
    > virtualenv ecom
    > Scripts\activate
    In mac and linux
    $ virtualenv ecom
    $ source bin/activate

Step 2: Clone the project
        git clone git@github.com:Tanusingh02/Ecommerce-website.git 
        
Step 3: Install dependencies 
    $ pip install -r requirements.txt
    or 
    $ pip install django pillow requests six

Step 4: Apply the migration if any
    $ python manage.py migrate

Step 5: You can now open project folder in your editor

Step 6: Run Development server
    $ python manage.py runserver

Now website can be run locally.
