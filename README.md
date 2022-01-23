# 19 PWA: Text-Editor

![License](https://img.shields.io/badge/license-MIT-blue)

## Description 

For this project I have worked on the provided starter code to build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

The accepetance crtieria for the task was as follows: 

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

Following image shows the application screenshot. 

![Screenshot](assets/screenshot.png)

## Table of Contents 
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contribute](#contribute)
- [License](#license)

## Installation
This application does not require installation. [Click here](https://herokuapp.com/) to view the application.

## Usage

This application runs online as well as offline.

To install the application to your machine, click on the download icon.

## Features 
This appplication has the following features used in it
- Nodemon
- Express
- Concurrently 
- idb
- babel-loader
- workbox-window
- service-worker 
- InjectManifest
- WebpackPwaManifest
- HtmlWebpackPlugin

## License
This project is released under the [MIT LICENSE](https://img.shields.io/badge/license-MIT-blue)