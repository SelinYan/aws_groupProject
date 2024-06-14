# Typing Game

## Overview

Typing Game is a simple speed typing game designed to help users improve their typing skills. The application uses Express.js for the backend and Parcel for bundling the frontend assets. Deployed using AWS CodePipeline and AWS BeanStalk.

Live demo:

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Configuration](#configuration)
- [License](#license)

## Installation

### Prerequisites

- Node.js (>=10.0.0)
- npm (>=6.0.0)

### Steps

1. Clone the repository:

   ```sh
   git clone https://github.com/SelinYan/aws_groupProject.git
   cd TypingGame
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

## Running the Application

1. run the server:

   ```sh
   npm start
   ```

2. run the application in development mode

   ```sh
   npm run dev
   ```

3. Visit http://localhost:3000 in your browser.

## Deployment

The application is deployed using AWS Elastic Beanstalk and AWS CodePipeline for continuous integration and delivery. The following steps outline the deployment process:

1. AWS Elastic Beanstalk:

Create an Elastic Beanstalk environment and configure it to use Node.js.
Deploy the application to the Elastic Beanstalk environment.

2. AWS CodePipeline:

Set up a CodePipeline to automate the deployment process.
Connect the pipeline to the GitHub repository to automatically deploy changes pushed to the repository.

## Technologies Used

Backend: Express.js
Frontend: HTML, CSS, JavaScript
Bundler: Parcel
Development Tools: Nodemon, Concurrently
CI/CD: AWS Elastic Beanstalk, AWS CodePipeline

## Configuration

The server uses port 3000 by default, or a port specified by the PORT environment variable.

## License

This project is licensed under the ISC License.
