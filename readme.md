Ecom mobility demo.

Install instructions

Either click on the Button and then skip forward to setting up Heroku Connect, or follow the detailed directions below:

1. Get the code from github:

```sh
git clone git@github.com:tsykoduk/ecom-mobilty-demo.git
```

2. Change to the new directory, and then create a Heroku app, and add the correct addons:

```sh
cd ecom-mobilty-demo/
heroku create
heroku addons:add heroku-postgresql:standard-0
heroku addons:add pubnub
```