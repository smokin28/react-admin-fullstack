# Me learning how to create Fullstack Dashboard

Frontend using:

React/react-datepicker/react-redux/mui/emotion/nivo

# Backend using:

Mongoose/express/dotenv/nodemon/morgan/helmet/cors/body-parser/country-iso-2-to-3

For the Server, MongoDb needs to be setup. .env needs to be in the 'server' folder with  
the URL to the MongoDb and custom PORT number. Then in server/index.js uncomment lines  
55-60 to inject sample data to MongoDb. Then use npm run dev once, verify data is in  
MongoDb, if there comment out lines 55-60 and use npm run start to start the server.

For the Client, .env.local needs to be in the 'client' folder with the REACT_APP_BASE_URL  
set to localhost with port number set in server. Then use npm start to view the Dashboard.

Thanks to EdRoh on YouTube!
