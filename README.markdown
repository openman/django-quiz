Django Quiz
===========

A pluggable Quiz application for the Django Web Framework.


Installation
------------

1. Add `quiz` to the `INSTALLED_APPS` in your project's `settings.py`

2. Include the `quiz` URLconf in your project `urls.py` like this `url(r'^quiz/', include('quiz.urls')),`

3. Run `python manage.py syncdb` to create the `quiz` models.

4. Start the development server and visit `http://127.0.0.1:8000/admin/` to create a quiz (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/quiz/.