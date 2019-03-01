This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## MVP Project Description

-This project is meant to provide a way to track delays of public transit over time using the One Bus Away API.
-Currently, the One Bus Away app allows a user to access real time transit vehicle location data in combination with transit schedules and other related data. 
-The app does not provide historical (non real-time) data, nor do any of the provided suite of APIs
-Since historical data is unavailable, it is not possible to analyze trends in transit service
-The purpose of this app is to pull down API-provided data on a regular basis to build a database of transit information, and then display it to the user
-The initial (MVP) use case will be to track the delay of the light rail trains at the downtown transit tunnel location, throughout the day and from day to day and week to week. 
-This location was chosen because the transit tunnel is currently shared between light rail and busses, but busses are planned to be transitioned to surface streets starting March 23 2019. Therefore, I expect a change in average delay will occur during this time. This app will allow me to verify whether or not this occurs, and quantify the change. 
-As an MVP, the data could be presented as a table

## Further Feature Development

-One of the first improvements would be to find a way to present the data in a more visual way
-After that (or simultaneously if possible), I'd like to make the data interactive by providing the ability to change the time frame of the data represented
-Then, I'd like to be able to add other locations and transit options to track, beyond just the light rail train the bus tunnel. These first other locations would be other very high volume locations and lines that would be of interest to the greatest number of people
-Eventually, I'd like the user to be able to enter a location and transit option (bus number or train), and have the app begin tracking delays for their requested parameters. Then the user would be able to come back to the app later and see and analyze the information. This option would require a log-in and user information.
-If storage space is not an issue, the app could eventually track all Puget Sound delay information and store it in a database, allowing the user to simply select their location and transit option and immediately see historical information. This option would not require user login, and would make more sense over the long run

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

