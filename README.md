# Express.js User Management API

This is a simple Express.js API for managing users. It provides basic CRUD (Create, Read, Update, Delete) operations for a list of users.

## Features

- **List Users:** Retrieve the list of existing users.
- **Add User:** Add a new user to the list.
- **Delete User:** Remove a user from the list.
- **Update User:** Modify the details of an existing user.

## Prerequisites

Make sure you have Node.js and npm installed on your machine.

## Getting Started

1. Clone this repository to your local machine:

git clone [https://github.com/ShubhamJain-23/express-user-api.git](https://github.com/ShubhamJain-23/Express-Node-API)


2. Navigate to the project directory:

cd express-user-api


3. Install dependencies:

npm install


4. Start the server:

npm start


The server will start running at `http://localhost:8080`.

## API Endpoints

- **GET /listUsers**: Retrieve the list of users.
- **PUT /addUser?name=**: Add a new user to the list.
- Parameters:
 - `name`: The name of the user to add.
- **DELETE /deleteUser?start=&deleteCount=**: Remove user(s) from the list.
- Parameters:
 - `start`: The index at which to start removing users.
 - `deleteCount`: The number of users to remove.
- **POST /updateUser?index=&name=**: Update the name of a user.
- Parameters:
 - `index`: The index of the user to update.
 - `name`: The new name for the user.

## Usage

You can use tools like cURL, Postman, or any HTTP client library to interact with the API.

### Example Usage:

- **List Users**:

GET http://localhost:8080/listUsers


- **Add User**:

PUT http://localhost:8080/addUser?name=John


- **Delete User**:

DELETE http://localhost:8080/deleteUser?start=0&deleteCount=1


- **Update User**:

POST http://localhost:8080/updateUser?index=0&name=Jane


## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


