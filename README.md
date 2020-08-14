## Toy Robot - Sean Thompson

This is the React version of my crack at the popular Toy Robot coding challenge doing the rounds around the Melbourne tech scene.

The original spec for the challenge is in the PROBLEM.md document in the root of this repo. It says an interface isn't required but being an interface dev I've chosen to implement one anyway as well as extend it a little with a header and a command history etc..

This is set up as a standard unejected [Create React App](https://github.com/facebook/create-react-app). which can be run in the browser.

Stack:

- React (obvs)
- TypeScript
- Styled Components
- Jest
- React Testing Library
- ESLint (configured to lint TS)
- Prettier
- immutability-helper

No state management for this one. I could have implemented Redux but the size of the project doesn't warrant inflicting that experience upon myself, so just local state.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn lint`

ES Lints all the source files, both JS and TS. Uses the popular airbnb config which is pretty strict.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
