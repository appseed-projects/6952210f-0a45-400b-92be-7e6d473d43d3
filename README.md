# Datta Able Django

Open-source **Django Dashboard** generated by `AppSeed` op top of a modern design. **[Datta Able](https://appseed.us/generator/datta-able/)** Bootstrap Lite is the most stylised Bootstrap 4 Lite Admin Template, around all other Lite/Free admin templates in the market. It comes with high feature-rich pages and components with fully developer-centric code. Before developing Datta Able our key points were performance and design.

<br />

> Context:

- Built with [Datta Able Generator](https://appseed.us/generator/datta-able/)
- Timestamp: `2022-05-19 14:09`
- Build ID: `6952210f-0a45-400b-92be-7e6d473d43d3`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- UI-Ready app, `SQLite Database`, Django Native ORM
- `Session-Based authentication`, Forms validation

<br />

![Datta Able - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168842521-ec98ecd5-489c-4a13-a9aa-0d47201d63de.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

> **Step 2** - Edit `.env` and remove or comment all `DB_*` settings (`DB_ENGINE=...`). This will activate the `SQLite` persistance. 

```txt
# True for development, False for production
DEBUG=True

# Deployment SERVER address
SERVER=.appseed.us

# For MySql Persistence
# DB_ENGINE=mysql                  <-- REMOVE or comment for Docker
# DB_NAME=appseed_django           <-- REMOVE or comment for Docker  
# DB_HOST=localhost                <-- REMOVE or comment for Docker 
# DB_PORT=3306                     <-- REMOVE or comment for Docker
# DB_USERNAME=appseed_django_usr   <-- REMOVE or comment for Docker
# DB_PASS=pass                     <-- REMOVE or comment for Docker

```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:85` in your browser. The app should be up & running.

<br />




## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/6952210f-0a45-400b-92be-7e6d473d43d3.git
$ cd 6952210f-0a45-400b-92be-7e6d473d43d3
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like bold elements and beautiful websites, **Datta Able** is the most stylish Bootstrap 4 Admin Template compare to all other Bootstrap admin templates. It comes with high feature-rich pages and components with fully developer-centric code. 

- 👉 [Django Datta PRO](https://appseed.us/product/datta-able-pro/django/) - product page
- 👉 [Django Datta PRO](https://django-datta-able-pro.appseed-srv1.com) - LIVE Deployment

<br >

![Datta Able PRO - Django](https://user-images.githubusercontent.com/51070104/167877944-d13afec9-4171-4c5e-97df-3ee643feecdb.jpg)

<br />

---
Datta Able Django - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
