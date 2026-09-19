Water Plant Monitoring Demo (Django)
-----------------------------------

Requirements:
  - Python 3.10.x
  - Install dependencies: pip install -r requirements.txt

Run:
  python manage.py migrate
  python manage.py createsuperuser   # optional
  python manage.py runserver

Open http://127.0.0.1:8000/ to view the dashboard.

Notes:
  - Demo sensor values auto-update randomly every 3 seconds.
  - The plant diagram image (internship.jpg) is included in monitor/static/monitor/plant_layout.jpg
