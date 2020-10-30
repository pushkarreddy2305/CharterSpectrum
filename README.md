M = MongoDB (We'll use Mongoose to make it easier for Node.js to work with MongoDB, and we'll use MongoDB Atlas = MongoDB database, but cloud).
E = Express (makes it easier to work with Node.js. We'll use cors middleware to access other servers outside our server).
R = React (for the frontend. We'll use bootstrap for styling, react-router-dom for React routes, react-datepicker for React Datepicker component, and axios to connect to the backend).
N = Node.js (for the server. We'll use dotenv to load environment variables from an .env file into process.env, and nodemon to make the app auto-restart when you edit/save files).

Restaurant App:

restaurant collection
To just get it running after you git clone, set up MongoDB Atlas, and then follow these CLI steps:

cd frontend
npm install
cd backend
npm install

# inside /CharterSpectrum: (separate CLI tab)
cd ..
cd charterSpectrum
npm start

# inside /CharterSpectrum: (separate CLI tab)
cd charterSpectrum/backend
nodemon server.js
# or: nodemon -x 'npm run lint; node server.js'
