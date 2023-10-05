# Text-editor

## Table of Contents
- [Description](#description)
- [Built With](#built-with)
- [Installation](#installation)
- [Walkthrough](#walkthrough)

## Description

This app is a text editor that runs in the browser and is a single-page application that meets Progressive Web Application (PWA) criteria. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The app will also function offline. Data is stored to an IndexedDB using a package called ```idb``` which features a number of methods that are useful for storing and retrieving data (used by companies like Google and Mozilla).

## Built with

<p><a href="https://nodejs.org/">Node.js</a></p>
<p><a href="https://www.npmjs.com/">NPM</a></p>
<p><a href="https://www.npmjs.com/package/express">Express.js</a></p>
<p><a href="https://webpack.js.org/">Webpack</a></p>
<p><a href="https://babeljs.io/">Babel</a></p>

## Installation

Please install the following if you have not installed:
* Express: ^4.17.1
* Nodemon: ^2.0.9

Add these files:
* package.json (by running npm init)
* gitignore (to ignore node_modules)

## Walkthrough

1. run ```npm install``` to ensure all packages are installed
2. ```npm run start``` to start the application in the backend 