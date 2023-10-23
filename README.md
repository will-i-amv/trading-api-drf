# Trading API - DRF

A trading API implemented with Django REST Framework, to simulate the functionality of a site like [TradingView](https://www.tradingview.com/)

[![Built with Cookiecutter Django](https://img.shields.io/badge/built%20with-Cookiecutter%20Django-ff69b4.svg?logo=cookiecutter)](https://github.com/cookiecutter/cookiecutter-django/)
[![Black code style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

## Setup

### Local setup

- Clone this repo:

      $ git clone https://github.com/will-i-amv/trading-api-drf

- Create and activate your virtual environment:

      $ python -m venv env
      $ source env/bin/activate

- Install dependencies:

      $ pip install -r requirements/local.txt

- Apply initial migration:

      $ python manage.py migrate

- Create a **superuser account**:

      $ python manage.py createsuperuser

- Run development server:

      $ python manage.py runserver

## Run Checks

### Type checks

Running type checks with mypy:

    $ mypy trading_api

### Test coverage

To run the tests, check your test coverage, and generate an HTML coverage report:

    $ coverage run -m pytest
    $ coverage html
    $ open htmlcov/index.html

#### Running tests with pytest

    $ pytest

## License

MIT License.
