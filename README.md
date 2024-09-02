# E-commerce Back End

## Description

This project is a back-end application for an e-commerce site. Utilising Express.js API to configure it to use Sequelize to interact with a PostgreSQL database. This application provides a set of API endpoints allowing the management of categories, products, and tags in an e-commerce platform.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the necessary dependencies.
4. Create a `.env` file in the root directory and add your PostgreSQL database name, username, and password:


## Usage

Once the server is running, you can use an API client like Insomnia or Postman to test the API routes.

## API Routes

- Categories
- GET /api/categories
- GET /api/categories/:id
- POST /api/categories
- PUT /api/categories/:id
- DELETE /api/categories/:id

- Products
- GET /api/products
- GET /api/products/:id
- POST /api/products
- PUT /api/products/:id
- DELETE /api/products/:id

- Tags
- GET /api/tags
- GET /api/tags/:id
- POST /api/tags
- PUT /api/tags/:id
- DELETE /api/tags/:id

## Screenshots

![POST products](https://github.com/user-attachments/assets/35dd5626-6406-47d6-8615-222883b68190)
![UPDATE category](https://github.com/user-attachments/assets/17a7e81f-486b-4315-ae15-8df89d8f4e28)
![DELETE tags](https://github.com/user-attachments/assets/3d442584-4754-46fa-859d-9e5e21fccf1e)

## Technologies Used

- Node.js
- Express.js
- Sequelize ORM
- PostgreSQL
- dotenv

## Credits

This code was cloned from the repository by the following original contributors:

@Xandromus -  Xander Rapstine


Original Repository: [https://github.com/coding-boot-camp/miniature-eureka]

## License

This project is licensed under the MIT License.
