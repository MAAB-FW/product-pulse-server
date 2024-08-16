# Product Pulse (server side)

This is a simple Express.js server with MongoDB integration. Follow the instructions below to set up the project locally.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

-   [Node.js](https://nodejs.org/) (v14 or later)
-   [npm](https://www.npmjs.com/) (comes with Node.js)
-   [MongoDB](https://www.mongodb.com/try/download/community) (MongoDB Community Server or MongoDB Atlas)

## Getting Started

### 1. Clone the Repository

Start by cloning this repository to your local machine using `git`:

```bash
git clone https://github.com/MAAB-FW/product-pulse-server.git
cd your-repo-name
```

### 2. Install Dependencies

    Using npm:

    ```sh
    npm install
    ```

    Or using yarn:

    ```sh
    yarn install
    ```

### 3. Set Up Environment Variables

Create a `.env` file in the root of the project and add the following environment variables:

```plaintext
MONGODB_URI=mongodb://localhost:27017/
```

### 4. Run the Server

Start the Express.js server by running:

```bash
npm run dev
```

### 5. Access the Server

Open your browser and navigate to:

```arduino
http://localhost:5000
```

You should see the server running.
