django-all-access
===================

django-all-access is a reusable application for user registration and authentication
from OAuth 1.0 and OAuth 2.0 providers such as Twitter and Facebook.

This version is modified to handle VUMC Ping OAuth2 authentication.
The original repository available at https://github.com/mlavin/django-all-access .

Installation
------------------------------------

It is easiest to install django-all-access from PyPi using pip::

    pip install git+https://github.com/ComputationalMedicineLab/django-all-access.git

django-all-access requires Python 2.7 or 3.3+ along with the following Python
packages::

    django>=1.8
    pycrypto>=2.4
    requests>=2.0
    requests_oauthlib>=0.4.2
    oauthlib>=0.6.2
    PyJWT==1.6.0
