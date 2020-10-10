# Holly-Demo

Deploy Holly to Firebase Hosting.

* [Getting started](#getting-started)

## Getting started
* First, ensure that node.js & npm are both installed. If not, choose your OS and installation method from [this page](https://nodejs.org/en/download/package-manager/) and follow the instructions.
* Next, use your command line to enter your project directory.
* This template comes with a ready-to-use package file called `package-sample.json`. You just need to rename it to `package.json`, then run `npm install` to install all of the dependencies into your project.

You're ready to go! Run any task by typing `npm run task` (where "task" is the name of the task in the `"scripts"` object). The most useful task for rapid development is `watch`. It will start a new server, open up a browser and watch for any SCSS or JS changes in the `src` directory; once it compiles those changes, the browser will automatically inject the changed file(s)!

## Deploy to Firebase
* Go to root folder.
* Open your terminal and run:
	```bash
	$ firebase login
* Provide your email and password and initialize your project.
	```bash
	$ firebase init
* Select Create a new project.
* Select Firebase Hosting.
* Write dist as your public folder and do not overwrite the contents.
* Run the following to depoy:
	```bash
	$ firebase deploy
* View at https://holly-1689.firebaseapp.com/