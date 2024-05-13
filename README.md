# Wisdomly Online Bookstore

Welcome to the Wisdomly Online Bookstore repository. This project demonstrates a fully functional online bookstore using AWS, Stripe for payments, and React for the frontend.

# Project Link:

https://dfxyqzum0c3c9.cloudfront.net/

## Technologies Used

- **React**: Frontend library for building user interfaces
- **AWS Amplify**: Used to connect and configure backend resources on AWS
- **AWS AppSync**: Manages the GraphQL API for the project
- **AWS S3**: Storage for book images and static website hosting
- **Stripe**: For handling payments

## Features

- Browse books, view details, add to cart, and checkout.
- Admin panel for adding and managing books.
- Authentication for users with different roles, enabling specific features for admins and guests.
- Payment processing integration using Stripe.

## Project Setup

1. **Clone the Repository**:

git clone https://github.com/Andromeda-1999/Bookstore-AWS.git

2. **Install Dependencies**:
Navigate to the project directory and run:

npm install

3. **Initialize AWS Amplify**:
Configure the project with AWS by initializing Amplify. Make sure AWS CLI is configured on your machine.

amplify init

4. **Deploy Backend Resources**:
Deploy the AppSync API, authentication, and storage resources:

amplify push

5. **Start the Development Server**:
Launch the project locally to see it in action:

npm start

6. **Deployment**:
Deploy the application using AWS S3 for static web hosting. Ensure all your backend resources are properly set up and synced with the cloud.
