# This project reference from [Serverless stack](https://serverless-stack.com/)

It is a single page application powered by a serverless API written completely in JavaScript. Here is the complete source for the backend and the frontend. It is a relatively simple application but we are going to address the following requirements.

- Should allow users to signup and login to their accounts
- Users should be able to create notes with some content
- Each note can also have an uploaded file as an attachment
- Allow users to modify their note and the attachment
- Users can also delete their notes
- The app should be able to process credit card - payments
- App should be served over HTTPS on a custom domain
- The backend APIs need to be secure
- The app needs to be responsive

We’ll be using the AWS Platform to build it. We might expand further and cover a few other platforms but we figured the AWS Platform would be a good place to start.


# Technologies & Services
We’ll be using the following set of technologies and services to build our serverless application.

- Lambda & API Gateway for our serverless API
- DynamoDB for our database
- Cognito for user authentication and securing our APIs
- S3 for hosting our app and file uploads
- CloudFront for serving out our app
- Route 53 for our domain
- Certificate Manager for SSL
- React.js for our single page app
- React Router for routing
- Bootstrap for the UI Kit
- Stripe for processing credit card payments
- Seed for automating Serverless deployments
- Netlify for automating React deployments
- GitHub for hosting our project repos.

We are going to be using the free tiers for the above services. So you should be able to sign up for them for free. This of course does not apply to purchasing a new domain to host your app. Also for AWS, you are required to put in a credit card while creating an account. So if you happen to be creating resources above and beyond what we cover in this tutorial, you might end up getting charged.