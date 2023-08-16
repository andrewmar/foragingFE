# Nourish & Gather: ForagingFE

## Description

Nourish & Gather is a foraging application designed to help users discover and share forageable resources. This repository contains the front-end code for the application, which is built using Expo Go and React Native.

## Project Structure

- `App.js`: The main entry point for the application.
- `babel.config.js`: Configuration file for Babel, a JavaScript compiler that converts ECMAScript 2015+ code into a backwards compatible version of JavaScript.
- `package.json`: Holds various metadata relevant to the project, including its dependencies.
- `app.json`: Configures parts of the app that need to be generated during the build phase.

## Setup and Installation

To set up the application on your local machine, follow these steps:

1. Clone or fork this repository.
2. Install the necessary dependencies by running `npm install`.
3. Start the application by running `npm start`. You will be prompted to choose how you wish to run the application (iOS, web, or Android).

## Usage

After running `npm start`, you can run the application on your device using Expo Go. 

Upon launching the application, you will be prompted to choose a username. This username will be used for posting resources and comments. 

Once a username is submitted, the application navigates to a map page where all of the forageable resources are marked. As a user, you can:

- View a resource
- Post comments on a resource
- Delete your own comments
- Add your own resource

The location of a resource is determined from the location data attached to the image of the resource.

## Contributing

Contributions are welcome! If you have a feature request, bug report, or proposal for code refactoring, please open a new issue on this repository. If you wish to contribute code, please fork the repository, make your changes, and open a pull request.
