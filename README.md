# :zap: Python Django Crypto

* Python-Django app to fetch and display crypto currency prices from the [Coingecko cryptocurrency API](https://www.coingecko.com/en/api)
* Code from a tutorial by [Pyplane](https://www.youtube.com/channel/UCQtHyVB4O4Nwy1ff5qQnyRw) - see [:clap: Inspiration](#clap-inspiration) below
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/python-django-crypto?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/python-django-crypto?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/python-django-crypto?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/python-django-crypto?style=plastic)


## :page_facing_up: Table of contents

* [:zap: Python Django Crypto](#zap-python-django-crypto)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-do list](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* [Coingecko cryptocurrency API](https://www.coingecko.com/en/api) supplied crypto currency information in JSON format. It is free and does not require an API key
* [Bootstrap starter template](https://getbootstrap.com/docs/4.3/getting-started/introduction/) used in `templates/base.html`

## :camera: Screenshots

![screen print](./img/main.png)
![screen print](./img/coingecko.png)

## :signal_strength: Technologies

* [Python v3](https://www.python.org/) programming language
* [Django v3](https://www.djangoproject.com/) server-side web framework
* [Coingecko cryptocurrency API](https://www.coingecko.com/en/api)
* [Bootstrap v4](https://getbootstrap.com/docs/4.5/getting-started/introduction/) framework
* [requests v2](https://pypi.org/project/requests/) Python HTTP library package
* [Celery v5](https://pypi.org/project/celery/) Distributed Task Queue
* [Redis](https://redislabs.com/) key value store
* [Homebrew v2](https://brew.sh/2019/02/02/homebrew-2.0.0/) - not for Windows - replace with Chocolatey?

## :floppy_disk: Setup

* [Install Python](https://docs.python-guide.org/starting/installation/)
* [Install pip](https://docs.python-guide.org/dev/virtualenvs/#installing-pipenv)
* [Install Django](https://docs.djangoproject.com/en/3.1/howto/windows/) by typing `pip install Django`
* Run `django-admin startproject crypto_proj` to create a new project [ref. docs](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
* Open `crypto_proj` in VS Code
* Run `python manage.py startapp positions` to create Python module
* Add code
* Run `pip freeze` to see list of modules installed. [Ref. Docs](https://pip.pypa.io/en/stable/reference/pip_freeze/)
* Run `python manage.py makemigrations` for changes to models etc.
* Run `python manage.py migrate` to migrate the migration files.
* To add a superuser run `python manage.py createsuperuser --username=joe --email=joe@example.com` [Ref. Docs](https://docs.djangoproject.com/en/3.1/topics/auth/default/) and log into admin panel
* Run `python manage.py runserver` to run server on port 8000. A refresh is needed after any code changes

## :computer: Code Examples

* extract from - tba

```python

```

## :cool: Features

* Django inbuilt packages - admin dashboard

## :clipboard: Status & To-do list

* Status: Incomplete: paused at video 3 - 4.05 while I check Homebrew for Windows - video only shows Mac version
* To-do: check if chocolatey package manager can replace Homebrew which is not for Windows

## :clap: Inspiration

* [Pyplane: Youtube: Django real time application | django channels, celery, redis | part 1 - overview](https://www.youtube.com/watch?v=Ib8UwwnPYsE)
* [Pyplane: Youtube: Django real time application | django channels, celery, redis | part 2](https://www.youtube.com/watch?v=YQRg5Mrg1oY)
* [Pyplane: Youtube: Django real time application | django celery in practice | part 3](https://www.youtube.com/watch?v=DhscKT1t8Vs)
* [Pyplane: Youtube: Django real time application | django celery in practice | part 4](https://www.youtube.com/watch?v=wfVwApNPcHs)

## :file_folder: License

* N/A

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
