# Django & Vue Canary Take Home

*[Assignment Details](https://github.com/drews256/python-take-home)*

## Local Setup
*I wrote these using MacOS Catalina 10.15.7 using: *
- Python 3.9.10 
- Django 4.0.3
- Node v16.14.0
- Yarn 1.22.17
- @vue/cli 5.0.4

```
# I personally use venv
$ python3 -m pip install -r requirements.txt

# Installs for Vue
$ cd frontend
$ yarn install
```

### Run Django Server:
```
$ python3 manage.py runserver
```
Backend running on [localhost:8000](http://localhost:8000)

### Serve Vue Front End
```
$ cd frontend
$ yarn serve
```

In this current implementation, Vue is running as a [Single-Page App (SPA)](https://vuejs.org/guide/extras/ways-of-using-vue.html#single-page-application-spa), so both for local dev make sure to run the django server in one shell and serve vue in another.