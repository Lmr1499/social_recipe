
---

# 🍽️ Recipe Sharing App

This is a simple recipe sharing application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## ✨ Features

- 📝 Users can create an account and log in to share their recipes.
- ❤️ Users can view, like, and comment on recipes shared by others.
- 📱 Responsive design for a seamless experience across devices.

## 📁 Project Structure

The project consists of two main folders:

1. **Server**: Contains the backend code responsible for handling requests, managing the database, and serving the API endpoints.

   - **Package.json**:
     ```json
     {
       "name": "server",
       "version": "1.0.0",
       "main": "index.js",
       "license": "MIT",
       "type": "module",
       "scripts": {
         "start": "NODE_OPTIONS='--experimental-specifier-resolution=node' nodemon src/index.js"
       }
     }
     ```

   - **Usage**:
     ```bash
     cd server
     npm install
    nodemon src/index.js
     ```

2. **Client**: Contains the frontend code built with React.js for the user interface of the application.

   - **Package.json**:
     ```json
     {
       "name": "client",
       "version": "1.0.0",
       "main": "index.js",
       "license": "MIT",
       "type": "module",
       "scripts": {
         "start": "react-scripts start",
         "build": "react-scripts build",
         "test": "react-scripts test",
         "eject": "react-scripts eject"
       }
     }
     ```

   - **Usage**:
     ```bash
     cd client
     npm install
     npm start
     ```

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Install dependencies for the server and client:
   ```bash
   cd your-repo/server
   npm install

   cd ../client
   npm install
   ```

3. Start the server and client (in separate terminal windows):
   ```bash
   cd your-repo/server
   npm start

   cd ../client
   npm start
   ```

4. Access the application at `http://localhost:3000` in your browser.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
