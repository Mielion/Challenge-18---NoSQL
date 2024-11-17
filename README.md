# Social Network API

## Table of Contents

- Description
- Features
- Technologies Used
- Installation
- Usage
- Endpoints
- License
- walkthrough  
- Questions

### Description

The Social Network API is a back-end application that provides the functionality needed to power a social networking platform. This API handles user data, friend relationships, and user-generated thoughts and reactions. It is built using MongoDB and Mongoose for the database and Express.js for routing, demonstrating RESTful API design principles.

### Features

- Create, read, update, and delete (CRUD) user accounts.
- Add and remove friends from user profiles.
- Create, read, update, and delete thoughts.
- Add and remove reactions to thoughts.
- MongoDB database with Mongoose for flexible, scalable data storage.

### Technologies Used

- Back-End: Node.js, Express.js
- Database: MongoDB, Mongoose
- Testing: Insomnia or Postman (recommended for API testing)
- Environment Variables: dotenv
  
### Installation

Clone the repository:
```
git clone https://github.com/yourusername/social-network-api.git
``` 
Navigate to the project directory:
bash
Copy code
cd social-network-api
Install dependencies:
bash
Copy code
npm install
Set up a .env file in the root directory with the following:
plaintext
Copy code
MONGODB_URI=your_mongodb_connection_string
Start the application:
bash
Copy code
npm start
Usage
Use an API testing tool like Insomnia or Postman to interact with the API.
Base URL for API requests:
bash
Copy code
http://localhost:3001/api
Endpoints
Here’s a brief overview of the available endpoints:

Users
GET /api/users - Get all users.
GET /api/users/:userId - Get a single user by ID.
POST /api/users - Create a new user.
PUT /api/users/:userId - Update a user by ID.
DELETE /api/users/:userId - Delete a user by ID.
POST /api/users/:userId/friends/:friendId - Add a friend.
DELETE /api/users/:userId/friends/:friendId - Remove a friend.
Thoughts
GET /api/thoughts - Get all thoughts.
GET /api/thoughts/:thoughtId - Get a single thought by ID.
POST /api/thoughts - Create a new thought.
PUT /api/thoughts/:thoughtId - Update a thought by ID.
DELETE /api/thoughts/:thoughtId - Delete a thought by ID.
POST /api/thoughts/:thoughtId/reactions - Add a reaction to a thought.
DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Remove a reaction.
License
This project is licensed under the MIT License.

Contributing
Contributions are welcome! Follow these steps:

Fork the repository.
Create a feature branch:
bash
Copy code
git checkout -b feature/YourFeature
Commit your changes:
bash
Copy code
git commit -m "Add YourFeature"
Push your branch:
bash
Copy code
git push origin feature/YourFeature
Open a pull request.
Questions
If you have any questions, please contact me:

GitHub: yourusername
Email: your-email@example.com




[SocialNetwork-api](https://drive.google.com/file/d/15VLXRN87eJqT37G2T7i-bXTgFhCIeael/view?usp=drive_link)
