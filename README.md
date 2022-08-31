# Node-NPM-steps

* Create a directy and use npm init to initialize npm inside the project folder
* Create a javascript file (e.g. index.js) within the project folder

### Creating a Module
* Create another javascript file (e.g. Module.js)
* Create the program/function and assign it to ```module.exports```

### Using the Module
* Import the module within the original javascript file using ```const module_name = require('./module_name.js')```
* Utilize the module_name with the function or operation tied with it
* Within the terminal, use ```npm i 'npm_package'``` to install an npm to utilize within your node project
* In VSCode, create a .gitignore file and list ```node_modules``` within it to prevent node dependencies from pushing up to github

## Setting up a Repo that uses Node Packages
* Fork and clone the repo
* Within the cloned folder terminal, run ```npm i``` to install the dependencies
* Open the files within VSCode and begin to program
* Ensure that .gitignore is present and that ```node_modules``` is listed within it