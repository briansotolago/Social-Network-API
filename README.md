# Social Network API

## Description

This project is a Social Network API built using Express.js and MongoDB, with Mongoose as the ODM. It allows users to share thoughts, react to friends' thoughts, and manage a friend list. This API is designed to handle large amounts of unstructured data, making it ideal for social media applications.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Video Walkthrough](#video-walkthrough)
- [Repo](#repo)
- [License](#license)
- [Contact](#contact)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/social-network-api.git
   ```

2. Navigate into the project directory:

   ```bash
   cd social-network-api
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Ensure MongoDB is installed and running on your machine. Follow the [MongoDB installation guide](https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb) if needed.

## Usage

To start the server, run the following command:

```bash
npm start
```

You can test the API endpoints using a tool like Insomnia or Postman.

## Features

- User management: Create, update, and delete users.
- Thought management: Create, update, and delete thoughts.
- Reaction management: Add and remove reactions to thoughts.
- Friend management: Add and remove friends from a user's friend list.

## API Endpoints

### Users

- `GET /api/users`: Retrieve all users.
- `GET /api/users/:id`: Retrieve a single user by ID.
- `POST /api/users`: Create a new user.
- `PUT /api/users/:id`: Update a user by ID.
- `DELETE /api/users/:id`: Delete a user by ID.

### Friends

- `POST /api/users/:userId/friends/:friendId`: Add a friend.
- `DELETE /api/users/:userId/friends/:friendId`: Remove a friend.

### Thoughts

- `GET /api/thoughts`: Retrieve all thoughts.
- `GET /api/thoughts/:id`: Retrieve a single thought by ID.
- `POST /api/thoughts`: Create a new thought.
- `PUT /api/thoughts/:id`: Update a thought by ID.
- `DELETE /api/thoughts/:id`: Delete a thought by ID.

### Reactions

- `POST /api/thoughts/:thoughtId/reactions`: Add a reaction.
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId`: Remove a reaction.

## Video Walkthrough

[Video Walkthrough](https://drive.google.com/file/d/1rwt9i6NJc2x1gXnBbESGNRSdYJXmrLgS/view)

## Repo

[Repo](https://github.com/briansotolago/Social-Network-API)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact:

- Email: [briansoto.bs23@gmail.com](mailto:briansoto.bs23@gmail.com)
- GitHub: [briansotolago](https://github.com/briansotolago)
