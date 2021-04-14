# Sample Heroku Deployment for Django

<a href="https://www.buymeacoffee.com/thedudetech"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a pizza&emoji=🍕&slug=thedudetech&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>

## Introduction

Sample with already predefined procedures and files needed.

## Installation

1. Ensure that you have connected  your GitHub account as a deployment pipeline
2. Push your repository code having Django, 
otherwise if the repo is empty Heroku will complain.
3. collect static to work you need to use whitenoise and create static directory
with .git-keep

   Reference: https://devcenter.heroku.com/articles/django-assets

4. We use dj-database-url to parse env variable in order to use Heroku's
PG Database, part of the stack pack

   Reference: https://github.com/jacobian/dj-database-url

## Live testing

You can use this url to test the https://still-plateau-60549.herokuapp.com/admin/
instance.

Credentials:

user: root

pass: Gm4JTT5V6L9cF8g

(randomly generated)

Don't change the password, please or

![I will found your - meme](https://i.imgflip.com/4u66uw.jpg)


## Useful tools

- https://michaeldyrynda.github.io/readme-generator/

- https://choosealicense.com/
