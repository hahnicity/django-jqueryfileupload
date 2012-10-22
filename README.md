django-jqueryfileupload
=======================

Django app for handle multiple file uploads via jquery-file-upload plugin.

[![Build Status](https://travis-ci.org/witoi/django-jqueryfileupload.png?branch=master,develop)](https://travis-ci.org/witoi/django-jqueryfileupload)


## Requirements

* Django>=1.3

## Testing

    python setup.py test

## Configuration

    INSTALLED_APPS += ('jqueryfileupload',)

    urlpatterns += (r'^fileuploader/', include('jqueryfileupload.urls'))
