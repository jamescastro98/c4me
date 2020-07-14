### `npm install`

Install all dependencies in the respective node modules folder.


### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### Project Hierarchy

Each individual page is made up of a bunch of components. pages can be found in src/pages.
The components that make up these pages are in src/pages/components. From there, you will see
loose files containing the JSX for rendering the components. You will also find a static folder - this contains all our static images, css and js.
We do utilize client side validation, but this will also be implemented server side - this way no one can inject code.

The app.js file contains the switches for each individual page. If a user is on a given valid url, we will render it. Else - 404 error message. Plain and simple.

### Bugs

Because the workspace is so big, you may encounter issues with file watching on Ubuntu. Run clear.sh as root, and it should clear this up.
