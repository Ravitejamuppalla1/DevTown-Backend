1. Clone the repository:
   ```bash
   git clone ttps://github.com/Ravitejamuppalla1/DevTown-Backend.git
2. Navigate to the backend folder:
   ```bash
      cd DevTown-Backend
      cd backend
3. Install dependencies:
     
          npm install
4. Run the application using nodemon:
       
            
             nodemon index.js

Technologies Used

     - Node.js
     - Express.js
     - MongoDB with Mongoose
     - AWS DynamoDB
     
Packages Used

     - bcryptjs: Used for hashing passwords.
     - dotenv: For loading environment variables.
     - jsonwebtoken: Used for creating and verifying JSON Web Tokens.
     - validator: Library for data validation.
     - uuid: Generates unique identifiers.
     - cors: Middleware for enabling Cross-Origin Resource Sharing.

Project Structure

         /Backend
           /App
             /controllers
               - task_controller.js
               - users_controller.js
             /middlewares
               - authenticate.js
             /models
               - task.js
               - user.js
            /config
               - Database.js
               - Route.js
            /.env
            /.gitignore
            /index.js
  
     
   
  
   
