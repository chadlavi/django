# Testing out Django

 cf. https://docs.djangoproject.com/en/2.0/intro/

to get the server up, go into this dir and run `python3 manage.py runserver localhost:8080` (sub localhost for whatever, sub port for whatever)

Be sure to copy `djangosite/settings_secret_template.py` to `djangosite/settings_secret.py` and fill in your values for Allowed Hosts (I recommend putting in the machine's IP and localhost as quoted strings).
