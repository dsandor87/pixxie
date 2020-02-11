[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)


[![madewithreact](https://img.shields.io/badge/madewith-react-green.svg)](https://reactjs.org/) [![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

# React Unsplash

React Unsplash is photo search webapp made in React which uses Unsplash JSON APIs for photo search. A clone app of  [https://unsplash.com](https://unsplash.com/) the most powerful photo engine in the world. Trying to make the unplash like UI  and add functionality as much as possible. Completed UI screenshots


Main search UI

![Interface](Assets/unsplash_clone.jpg?raw=true "Web App picture")

Donwloading Photos and showing likes

![Interface](Assets/download_photos.jpg?raw=true "Web App picture")

## Prerequisites

You are required to have [Node.js](https://nodejs.org/) installed to run the app locally.

## Getting Started

Install [unsplash-js](https://github.com/unsplash/unsplash-js) ([github](https://github.com/unsplash/unsplash-js))

```
npm i --save unsplash-js
```
## Creating a developer account

To access the Unsplash API, first [register](https://unsplash.com/developers) as a developer.


## Registering your application

Once your account has been registered for the API, log in -> go to the Developers page -> Go to "Your Applications"->  "New Application" and fill in the required details.



SignUp or Login in [Unsplash](https://unsplash.com). Go to API/devlopers ->  Documentation. Then Register your app to get the API key and secret.

## API Usage
Make a new `.env` file and do the following

```
 API_KEY = your_api_key
 API_SECRET = your_api_secret
```

## Usage

```sh
# install all dependency
~/ npm install

# run
~/ npm run dev 
```

## Formatting Code

```sh
~/ npm run format 
```

## Clearing Build

```sh
~/ npm run clear 
```


## Contribution

The devlopement of the App is still in progress. Only some part is implemented. You can help with 
code contribution to add more functionality in the App.

## License

**React Unplash** is available under the **MIT license**. See the [LICENSE](https://github.com/junipdewan/react-unsplash/blob/master/LICENSE.md) file for more info.

## Important 

[Unplash](https://unsplash.com) is a registered trademark. This project is just for learning purposes and should be treated as such.
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
