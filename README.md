## Example javascript project

## First steps

1. Install Node + NPM with your favorite package manager.
2. Install project dependencies with: __npm install__

## Commands

### npm start

Starts webserver running the application in localhost:3000. This usually also monitors any changes in the source files and updates if any changes are detected. This call doesn't return until server is killed.

### npm test

Runs unit tests

### npm run build

Builds the project. Right now output is in build/ folder, but this should probably be renambed to dist/

### npm run clean

Cleans build directory

### npm run integration-test

Runs integration tests, right now it just runs same tests as __npm test__

### npm run version

Prints version