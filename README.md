Github Links:

https://github.com/syoung466/cytellix-frontend

https://github.com/syoung466/cytellix-backend

Requirements:
1. Have "npm" installed
2. Have Angular CLI (npm install -g @angular/cli) 
3. Have Angular Material (npm add @angular/material)

Instructions:
1. Git clone both the frontend and backend repositories.
2. Create a folder to store the project.
3. Copy all the files from the "cytellix-frontend" repo and the backend folder from the 
    "cytellix-backend" repo into the folder you created in step 2.
4. Navigate into the folder you made in step 2 in the terminal 
    and run the command "npm install".
5. Run the command "npm run start:server".
6. Open a separate terminal and run the command "ng serve".
7. Open/Navigate to the localhost link returned in the terminal.

Information about the application:
- Users can sign up and log in. You cannot sign up with an email that is already registered.
- Users can create new posts with an attached image. Images are required. Title's must be at least 3 characters.
- Users can edit and delete only their own posts.
    - The option to edit and delete a post is not available for anyone except the user who posted it.
