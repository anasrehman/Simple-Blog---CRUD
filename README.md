
# Build Your Own API Project

This repository contains the code and resources for the "Build Your Own API" course by Angela Yu. The project demonstrates how to create a RESTful API using Node.js and Express.js, and includes a frontend built with HTML, CSS, and EJS.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project is a RESTful API built using Node.js and Express.js. It includes a frontend created with HTML, CSS, and EJS. The API allows users to perform CRUD (Create, Read, Update, Delete) operations on a dataset. The course by Angela Yu provides a comprehensive guide on how to build this API from scratch, covering fundamental concepts and best practices.

## Features

- Create new entries in the dataset
- Retrieve details of existing entries
- Update existing entries
- Delete entries
- Error handling for invalid requests
- Dynamic rendering of data with EJS
- Basic frontend interface with HTML and CSS

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository
    ```sh
   https://github.com/anasrehman/Simple-Blog---CRUD.git
    ```
2. Navigate to the project directory
    ```sh
    cd your-repo-name
    ```
3. Install the required packages
    ```sh
    npm install
    ```

## Usage

To run the API locally, use the following command:

```sh
node app.js
```

The API will be accessible at `http://127.0.0.1:3000`.

## Endpoints

Here are the available endpoints for the API:

- `GET /items`: Retrieve all items
- `GET /items/:id`: Retrieve a single item by its ID
- `POST /items`: Create a new item
- `PUT /items/:id`: Update an existing item by its ID
- `DELETE /items/:id`: Delete an item by its ID

## Testing with Postman

You can test the API endpoints using Postman:

1. Open Postman and create a new request.
2. Select the appropriate HTTP method (GET, POST, PUT, DELETE).
3. Enter the request URL (e.g., `http://127.0.0.1:3000/items`).
4. For POST and PUT requests, select the Body tab and choose raw and JSON format to send data.
5. Click Send to see the response.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have suggestions for improving this project, please fork the repository and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp/?couponCode=LEADERSALE24A) - For the comprehensive course
- [Node.js](https://nodejs.org/) - The JavaScript runtime used
- [Express.js](https://expressjs.com/) - The web framework used
- [Postman](https://www.postman.com/) - For API testing
- [GitHub](https://github.com/) - For hosting the repository

---

Feel free to customize this template to better fit your project. Include any additional sections or information specific to your project as needed.
