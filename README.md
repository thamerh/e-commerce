#  eCommerce Website

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to your eCommerce website built with Next.js, MongoDB, and Stripe. This project aims to provide a scalable and modern solution for online commerce.

## Features

- **Next.js**: Utilizes the power of React with server-side rendering for a fast and responsive user experience.
- **MongoDB**: Database storage for your product information, orders, and user data.
- **Stripe Integration**: Secure payment processing for a seamless checkout experience.
- **Responsive Design**: Ensures a consistent experience across various devices.

## Requirements

Make sure you have the following installed before running the application:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Stripe Account](https://stripe.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/thamerh/e-commerce.git
   
2. Navigate to the project folder:
   cd e-commerce
3. Install dependencies:
   npm install
   
## Configuration

1. MongoDB Configuration:
 - Create a MongoDB database for your project.
 - Copy the .env.example file to `.env` and update the MongoDB connection string:
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<database>
   
2. Stripe Configuration:
  - Sign in to your Stripe account and get your API keys.
  - Update the `.env` file with your Stripe API keys:
     STRIPE_PUBLIC_KEY=your_public_key
     STRIPE_SECRET_KEY=your_secret_key
 
## Usage

Run the development server:
  npm run dev
  Visit http://localhost:3000 in your browser.
  
## Deployment
To deploy eCommerce website, follow the deployment guidelines for Next.js.

## Contributing

Contributions are welcome! Please follow the contribution guidelines.

