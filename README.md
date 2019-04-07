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


# Demo
## Registering step
![registering step](https://user-images.githubusercontent.com/42479575/55684668-b2f2a880-596f-11e9-8a17-b02b8ba486c0.png)

## Confirmation link and key
![confirmation link and key](https://user-images.githubusercontent.com/42479575/55684677-d1f13a80-596f-11e9-8f48-f8ac444c433c.png)

## Then, Login
![login step](https://user-images.githubusercontent.com/42479575/55684691-0664f680-5970-11e9-8c09-4a593aa0bb57.png)

## List of all users and recent added user.
![user added to the user list](https://user-images.githubusercontent.com/42479575/55684695-11b82200-5970-11e9-833e-85217f11d165.png)
