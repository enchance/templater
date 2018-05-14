Let’s get nginx to speak to the "hello world" test-01.py application.

    uwsgi --socket :8001 --wsgi-file test-01.py


**Sauce**:

- [nginx and uWSGI and test.py](http://uwsgi-docs.readthedocs.io/en/latest/tutorials/Django_and_nginx.html#nginx-and-uwsgi-and-test-py)