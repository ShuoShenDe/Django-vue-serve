# This project is created for integrate vue server and Django framework

## Step 1: install Django and vue
You should run them on

## Step 2: download dependencies of Vue and requirements of Django

## Step 3: integrate vue and Django when in development mode
![vue reference for development and production mode](https://dev.to/saymy__name__/hooking-up-django-and-vue-js-19j3)
Especially, when you use Windows system, you should set
```in vue.config.js
...
publicPath: "http://127.0.0.1:8080/"
...
config.devServer
      // the first 3 lines of the following code have been added to the configuration
      .public("http://127.0.0.1:8080/")
...
```

## Step 4: run vue server in frontend folder
```use npm
npm run serve
```
## Step 4: run Django server
```use python
python manage.py runserver
```
Now navigate to http://127.0.0.1:8000, and you should see the Vue App instead of django’s default page. Cool eh? This means that the VueJs applications is being rendered through Django.
