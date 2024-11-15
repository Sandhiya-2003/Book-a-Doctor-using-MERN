# Book-a-Doctor-using-MERN
In this Project we have tried to create a Book a Doctor Application using MERN Stack. This application is designed to facilitate online appointment booking for patients and doctors. It provides a user-friendly interface for patients to search for doctors, book appointments, and manage their schedules.
**Prerequisites**
1. Node.js and npm (or yarn): Ensure you have the latest versions installed.
2. MongoDB: Set up a local or cloud-based MongoDB database.

**To run this on your local machine**
Step 1: Use Git to clone the project repository to your local machine or Clone the repository by using clone from version control systems option from IDE . 
Step 2 : Use npm or yarn to install the required dependencies 
Step 3 : Add .env file in root directory for the backend which contains
	_PORT=5000
  MONGO_URI=YOUR_OWN_MONGODB_URL
  JWT_SECRET=YOUR_JWT_SECRET_
Step 4: Add .env file in client directory for the frontend which contains
_REACT_APP_SERVER_DOMAIN=http://127.0.0.1:5000/api
REACT_APP_CLOUDINARY_BASE_URL=https://api.cloudinary.com/v1_1/{CLOUD_NAME}/image/upload
REACT_APP_CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME
REACT_APP_CLOUDINARY_PRESET=YOUR_CLOUDINARY_PRESET_
Replace the {CLOUD_NAME} with your own cloudinary cloud name
Step 5: Install MongoDB , NodeJS for your machine and create the database and create required collections In MongoDB

### Tools and technologies used :
1. MongoDB
2. ExpressJS
3. ReactJS
4. NodeJS
5. HTML
6. CSS
7. IntelliJ
