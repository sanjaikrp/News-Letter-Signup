# Newsletter Signup Project

## Introduction
The Newsletter Signup Project is a web application designed to collect email addresses from users who wish to subscribe to a newsletter. It provides a simple and efficient way to build and manage a mailing list.

## Features
- User-friendly signup form
- Email validation
- Confirmation email upon subscription
- Integration with email marketing services (e.g., Mailchimp)
- Responsive design for both desktop and mobile

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express
- Database: MongoDB
- Email Service: Mailchimp API

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/News-Letter-Signup.git
    ```
2. Navigate to the project directory:
    ```sh
    cd News-Letter-Signup
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```
4. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
    Fill in the required values in the `.env` file, including your Mailchimp API key and list ID.
5. Start the development server:
    ```sh
    npm start
    ```

## Usage
1. Open your web browser and navigate to `http://localhost:3000`.
2. Use the provided form to enter your email address and subscribe to the newsletter.
3. Check your email for a confirmation message to complete the subscription process.
