# LinkUp
 A social media reference application similar to Linktree.
 
# Folders
- mysite: contains settings.py which includes dependencies and base url paths.
- user: has user programs such as migrations folder ,models, views, and forms files.
- links: contains post information such as templates, url paths, migrations, views, and models.
- media: stored media content.

# Things to install (Linux/Unix)
- $ python -m django --version
- $ django-admin startproject mysite
- $ pip install django-crispy-forms
- $ python manage.py migrate *do this if change information in models*

# How to run (Linux/Unix)
- $ python manage.py runserver
