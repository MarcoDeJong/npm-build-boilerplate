# npm-build-boilerplate

A collection of packages that build a website using `npm scripts`.

* [Using in your project](#using-in-your-project)
* [Need help?](#need-help)

## Using in your project
* First, ensure that node.js & npm are both installed. If not, choose your OS and installation method from [this page](https://nodejs.org/) and follow the instructions.
* Next, use your command line to enter your project directory.
  * If this a new project (without a `package.json` file), start by running `npm init`. This will ask a few questions and use your responses to build a basic `package.json` file. Next, copy the `"devDependencies"` object into your `package.json`.
  * If this is an existing project, copy the contents of `"devDependencies"` into your `package.json`.
* Now, copy any tasks you want from the `"scripts"` object into your `package.json` `"scripts"` object.
* Finally, run `npm install` to install all of the dependencies into your project.

You're ready to go! Run any task by typing `npm run task` (where "task" is the name of the task in the `"scripts"` object). The most useful task for rapid development is `npm start`. It will start a new server, open up a browser and watch for any CSS or JS changes in the `src` directory; once it compiles those changes, the browser will reload.

## Need help?
Feel free to [create an issue](http://github.com/marcodejong/npm-build-boilerplate/issues)

Thanks go out to Damon Bauer for [his version](https://github.com/damonbauer/npm-build-boilerplate)
Thanks go out to the guys at Voorhoede for [their recipes] (https://github.com/voorhoede/front-end-tooling-recipes)