# React Component State Update Issue

This repository demonstrates a common error in React components where the state is not updated correctly based on changes in props. The `bug.js` file contains a component with the incorrect lifecycle method, `componentWillMount`, which is used for updating the state. The `bugSolution.js` file shows the corrected version that uses the correct lifecycle method, `componentDidUpdate`, to update the state appropriately.

## Setup

Clone the repository and run `npm install` to install the dependencies.

## Running the code

You can run the code with `npm start`. The solution is provided in the `bugSolution.js` file.