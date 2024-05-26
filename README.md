This project was built with the following technologies:

- Node.js
- Express.js
- MongoDB (with Mongoose)
- React.js

1) Clone the repository to your local machine
2) Navigate to the backend folder:
    cd backend
3) Create a .env file in the root directory with the following content:
    PORT=5000
    MONGO_URI=mongodb+srv://username:password@yourcluster.lptwdk7.mongodb.net/?retryWrites=true&w=majority&appName=toDoCluster
    Replace username, password, and yourcluster with your MongoDB Atlas username, password, and cluster name respectively.
4) Install dependencies:
    npm install
5) Run the application:
    npm start
6) Navigate to the frontend folder:
   If you are in backend folder:
     cd ../frontend
   If you are in root:
     cd frontend
7) Create a .env file in the root directory with the following content:
    REACT_APP_API_URL=http://localhost:5000/api
8) Install dependencies:
    npm install
9) Run the application:
    npm start
