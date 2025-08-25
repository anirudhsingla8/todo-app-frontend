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

The frontend is configured to proxy API requests to the backend running on `http://localhost:3001`.

To use this frontend with the backend:
1. Start the backend server (see backend README)
2. Run `npm run dev` in this directory
3. Open http://localhost:5173 in your browser

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