# Authentication Assignment

## Applied authentication features via Django-REST framework

## for installing dependencies and testing <pre><code>pip3 install -r requirements.txt </code></pre>
## Then migrate the database by <pre><code>python manage.py makemigrations</code></pre>
## afterthat                    <pre><code>python manage.py migrate</code></pre>
## and                          <pre><code>python manage.py migrate --run-syncdb</code></pre>
## Run the local server by <pre><code>python manage.py runserver</code></pre>
## For testing purpose <br>
    Admin name: zilani
    password: django12

* or create a superuser by: <pre><code>python manage.py createsuperuser</code></pre>

### Register a user by this endpoint ...
<pre><code>http://127.0.0.1:8000/api/vi/rest-auth/registration/</code></pre>
### Login a user by this endpoint ...
<pre><code>http://127.0.0.1:8000/api/vi/rest-auth/login/</code></pre>
### Logout route
<pre><code>http://127.0.0.1:8000/api/vi/rest-auth/logout/</code></pre>
### View and check all users from this route/endpoints...
<pre><code>http://127.0.0.1:8000/api/vi/users/</code></pre>
