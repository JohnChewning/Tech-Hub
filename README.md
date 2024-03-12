# Tech Hub Web Application

Tech Hub is a web application that allows users to share and discuss technology-related posts. Users can create an account, log in, create new posts, and interact with other users through comments.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication:** Users can create accounts, log in, and log out securely.
- **Create Posts:** Authenticated users can create new posts to share information with the community.
- **Comments:** Users can comment on posts to engage in discussions.
- **Dashboard:** Authenticated users have access to a personalized dashboard where they can manage their posts.

## Technologies Used

- **Node.js:** A JavaScript runtime for building the server-side of the application.
- **Express.js:** A web application framework for Node.js, used to build the server and handle HTTP requests.
- **Sequelize:** A promise-based Node.js ORM for MySQL, used for database operations.
- **MySQL:** A relational database management system for storing user data and posts.
- **Handlebars.js:** A templating engine for creating dynamic HTML templates.
- **JavaScript (ES6+):** The primary programming language for building the application's frontend and backend logic.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/tech-hub.git
   ```

2. Navigate to the project directory:

    ```bash
    cd tech-hub
    ```

3. Install the project dependencies:

    ```bash
    npm install
    ```
4. Set up the MySQL database:

 - Create a .env file in the root directory and add your MySQL credentials:

    ```env
    DB_NAME=tech_hub_db
    DB_USER=root
    DB_PASSWORD=your_password
    DB_HOST=localhost
    ```

## Usage

1. Start the application:

    ```bash
    npm start
    ```
2. Open your web browser and navigate to http://localhost:3001.

3. Sign up for a new account or log in if you already have one.

4. Explore the homepage, create new posts, and engage in discussions with other users.

## Contributing

N/A

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).