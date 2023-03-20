# social-network-api

## Description
The application is a web text editor where you can write notes or code with or without internet connection.  The integrated sevice worker and Cache ensure that the application will remain functional even without internet.  You can also download/ install the application for use.



## Table of Contents
* [Links](#links)

* [Installation](#installation)

* [Usage](#usage)

* [License](#license)

* [Code](#code)

* [Tests](#tests)

* [Questions](#questions)

## Links

GitHub URL:  https://github.com/rypab4/Text-Editor
Heroku URL: https://text-editor-2023-again.herokuapp.com/
## Installations 

To install necessary dependencies, run the following command if running from github and on local:

```
npm install
    "@babel/core": "^7.15.0",
    "@babel/plugin-transform-runtime": "^7.15.0",
    "@babel/preset-env": "^7.15.0",
    "@babel/runtime": "^7.15.3",
    "babel-loader": "^8.2.2",
    "css-loader": "^6.2.0",
    "express": "^4.17.1"
    "html-webpack-plugin": "^5.3.2",
    "http-server": "^0.11.1",
    "style-loader": "^3.2.1",
    "webpack": "^5.51.1",
    "webpack-cli": "^4.8.0",
    "webpack-dev-server": "^4.0.0",
    "webpack-pwa-manifest": "^4.3.0",
    "code-mirror-themes": "^1.0.0",
    "idb": "^6.1.2",
    "nodemon": "^2.0.4",
    "workbox-webpack-plugin": "^6.2.4"

```


## Usage

1.  If running using local server with the github repo, npm start.  Otherwise go to https://text-editor-2023-again.herokuapp.com/

2.  Going through the github repo and npm start will create a database, editor, header, install, and main bundle.  A manifest bundle will also be created.
![alt text](/README_imgs/manifest.png)

3.  The text editor will look like the following:
![alt text](/README_imgs/JATE_first_image.png)

4.  The text editor also shows the application's registered service worker.
![alt text](/README_imgs/SW.png)

5.  The text editor also will have an indexed database
![alt text](/README_imgs/indexDB.png)


## License
    
none


## Questions
If you have any questions about the repo, open an issue or contact me directly at rypab4@gmail.com.  You can find my work at https://www.github.com/rypab4.