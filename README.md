

## Features

- Create, update and edit products
- Secure user registration and authentication
- Secure Payments with Stripe
- Fast image upload & optimization with Cloudinary
- Email Services using Sendgrid
- Generate bills in PDF form for every order

## Tech Stack

- Node.js
- Express.js
- EJS
- MongoDB

## Local Development

Run the project in your machine locally.

### Step 1: Clone the repository

Clone the repo locally using:

```sh
git clone https://github.com/Aruzhan2004/myAss.git
```

### Step 2: Install Dependencies

Install dependencies in the root folder

```sh
cd myAss
npm install
```

### Step 3: Setup Environment Variables

You will need to provide your own `.env` variables, here's how you can do it:

- create a new file `.env` in the root
- open [.env.EXAMPLE](./.env.EXAMPLE)
- copy the contents and paste it into your own `.env` file
- make sure you replace the values with your own valid values

> Note: The `NODE_ENV` should either be "development" or "production". This will decide which database to use `MONGO_LOCAL` or `MONGO_ATLAS`

### Step 4: Run the server

```sh
npm run dev
```
