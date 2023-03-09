# Full Stack Application using MERN

This is a Full Stack Application built using the MERN stack: MongoDB, Express, React and Node.js. The application is designed to showcase the use of these technologies to create a web application.

## Installation

1. Clone the repository: `git clone https://github.com/username/repo.git`
2. Install dependencies:
   - Server: `cd server && npm install`
   - Client: `cd client && npm install`
3. Create a `.env` file in the server directory and add the following:

   > MONGO_URI=<your_mongo_uri>
   > PORT = 5001

4. Create a `.env.local` file in the client directory and add the following:
   > REACT_APP_BASE_URL=<your_server>
4. Start the application:
- Server: `cd server && npm start`
- Client: `cd client && npm start`

## Technologies

This application uses the following technologies:

- MongoDB: A document-oriented NoSQL database used for storing data.
- Express: A fast, unopinionated, minimalist web framework for Node.js used for building APIs.
- React: A JavaScript library for building user interfaces.
- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine used for building server-side applications.

## Environment Variables

This application uses the following environment variables:

- `MONGO_URI`: The MongoDB connection string.
- `PORT`: The server port number.
- `REACT_APP_BASE_URL`: The base URL of the React application.

## Deployment

This application can be deployed using different cloud platforms. For example, the frontend can be deployed using Vercel and the backend can be deployed using Render.

To deploy the frontend on Vercel, follow these steps:
1. Sign up for an account on vercel.com.
2. Connect your GitHub account to Vercel.
3. Create a new project on Vercel and select the React app template.
4. Follow the prompts to configure your deployment settings. You may need to provide your environment variables here.
5. Once the deployment is complete, you can access your app at the URL provided by Vercel.

To deploy the backend on Render, follow these steps:
1. Create an account on Render and create a new web service.
2. Connect the service to your GitHub repository and select the branch to deploy.
3. Add a new environment variable called `MONGO_URI` and set it to your MongoDB URI.
4. Add a new environment variable called `PORT` and set it to the server port number.
5. Follow the prompts to deploy the service.
