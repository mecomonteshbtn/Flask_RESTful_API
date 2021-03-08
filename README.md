# Flask_RESTful_API

Why flask?
 - Easy to get started 😊
 - Great for building Rest APIs and microservices.
 - Used by big companies like Netflix, Reddit, Lyft, Et cetera.
 - Great for building APIS for machine learning applications.
 - Force is strong with this one 😉

Who is this series for?
 - Beginners with basic Python knowledge who wants to build cool apps.
 - Experienced flask developers who have been working with flask `SSR` (Server Side Rendering).

## First of all install `pipenv`
using command

```
pip install --user pipenv
```

`Pipenv` is used to create a `virtual environment` which isolates the python packages you used in this project from other system python packages. So, that you can have a different version of same python packages for different projects.

Now, let's install `flask` using `pipenv`
```
pipenv install flask
```
This will create a new virtual environment and install flask. This command will create two files `Pipfile` and `Pipfile.lock`.

Pipfile contains the packages that are required for your application. As you can see `flask` is added to `[packages]` list. This means when someone downloads your code and runs `pipenv install`, `flask` gets installed in their system. Great, right?

If you are familiar with `requirements.txt`, think `Pipfile` as the `requirements.txt` on steroids.


Flask is so simple that you can create an API using a single file. (But you don't have to 😅)

Create a new file called `app.py` where we are gonna write our Flask Hello World API. Write the following code in `app.py`
