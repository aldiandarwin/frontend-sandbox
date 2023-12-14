# Project Title: Payment Gateway Frontend

This is the frontend repository for the Payment Gateway project. The frontend communicates with the backend built using Express.js and integrates with the Midtrans sandbox for payment processing.

![Mock-Up.png](https://github.com/aldiandarwin/frontend-sandbox/assets/70283015/a2ffd65d-970b-4d8f-978e-e5eac9f6df24)

## Tech Stack

React.js

A JavaScript library for building user interfaces.

Prettier

An opinionated code formatter to enforce consistent code style.

## Getting Started

Clone the repository:

bash

```Copy code
git clone  <https://github.com/aldiandarwin/frontend-sandbox.git>
```

cd payment-gateway-frontend

Install dependencies:

bash

```Copy code
npm install
```

Set up the environment variables:

Create a .env file in the root of the project and add the following configuration:

env

```Copy code
REACT_APP_BACKEND_URL="http://localhost:8000"
```

Update the URL with the actual backend URL.

Run the development server:

bash

```Copy code
npm start
```

The development server will run on <http://localhost:5173>.

### Code Formatting and Styling

Prettier: This project uses Prettier for code formatting. Run the following command to format your code:

bash

```Copy code
npm run format
```
