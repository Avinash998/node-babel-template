
# node-babel-template![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

This is the sample node project which tells about the implementation of babel in your project.

## Installation

### Requirements
* Node 8 or latest
* npm 6 or latest

### Installation
#### Create your project directory 
`$ mkdir project_dir`

`$ cd project_dir`

`$ git clone https://github.com/Avinash998/node-babel-template.git`

`$ npm install`
#### Install in your existing project

`$ npm install babel-cli -D`

`$ npm install babel-preset-env -D`

#### Enviroment Setup
Create a file inside project directory
`$ touch .babelrc`
```javascript
//Include in .babelrc
{ 
 "presets": ["env"]  
 }
```
```javascript
// Add these scripts in package.json
"scripts": {  
	"test": "echo \"Error: no test specified\" && exit 1",  
	"build": "babel src -d lib"  
}
```

## Usage

To build from ES5 to ES6+
`$ npm run build`

## NPM Packages

### devDependencies
* babel-cli
* babel-preset-env

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
