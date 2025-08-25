# React Todo App (Frontend)

This is the frontend portion of the React Todo application.

## Project Structure

- `src/` - Source code for the React application
- `public/` - Static assets
- `src/components/` - React components
- `src/services/` - Service modules for API calls
- `src/assets/` - Images and other assets

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

4. Preview the production build:
   ```bash
   npm run preview
   ```

## Development

The frontend is configured to proxy API requests to the backend. You can configure the backend URL by creating a `.env` file in the root of the project.

To use this frontend with the backend:
1. Create a `.env` file in the root of the project. See the "Environment Variables" section for more details.
2. Start the backend server (see backend README)
3. Run `npm run dev` in this directory
4. Open http://localhost:5173 in your browser

## Environment Variables

To run the frontend, you can create a `.env` file in the root of the project and add the following environment variable:

- `VITE_BACKEND_URL`: The URL of the backend server. Defaults to `http://localhost:3000`.

Example `.env` file:

```
VITE_BACKEND_URL=https://todo-app-backend-vercel.vercel.app/
```

## API Endpoints

The frontend communicates with the backend through the following API endpoints:
- `/api/auth/login` - User login
- `/api/users/signup` - User registration
- `/api/todos` - Todo operations (GET, POST, PUT, DELETE)

## Technologies Used

- React
- Vite
- Material UI
- JavaScript/JSX