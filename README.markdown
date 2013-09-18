Django Quiz
===========

A pluggable Quiz application for the Django Web Framework.


Installation
------------

+ Add `quiz` to the `INSTALLED_APPS` in your project's `settings.py`

+ Add an URL entry to your project's `urls.py`, 

for example:

    urlpatterns += patterns('',
        url(r'^quiz/', include('django_quiz.urls')),
    )

