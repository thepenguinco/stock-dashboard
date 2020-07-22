# Stock Dashboard

Stock Dashboard is an experimental tool made with ReactJS to display live financial data using financial APIs and explore financial datasets using various tools.  

Planned Tools
- Options Pricing Calculator
- Dataset Analysis and Exploration Tools
- Backtesting on Historical Data

Contributions are welcome.

## Table of Contents

* [Installation](#installation)
* [Basic usage](#create-react-app)
* [Documentation](#documentation)
* [License](#license)

## Installation

### Clone repo

``` bash
# clone the repo
$ git clone https://github.com/coreui/coreui-free-react-admin-template.git

# go into app's directory
$ cd my-project

# install app's dependencies
$ npm install
```

## Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app)

see also:
[CRA docs](https://create-react-app.dev/docs/getting-started)

## CoreUI Admin Template
This project also uses the [CoreUI Free Admin Template](https://github.com/coreui/coreui-free-react-admin-template/tree/master/src)

## Basic usage

``` bash
# dev server with hot reload at http://localhost:3000
$ npm start
```

Navigate to [http://localhost:3000](http://localhost:3000). The app will automatically reload if you change any of the source files.

### Build

Run `build` to build the project. The build artifacts will be stored in the `build/` directory.

```bash
# build for production with minification
$ npm run build
```

## Documentation

### Project File Structure

```
├── public/          #static files
│   └── index.html   #html template
│
├── src/             #project root
│   ├── assets/      #assets - js icons object
│   ├── containers/  #container source - template layout
|   │   ├── _nav.js  #sidebar config
|   │   └── ...      
│   ├── scss/        #user scss/css source
│   ├── views/       #views source
│   ├── App.js
│   ├── App.test.js
│   ├── polyfill.js
│   ├── index.js
│   ├── routes.js    #routes config
│   └── store.js     #template state example 
│
└── package.json
```