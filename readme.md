# This project is created for integrate vue server and Django framework

## Step 1: integrate vue and Django when in development mode
![vue reference for development and production mode](https://vuejs.org/v2/guide/installation.html#Development-vs-Production-Mode)


## Step 2: integrate vue and Django when in development mode
![configure reference](https://medium.com/@rodrigosmaniotto/integrating-django-and-vuejs-with-vue-cli-3-and-webpack-loader-145c3b98501a)(https://dev.to/saymy__name__/hooking-up-django-and-vue-js-19j3)

## Step 2: run vue server in frontend folder
```use npm
npm run serve
```

Then, run Django
```use python
python manage.py runserver
```

Now navigate to http://127.0.0.1:8000, and you should see the Vue App instead of django’s default page. Cool eh? This means that the VueJs applications is being rendered through Django.
