# React_prac-01

Create React app from scratch

Create a new directory for react app.
Initialize your project with npm init.
In project folder add public and src folders.
Also add .gitignore file here mention the files which you don't want to be included for ex. node_modules.
Inside public directory add index.html
public directory will handle all static files.
index.html is a file which will render your app which will be displayed on browser.


Babel:

babel-core is the main babel package — We need this for babel to do any transformations on our code. babel-cli allows you to compile files from the command line. preset-react and preset-env are both presets that transform specific flavors of code — in this case, the env preset allows us to transform ES6+ into more traditional javascript and the react preset does the same, but with JSX instead.

In the project root, create a file called .babelrc. Here, we’re telling babel that we’re going to use the env and react presets.

Webpack
Now we need to acquire and configure Webpack. We’ll need a few more packages, and you’ll want to save these as dev dependencies: npm install --save-dev webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader.

Webpack uses loaders to process different types of files for bundling. It also works easily alongside the development server that we’re going to use to serve our React project in development and reload browser pages on (saved) changes to our React components. In order to utilize any of this though, we’ll need to configure Webpack to use our loaders and prepare the dev server.

Create a new file at the root of the project called webpack.config.js. This file exports an object with webpack’s configuration.

React
First, we’ll need to get two more packages: react and react-dom Go ahead and save those as regular dependencies.

Your final project structure should look like the following, unless you changed some names along the way:

.
 public
| index.html
 src
|  App.css
|  App.js
| index.js
.babelrc
.gitignore
package-lock.json
package.json
webpack.config.js

In App.css add css as per your need. and then import path in App.js
index.js is the main page where our project will be started.


ScreenShot:
![Screenshot from 2023-03-01 11-36-59](https://user-images.githubusercontent.com/122339608/222058696-5df96c48-ffdd-4f88-aa66-2f468359c143.png)

