# Crown Sterling Front End Engineering Challenge

Welcome, and thank you for taking the time to complete the Crown Sterling take-home challenge.

You will have 48 hours to complete the assignment. Once you have completed your solution, please reply with a link to a github repository and instructions on how to install / run the application

The goal of this challenge is to build out a "Movie Awards 2021" interactive ballot. Please clone this repository and submit it once you are finished.

Here are the rules of this challenge.. you must:

 1) Build an application that displays a list of categories and nominees. Please follow the design in the wireframe below. Run `yarn start` to start the application.
 2) Run `yarn backend` to start the server and get access to API methods such as `getBallotData`. Use the React `useEffect` hook to fetch the ballot data from the provided API, and save it to state by using the React `useState` hook.
 [useEffect Documentation](https://reactjs.org/docs/hooks-effect.html)
 [Fetch API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
[useState Documentation](https://reactjs.org/docs/hooks-state.html)
 3) When you click on a nominee, we should highlight the nominee card and save the selections using the React `useState` hook. A user can only select one nominee per category, and we should be able to see all of their selections highlighted. The selected nominee card should follow the style guides below.
 4) Make the layout responsive with at least one breakpoint (your choice as to how it looks on a smaller screen width).
 5) Once the user is finished making their selections, they can click on a submit button that displays a results modal screen. A user can dismiss the modal by clicking on the close button (follow the wireframe below).

## Requirements:
 1) All navigation should happen in the same page
 2) Demonstrate use of React hooks
 3) Demonstrate knowledge of component modularization
 4) Utilize CSS to create the layout of the page. Add hover styles to the items the user is interacting with.
 5) Create components as you feel is best suited for your solution

![Ballot Wireframe](src/take-home-wire.jpg?raw=true "Ballot Wireframe")
![Ballot Success Modal Wireframe](src/take-home-success.jpg?raw=true "Ballot Success Modal Wireframe")


Remember, this is a competition. Go above and beyond to create something beautiful. Any additional tools, packages or libraries can be used by you.

See /Components/Ballot.js for your code. Feel free to make more files or directories as you see fit.

## Bonuses
2) Make it pretty.
3) Make it accessible
4) Add unit tests

## Styling Guidelines

Your style is your own. Make it cohesive, from color choice to font.

Good luck and if you have questions, please reach out to us at mbeurmen@crownsterling.io

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn backend`

Starts the server which allows the user to access the ballot API.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
