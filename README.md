# TechJunction

TechJunction is a collaborative platform designed for college students to engage in problem-solving, knowledge-sharing, and interaction within their academic community. The platform enables students to post study materials, interact with others through comments and replies, save posts, and chat one-on-one with peers.

## Features

- **Post Study Materials**: Students can share and manage their study materials.
- **Comment and Reply**: Engage in discussions by commenting and replying to posts.
- **Save Posts**: Save posts for easy access later.
- **One-to-One Chat**: Communicate privately with peers.
- **Authentication**: Secure login using JWT tokens.

## Tech Stack

- **Frontend**: React (located in `client` folder)
- **Backend**: Node.js, Express.js (located in root directory)
- **Database**: MongoDB (NoSQL)
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: [Render](https://render.com)

## Demo

Check out the live application here: [TechJunction](https://techjunction-7f3t.onrender.com/)

## Installation and Setup

### Prerequisites

- Node.js
- MongoDB (local or Atlas)

### Steps

1. Clone the repository:
   ```bash
   git https://github.com/aashiyatanwar/TechJunction.git
   cd TechJunction

2. Backend Setup:

    - Navigate to the root directory
    - Create .env file
       ```bash
       MONGODB_URL = your-connection-string
       ACCESS_TOKEN_SECRET = your-access-token
       REFRESH_TOKEN_SECRET = your-refresh-token
       SKIP_PREFLIGHT_CHECK = true
    - Run : npm i && npm start

3. Frontend Setup:
    - Navigate to the client directory : cd client
    - Run : npm i && npm start
