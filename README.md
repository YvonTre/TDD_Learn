# TDD_Learn
> A simple to-do list app using django framework with TDD method.

## basic setup
```bash
# install dependencies
$ pip install -r requirements.txt

# start server
$ python manage.py runserver

# perform all functional tests
$ python manage.py test functional_tests

# perform sigle functional test
$ python manage.py test functional_tests.FUNCTIONAL_TEST_NAME

# perform all unit tests
$ python manage.py test lists/tests

# perform single unit test
$ python manage.py test lists/tests.UNIT_TEST_NAME

# deploy the site using fabric
$ cd deploy_tools
$ fab deploy:host=YOUR_DEPLOYMENT_DOMAIN_NAME
