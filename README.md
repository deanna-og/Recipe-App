# Recipe App

## Starting the Application

### Set up .env
1. Use .env.tpl
2. Rename to .env

### Obtain Spoonacular API Token
1. Go to [Spoonacular API](https://spoonacular.com/food-api).
2. Sign up for an account.
3. Navigate to your profile and locate the section for API keys.
4. Generate a new API key.
5. Copy the API key and add it to the .env file as API_KEY in backend.

### Create Database
1. Visit [ElephantSQL](https://www.elephantsql.com/) and sign up or log in.
2. Create a new instance with the "Tiny Turtle" plan for a free database.
3. Name your database (e.g., `recipe-app-db`) and select the nearest region.
4. Once created, copy the database URL from the details section.
5. Add it to the .env file as DATABASE_URL in backend.

### Backend
1. `cd backend` to navigate to the backend directory in your terminal.
2. Ensure the Spoonacular API key is added to your `.env` file.
3. Run `npm install` to install all necessary dependencies.
4. Start the backend server with `npm start`.

### Frontend
1. Open a new terminal window or tab.
2. `cd frontend` to navigate to the frontend directory.
3. Run `npm install` to install dependencies.
4. Start the frontend server with `npm run dev`.

The frontend of the application should now be accessible in your web browser, and the backend server should be running to handle API requests.

For detailed tutorial steps, visit [FreeCodeCamp Tutorial](https://www.freecodecamp.org/news/full-stack-project-create-a-recipe-app-using-react-node-js/).

