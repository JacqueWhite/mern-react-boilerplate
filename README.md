# mern-react-boilerplate

Boilerplate for creating a full-stack MERN application using these technologies:

- React
- Node
- Express
- Community MongoDB (and/or MongoDB Atlas)
  - - [MongoDB Atlas](https://mongodb.com/atlas)
  - - [MongoDB Documentation](https://docs.mongodb.com/)
- Mongoose

## Get Started

Set up a MongoDB database either [locally](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/) or with [MongoDB Atlas](https://mongodb.com/atlas) for free

### Set up environment variables

Copy the env.local.example file in this directory to .env.local (which will be ignored by Git):

`cp .env.local.example .env.local`

Set each variable on .env.local:

- `MONGODB_URI` - Your MongoDB connection string. If you are using MongoDB Atlas you can find this by clicking the "Connect" button for your cluster.

### Set up React in Development Mode

`npm install`
`npm run dev`

# or

`yarn install`
`yarn dev`

Your app should be up and running on http://localhost:3000!

You will either see a message stating "Connected to MongoDB" or a connection error message. Ensure that you have provided the correct MONGODB_URI environment variable.
