# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


### GitHub Access Key
if you see an error with 'bad credentials' in craphql api response.
Please update 'BEARER_TOKEN' in Constants.js filw with your key.

#### How to get new Github Access key?
github > settings > developer settings > personal access token > generate new token
add any note and selects the required options and click on 'Generate Token'.
copy the token

## Components

#ErrorBoundary component
If there is any exection in the child component. it will be cought in ErrorBoundary component in production mode.
This will display custom message and error stack instead of showing errors on screen

### CMS
All the content showed on the screen is taken from this cms folder.This helps in 
* Easy Content Management
* Swith the content to any CMS tool

### Common Components
Components like buttons, errormessaging, spinnets, accordians should be placed here. this helps in 
* code- reusability
* It can be used across applications if saperated into different module

### Apllo client v3

More details about apollo client with react can be found here https://www.apollographql.com/docs/react/

### React Testing Library

More details about this way of testing can be found in https://testing-library.com/docs/react-testing-library/intro/

# screenshots

![first image](https://github.com/piyush02031/github-project/blob/main/screenshot.JPG)
![second image](https://github.com/piyush02031/github-project/blob/main/screenshot2.JPG)
![tests](https://github.com/piyush02031/github-project/blob/main/tests.JPG)

