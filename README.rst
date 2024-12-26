============
django-note
============

django-note is a Django app to conduct web-based note. For each
question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "note" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...,
        "django_note",
    ]

2. Include the note URLconf in your project urls.py like this::

    path("note/", include("django_note.urls")),

3. Run ``python manage.py migrate`` to create the models.

4. Start the development server and visit the admin to create a note.

5. Visit the ``/note/`` URL to participate in the note.
