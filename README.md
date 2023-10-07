# Daily-Vatility-App

Health and fitness app to help users manage their weight and health.
![screenshot](https://github.com/akonde/Daily-Vatility-App/assets/49449335/b8d28dd6-302f-4d86-9943-467842c89836)


## Deployed Application

[Daily Vitality](https://daily-vitality.netlify.app/)

## Table of Contents:

1. [Description](#description)
2. [Installation](#installation)
3. [Technologies Used](#technologies)
4. [Usage](#usage)
5. [Contributions](#contributions)
6. [E-mail](#e-mail)

## Description

Health and fitness app which visually represents the users' current state of health and provides a rich interactive dashboard that will help them see goals and targets to manage their health. It shows the BMI and daily calorie targets and will help the users to keep track of their goals to achieve the desired weight and improve their health.
The users will create a profile by entering key data such as their gender, height, weight, activity level and their desired target. The app will then generate their BMI and ideal weight and based on the user's goal and current activity level, it will give information such as daily calorie consumption target.

## Technologies, APIs and Libraries Used

The app was built using Vite Framework and React and the following libraries and APIs.

- React-query: we used [useQuery](https://tanstack.com/query/latest/docs/react/reference/useQuery) to facilitate fetching data.
- useHooks library: we used [useLocalStorage](https://usehooks.com/uselocalstorage) hook to manage the local storage better.
  Axios: to get the data and manage it
  Bootstrap: to style the app
  [lucide-react](https://lucide.dev/): for the icons used in the application
  [chart.js](https://www.chartjs.org/) & [react-chartjs-2](https://react-chartjs-2.js.org/): to generate the pie charts
  [react-gauge-chart](https://www.npmjs.com/package/react-gauge-chart): to generate the angular gauge
  API used: [Fitness Calculator](https://rapidapi.com/malaaddincelik/api/fitness-calculator)

## Installation

To install the application, please follow the following steps:

1. Clone the repository in your local machine using the command below:

```
git clone
```

2. Install the dependencies:

```
npm install
```

3. Get the API URL and your API key from [RapidAPI](https://rapidapi.com/malaaddincelik/api/fitness-calculator) and add it to the .env file. The .env file should be in the root folder of the project.

```
VITE_FITNESS_API_KEY=your_api_key
VITE_FITNESS_API_URL=your_api_url
```

Find a sample .env file in the root folder of the project.

4. Run the application:

```
npm run dev
```

## Contributing

This project was developed by Team Star Techies.
Team members: Sara Bechinoun, Mohsin Khan Ajmal,
Maxwell Acha, Akintayo Durotoye and Sabeen Faisal

## License

None

## GitHub

https://github.com/sarabenchinoun/daily-vitality

## E-mail

[tayodurotoye@gmail.com](mailto:tayodurotoye@gmail.com)
