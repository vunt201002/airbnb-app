# Introduction
This is an movie app with MERN (MongoDB, Express, ReactJS, NodeJS), TailwindCSS.

# Demo
You can check out a live demo of this application [here](https://airbnb-app-6tc5.onrender.com)

# Installation
1. Clone my repo
```
    git clone https://github.com/vunt201002/netflix-app
```
2. Install node_modules
```
    cd client
    npm install
    
    cd ..
    cd server
    npm install
```
3. Start the server
```
    npm start
```
4. Runs the app in the development mode
```
    npm start
```
After that, open [http://localhost:3000](http://localhost:3000) to view it in your browser.

# Configuration
This application uses a few environment variables that you'll need to set:
- `PORT`: The port to run the server on (default is `9000`)
- `MONGO_URL`: The URL of your MongoDB database
- `API_KEY`: Your API key on tmdb
- `SECRET_KEY`: A secret key used to sign JSON Web Tokens for user authentication

# Features
This web application has the following features:
- User authentication: login, sign up
- Booking
    - Booking room
    - Delete your booking, update
- Room
    - Add your own room
    - Update info, delete

 # Contributing
If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request.