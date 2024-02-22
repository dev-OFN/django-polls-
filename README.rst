===
Polls
===

Polls is a Django app to conduct web-based polls. for each question, 
visitors can choose between a fixed number of answers 

detailed Documentation in the "docs" directory

Quick start
------------

1. Add "polls" to your INSTALLED_APPS setting like this::
    INSTALLED_APPS=[
        ...,
        "polls",
    ]

2. Include the polls URLconf in your project urls.py like this::
    path("polls/", Include("polls.urls")),


3.  Run'' python manage.py migrate''  to create polls models

4.  Start development server visit http:/127.0.01:8000/admin/ to create polls (you'll need admin app enabled)

5.  visit http:/127.0.01:8000/polls/to participate in the polls