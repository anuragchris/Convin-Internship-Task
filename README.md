Steps to Execute the project

<b> Step 1 </b>

Install requirements from requirements.txt

    pip install -r requirements.txt
  
<b> Step 2 </b>

Clone the repository

    git clone git@github.com:anuragchris/Convin-Internship-Task.git
    
<b> Step 3 </b>

    Login to https://console.developers.google.com, create your own google calendar api credentials.

<b> You need to rename your credetials.json file as "client_secret.json" </b>

<b> Step 4 </b>

After replacing the credentials file in project folder , Go to the Project folder and run Command Prompt. Now run the following commands : 

    ```bash
    cd {{Your current directory location (Copy-Paste it from the directory bar)}}
    
    python manage.py makemigrations
    
    python manage.py migrate
    
    python manage.py runserver

    ```
    
 
<b> Step 5 </b>

Now open your Preferd Browser and enter the following url in searchbar.

    http://localhost:8000/rest/v1/calendar/init/
    