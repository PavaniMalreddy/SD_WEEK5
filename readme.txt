 you need to apply the migrations by running the following command in your project directory:

python manage.py migrate

This command will apply any pending migrations and update your database schema. After running this command, you should see a message indicating that the migrations have been applied.

Run the following command to start the development server:

python manage.py runserver

Access the Hello World JSON response
Open your web browser and navigate to http://127.0.0.1:8000/app/hello/. You should see the JSON response: {"Message": "Hello World!"}.

