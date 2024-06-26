# Acadoze Repository

## Technologies Used
- NextJs
- Node.js
- Express.js
- Sequelize
- PostgreSQL

## Setting Up Environment Variables

This project uses environment variables for configuration. Follow these steps to set up your environment variables:

1. Create a new file named `.env` in the root of the project.
2. Copy the contents of `.env.sample` into `.env`.
3. Replace the placeholder values in `.env` with your actual values.

## Development Setup

To set up the development environment for this project, follow these steps:

2. Install dependencies: `npm install`
3. Run the application: `npm start`

## Running Development Migrations

To run development migrations for your database, follow these steps:

1. Ensure that your database server is running and that your development database is properly configured in `config/config.js`.
2. Use the following command to run the migrations
- `npx sequelize-cli db:migrate`

