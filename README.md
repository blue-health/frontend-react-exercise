# BlueHealth React Exercise

> Welcome to the programming exercise for React Frontend Developers! :)

## Your Task

// TODO

## Get Started

1. Install [node.js](https://nodejs.org/en/) and the [Yarn](https://yarnpkg.com/getting-started/install) package manager.
2. After cloning the repository, run `yarn` in its root to install all dependencies and set up the git hooks.
3. _Optional: Configure VSCode as described in "Editor Setup" below._
4. Start the application using `yarn start`. Happy coding!

_Note: See "Available Scripts" below for more information._

### File Structure

All files should be named in `lower-case-with-dashes.ts`. There is no exception in casing for files holding a component.<br />
TypeScript files (usually `.ts`) using React's JSX syntax should receive a `.tsx` file extension.

The contents of this repo are structured in the following way:

- `.vscode/`: [VSCode](https://code.visualstudio.com/) config
- `build/`: Build artifacts (excluded from version control)
- `src/`: The application's source files
  - `app/`: The app's entry point
  - `components/`: Application-specific React components that do not hook into the application store
  - `i18n/`: Internationalization helpers & translations
  - `models/`: [MobX](https://mobx.js.org) models
  - `screens/`: All application screens accessible via their own route/as part of the navigation hierarchy
  - `theme/`: The UI theme

## Available Scripts

The most important scripts are outlined below. You can find all script definitions in the `package.json`.

### `yarn start`

Launches a development server that runs the application in development mode.

After running this command, navigate to [http://localhost:4200](http://localhost:4200) to view the app in your browser.<br />
The app will automatically reload if you change any of the source files.

### `yarn format`

Runs automated code formatting on all applicable file types.

### `yarn lint`

Lints all applicable files and prints the output.

### `yarn compile`

Dry-runs the TypeScript compiler.<br />
This is especially useful to check whether any types or references broke after a big refactoring.

### `yarn test`

Runs unit tests via [Jest](https://jestjs.io).

Tests are automatically discovered from all `*.spec.{ts,tsx}` files.

### `yarn storybook`

Launches [Storybook](https://storybook.js.org/).

Stories are automatically added from all `*.stories.{ts,tsx}` files.

### `yarn build`

Builds the application.<br />
The build artifacts will be stored in the `build/` directory.

## Editor Setup

We recommend using [VSCode](https://code.visualstudio.com/).

After opening the repo in VSCode, it will ask you if you want to install recommend extensions. For a seamless development experience, we recommend accepting.
