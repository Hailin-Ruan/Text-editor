# Text-editor

## Table of Contents
- [Description](#description)
- [Link](#link)
- [Built With](#built-with)
- [Installation](#installation)
- [Walkthrough](#walkthrough)

## Description

This app is a text editor that runs in the browser and is a single-page application that meets Progressive Web Application (PWA) criteria. User can write notes or code snippets with or without internet.

It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The app will also function offline. Data is stored to an IndexedDB using a package called ```idb``` which features a number of methods that are useful for storing and retrieving data (used by companies like Google and Mozilla).

## Link

<p><a href="https://just-another-text-edit0r-bd37dce72f66.herokuapp.com/">JATE</a></p>

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
* gitignore

## Walkthrough

1. run ```npm install``` to ensure all packages are installed
2. ```npm run start``` to start the application in the backend and serve the client
* Webpack will bundle Javascript files in a ```dist``` folder, it will also generate HTML file, service worker and manifest file.

**Application's functionality and download**
<img width="1440" alt="Screen Shot 2023-10-06 at 1 05 26 am" src="https://github.com/Hailin-Ruan/Text-editor/assets/134148160/19f910bf-fab2-4ebd-8003-cbc3a58848bd">

**Application's manifest.json**
<img width="1428" alt="Screen Shot 2023-10-06 at 12 51 59 am" src="https://github.com/Hailin-Ruan/Text-editor/assets/134148160/ce80ace2-1d32-4f68-a85f-feb2127cf609">

**Application's registered service worker**
<img width="1433" alt="Screen Shot 2023-10-06 at 12 53 50 am" src="https://github.com/Hailin-Ruan/Text-editor/assets/134148160/282cec48-449c-4cd1-a5fa-8d09a541ebf9">

**Application's IndexedDB storage**
<img width="1429" alt="Screen Shot 2023-10-06 at 1 02 03 am" src="https://github.com/Hailin-Ruan/Text-editor/assets/134148160/761a6639-e542-460b-a95a-4ccf68b893ce">
