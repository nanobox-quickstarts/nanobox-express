# Express.js on Nanobox
This is the companion application for the [Express.js: Getting Started](https://guides.nanobox.io/expressjs/) guide on [guides.nanobox.io](https://guides.nanobox.io) and is pre-configured and ready to run on [nanobox](https://desktop.nanobox.io/)!

## Up and Running

``` bash

# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-expressjs.git

# cd into the expressjs app
cd nanobox-expressjs

# build the code
nanobox build

# start the dev environment
nanobox dev start

# add a convenient way to access your app from the browser
nanobox dev dns add expressjs.nanobox.dev

# console into the dev environment
nanobox dev console

# run the app
/app $ npm start
```

Visit the app from your favorite browser at: `expressjs.nanobox.dev:8080`

### Now What?
For more details about how this works or for more advanced topics related to running Express.js applications on nanobox visit [guides.nanobox.io/expressjs/](https://guides.nanobox.io/expressjs/)
