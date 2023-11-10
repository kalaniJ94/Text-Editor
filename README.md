# Text-Editor

## Description

This challenge was an interesting look into the world of PWAs, and the powerful tools they offer for web developers. The technology and techniques were a challenge to learn, but I look forward to using them in the future. The ability to turn any app into an offline downloadable app is an interesting idea, even compared to similar tools like React Native.  

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [## How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Usage

(WHen using VScode to open the app.)

When using this app, first open the integrated terminal and install any necessary packages to run. After doing so, your package.json should look like so: 
"scripts": {
    "start:dev": "concurrently \"cd server && npm run server\" \"cd client && npm run dev\"",
    "start": "npm run build && cd server && node server.js",
    "server": "cd server nodemon server.js --ignore client",
    "build": "cd client && npm run build",
    "install": "cd server && npm i && cd ../client && npm i",
    "client": "cd client && npm start",
    "herokuPostBuild": ""
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.17.1",
    "if-env": "^1.0.4",
    "mini-css-extract-plugin": "^2.7.6"
  },
  "devDependencies": {
    "concurrently": "^5.2.0",
    "nodemon": "^2.0.4"
  }

If you are missing any packages, install them using "npm run install". Use the "npm run start:dev" command to begin the start script, which will run several servers concurrently. You will find that a "dist" folder within your file structure has been created for you. Right click on the "index.html" file within this folder, and run with live server. 

Upon starting the app, you will be able to use the Text Editor in your browser, or install the app for offline use. 


## Credits

Credit for helping finish this challenge go to Alexa Lester (https://github.com/alester77) and Colton Laidig (https://github.com/coltondane)
## License

MIT License

Copyright (c) 2023 Kalani Jones.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## How to Contribute

If you've like to contribute to this project, please reach out! We are incredibly proud of the work, and also of the numerous future opportunities for future features it could hold.

Before you reach out, please be familiar with the Contributor Covenant and the code of conduct within.

Link to GITHUB repo can be found here: https://github.com/kalaniJ94/Text-Editor

## Tests

No tests are currently available for this application. 