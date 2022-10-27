# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

### `Structure Folder/File Advanced`
# src
# __assets
# ____global.css
# ____logo.svg
# __components
____form
      __tests__
________Checkbox.test.js
________FormInput.test.js
________FormSelect.test.js
________RadioButton.test.js
______Checkbox.js
______FormInput.js
______FormSelect.js
______RadioButton.js
____ui
      __tests__
________Button.js
________ButtonGroup.js
________Dropdown.js
________Modal.js
______Button.js
______ButtonGroup.js
______Dropdown.js
______Modal.js
__context
    __tests__
______AnalyticsContext.test.js
____AnalyticsContext.js
__data
____configValues.json
____constants.js
____defaultTodo.json
__features
____authentication
______components
				__tests__
__________LoginForm.test.js
__________SignupForm.test.js
________LoginForm.js
________SignupForm.js
______hooks
				__tests__
__________useLogin.test.js
__________useSignup.test.js
__________useVerifyPassword.test.js
________useLogin.js
________useSignup.js
________useVerifyPassword.js
______services
				__tests__
__________getUser.test.js
__________login.test.js
__________signup.test.js
________getUser.js
________login.js
________signup.js
______index.js
____projects
______components
______services
______index.js
____settings
______components
				__tests__
__________SettingForm.test.js
________SettingForm.js
______context
______hooks
______services
______index.js
____todos
______assets
______components
______context
______services
______index.js
__hooks
    __tests__
______useFetch.test.js
______useLocalStorage.test.js
____useFetch.js
____useLocalStorage.js
__layouts
    __tests__
______Navbar.test.js
______PageContainer.test.js
______Sidebar.test.js
____Navbar.js
____PageContainer.js
____Sidebar.js
__lib
    __tests__
______fetch.test.js
____fetch.js
__pages
____Home.js
____Login.js
____Settings.js
____Signup.js
____Projects.js
__services
    __tests__
______analytics.test.js
____analytics.js
__utils
    __tests__
______formatCurrency.test.js
______formatDate.test.js
____formatCurrency.js
____formatDate.js
__App.js
__App.test.js
__index.js
__reportWebVitals.js
__setupTests.js