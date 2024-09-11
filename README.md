# Webpack build tool

## About
A simple project using the basic frontend tools and a webpack build tools

## Setup
- Fork this repository and then git clone the repo into your local director
- cd (change directory) into your created directory.
- Run `npm i` or `npm install` to install all the initial dependencies
- Use `npm start` to start a local development server and then make your changes.
Happpy coding... :)

## NPM scripts
`npm start` to start a local development server
`npm build` to create a production build dist directory.
`npm build:dev` to creat a development build for your application

## Build process
The build uses the index.js as the entry for the application and main.bundle.js as the output. Assets and other dependencies are needed for the application are imported into the index.js. Webpack uses loaders like `sass-loader`, `css-loader` to process these assets so they can be easily used in the browser.