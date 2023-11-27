# E-Commerce Website with React, Firebase, Razorpay, Tailwind CSS, and Material UI

This repository contains the source code for building a modern e-commerce website using React as the front-end library, Firebase as the backend, Razorpay for payment processing, and Tailwind CSS and Material UI for styling. This README file will guide you through setting up and running the project.

## Features

- User authentication (Firebase Authentication).
- Product catalog and category filtering.
- Shopping cart functionality.
- Checkout process with Razorpay integration.
- Order history for authenticated users.
- Responsive design using Tailwind CSS and Material UI.


## Prerequisites

Before you begin, ensure you have the following tools installed on your system:

- [Node.js](https://nodejs.org/): You will need Node.js to run this project. You can download it from the official website.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Satyam5665/ecommerce_mern.git
   ```

2. Change into the project directory:

   ```bash
   cd ecommerce_mern
   ```

3. Install project dependencies using npm:

   ```bash
   npm install
   ```


## Configuration

Before running the application, you need to configure Firebase and Razorpay.

### Firebase Configuration

1. Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).

2. Set up Firebase Authentication, Realtime Database, and Firestore as needed for your e-commerce website.

3. Obtain your Firebase configuration object (apiKey, authDomain, projectId, etc.) from the Firebase Console and replace it in the `src/firebase/firebaseConfig.js` file.

### Razorpay Configuration

1. Sign up for a Razorpay account if you don't have one already.

2. Obtain your Razorpay API key and replace it in the `src/components/Checkout.js` file.

## Running the Application

To run the application locally, use the following command:

```bash
npm start
```

This will start the development server, and the application will be accessible at `http://localhost:3000`.


Thank you for choosing this e-commerce website template built with React, Firebase, Razorpay, Tailwind CSS, and Material UI. 
We hope it helps you kickstart your e-commerce project! If you have any questions or need further assistance, please feel free to reach out. Happy coding!
