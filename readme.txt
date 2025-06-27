Startup Launchpad
=================

A Django project powered by ASGI and Daphne.

Setup Instructions
------------------

1. Navigate to the project folder:

   cd startup_launchpad

2. Create and activate a virtual environment:

   On Windows:
   python -m venv venv
   venv\Scripts\activate

   On macOS/Linux:
   python3 -m venv venv
   source venv/bin/activate

3. Install dependencies:

   pip install -r requirements.txt

4. Apply migrations:

   python manage.py migrate

5. Start the server with Daphne:

   daphne startup_launchpad.asgi:application

Access the App
--------------

Once running, open your browser and go to:

   http://127.0.0.1:8000/

