# WEBHOOK
Webhookify is an app that consists of an admin site where you can create an account and register multiple destinations for the accounts. Every edit of the account will get notified to the destination URL.

Setup
To run this project on your local machine, follow these steps:

Clone the project repository:

git clone https://github.com/MadheshKumarVJ/webhookify.git
Move to the project directory:

cd webhookify/webby/
Install the requirements:

pip install -r requirements.txt
Create a superuser:

./manage.py createsuperuser
Provide the required details.

Run migrations:

./manage.py migrate
Run the server:

./manage.py runserver 8000
