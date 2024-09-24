# Welcome to My Yelp
***

## Task
    The task is to deploy a ReactJS application to AWS using Amplify with authentication. 
    The challenge involves ensuring that the application works seamlessly with AWS Amplify's hosting and GraphQL integration. 
    Additionally, the app should be secure, requiring user authentication, and the integration with GraphQL queries and mutations
    must work as expected in the cloud environment. This project involves working with AWS services, 
    managing user authentication with Amplify, and handling GraphQL requests within the React app, 
    making sure everything functions properly in the deployed environment.

## Description
To solve this problem, I deployed the ReactJS application to AWS Amplify, 
             which offers hosting and authentication services. 

    The process involved the following steps:

        1: Amplify Initialization: 
            Initialized AWS Amplify in the project, setting up the required configuration 
            for hosting and authentication.

        2: Authentication: 
            Used Amplify’s built-in authentication service to handle user sign-up, sign-in, 
            and session management, ensuring secure access to the app.

        3. GraphQL Integration: 
            Configured Amplify’s GraphQL API using AWS AppSync, which allows the application to interact with 
            the backend using queries and mutations. The GraphQL schema and resolvers were set up to ensure
             proper data flow between the front-end and the back-end.

        4: Deployment: 
            After setting up Amplify and authentication, the project was deployed to AWS. 
            Amplify’s continuous deployment feature automatically builds and deploys changes to the application
            when new code is pushed to the repository.

## Installation
    To install the project, follow these steps:

        1: Clone the repository:

            bash
            git clone https://github.com/Tobi-Ti/My_Yeld.git
        
        
        2: Navigate to the project directory:

           bash
            cd project-name

        3: Install dependencies using npm:
        
            bash
            npm install
        
        4: Set up Amplify (if not already configured):

            bash
            amplify init
            Follow the prompts to configure Amplify for the project.

        5: Push Amplify configuration to AWS:

            bash
            amplify push
        This will set up the necessary resources on AWS (such as authentication and GraphQL) 
        and link them to your React app.

## Usage
    Once installed, you can run the application locally or access it from the deployed environment on AWS Amplify.

        1: Running the application locally:
            bash
            npm start
            This will start the application on http://localhost:3000.

        2: Using the deployed version: 
            After deployment, the app is available at the AWS Amplify hosting URL. 
            The URL can be found in the AWS Amplify console after deployment. 
            You will need to sign up or sign in to access the application.
           
            link: https://d2x9mkhzhd0ws7.cloudfront.net

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
