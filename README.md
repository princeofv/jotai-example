# Getting Started

For a long time, Redux had been the leader library of global state management in React. But with the introduction of hooks, I have found that libraries like react-query or useSWR() handle the fetching of data with less boilerplate.

But the simple UI state like side-menu expand, theme, dark-mode, etc. require separate management — in which case a simple global state management library like Jotai (https://github.com/pmndrs/jotai) becomes handy.

git clone https://github.com/princeofv/jotai-example

cd jotai-example

npm install

## Available Scripts

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
