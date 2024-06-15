Django CRM
Dependencies:
To start this project, first create virtualenv using python3. You need to have venv module installed.<br> Example command:

<code>python3 -m venv env</code><br>
To activate your local environment use this command (Windows):<code>env\Scripts\activate.bat</code><br>
Now you can install all the requiremenets for the project.<br>
 This should work:<code>py -m pip install -r requirements.txt</code><br>
Running the website:
To run the website do as follows:

Activate your local environment (if it is not activated already):
<code>env\Scripts\activate.bat</code><br>
Apply migrations:<code>python3 manage.py migrate </code><br>
Create superuser:<code> py manage.py createsuperuser</code><br>

Run the server: <code>py manage.py runserver</code><br>

By default, your website should be hosted at: http://127.0.0.1:8000/.
Use login provided when creating superuser.

Additional tools:
If you want to exit local environment, then just put:

<code>deactivate</code>
