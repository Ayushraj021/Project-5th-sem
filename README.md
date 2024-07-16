# Regal Robes E-commerce Website

Welcome to the official repository of Regal Robes, a premier men's wear e-commerce website. This project is built using ReactJS for the frontend, Java for the backend, and MySQL for the database. The application is hosted on AWS Amplify, with code managed through GitHub.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Product browsing and searching
- Shopping cart functionality
- Order management system
- User profile management
- Responsive design for optimal viewing on all devices

## Installation

### Prerequisites

- Node.js and npm
- Java Development Kit (JDK)
- MySQL
- AWS CLI configured with your account

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/regal-robes.git
   cd regal-robes/backend
   ```

2. Build the Java application:
   ```bash
   ./gradlew build
   ```

3. Set up the MySQL database:
   ```sql
   CREATE DATABASE regal_robes;
   USE regal_robes;
   SOURCE path/to/schema.sql;
   ```

4. Run the backend server:
   ```bash
   java -jar build/libs/regal-robes-backend.jar
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Open your web browser and navigate to `http://localhost:3000` to view the application.
2. Register a new user account or log in with an existing account.
3. Browse the catalog, add items to your cart, and proceed to checkout.

## Project Structure

```
regal-robes/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   └── test/
│   └── build.gradle
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── App.js
│   └── package.json
├── README.md
└── .gitignore
```

## Contributing

We welcome contributions to improve Regal Robes! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for visiting Regal Robes! We hope you enjoy using our e-commerce platform.

For any questions or support, please contact us at ayushraj02929@gmail.com.
