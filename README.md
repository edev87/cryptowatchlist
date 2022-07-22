# CryptoWatchList Web App
The CryptoWatchList Web App allows users to register for an account and will be allowed to save and/or delete their favorite crytpo coins from a watchlist listed under their accoount.

![projectDemoCrypto](https://user-images.githubusercontent.com/57330874/172710963-5eb6a390-bab0-4ca5-93f3-bbda6068752d.gif)


Link to project: [https://crytowatchlist.netlify.app]


## How It's Made:
**Tech used:** React, Tailwind CSS, React SparkLines, React Icons, UseState, UseEffect, Axios, CoinGeckoAPI, User Authentication, Firebase

I created a wireframe for the website to design the UI. The wireframe started off with shapes and placeholders. After creating the shapes and placeholders, I added names to the shapes to identify what components would make the React App. After naming the components I decided what content should go in each component to make my project modular and more easier to manage when handling edits and updates. After filling the components with data, I implemented Tailwind CSS for the styling and adjusted the styles accordingly to my liking.

## Optimizations

I plan to add more colors to the theme context so the user can choose from a variety of theme colors. I will also look into ways to make my site faster such as caching images, or any other data so that my site can load more efficiently. I also plan to add more features to the dashboard to give users more information about the crypto coins that are saved to their watchlist. I also want to add more features for this app and possiblly create a dashboard with more information for the suer to utilize.

## Lessons Learned:
From making this project I learned more about handling data when making API calls and utilizing the React Hooks API. I also learned how to improve my time management skills by making a detailed wireframe before coding my project which made it easier to identify the components and content that would make my react app vs trying to build an application from scratch estimating where the content should go. Making a detailed wireframe also made it easier for me to apply styles, I was able to get an idea of what styles I would re-use throughout code and which styles I would only use once.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

#### `npm install`
#### `npm i axios`
#### `npm i react-icons`
#### `npm i react-sparklines`
#### `npm install -D tailwindcss`
#### `npx tailwindcss init`
#### `npm i firebase`

#### Copy and paste `"./src/**/*.{html,js}"` into the content array inside of tailwind.config.js
```js
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

```
#### Copy and paste inside of index.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
