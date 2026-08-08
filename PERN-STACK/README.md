# PERN Stack Boilerplate

A starter boilerplate for a PERN stack application using PostgreSQL, Express, React, and Node.js.

## Project Structure

- `backend/` - Express server and API logic
  - `src/` - application entry point and backend source code
  - `controllers/` - request handlers
  - `db/` - database connection setup
  - `middlewares/` - middleware utilities (auth, error handler, multer, etc.)
  - `models/` - application models
  - `routes/` - API route definitions
  - `utils/` - helper utilities
  - `public/` - public assets and temporary files
  - `env.txt` - environment variable references or notes

- `frontend/` - React frontend powered by Vite
  - `src/` - React components, styles, and entry points
  - `public/` - static frontend assets
  - `index.html` - frontend HTML template

## Key Features

- Express API server
- JWT authentication support
- File upload handling with Multer
- Cloudinary integration utilities
- React frontend built with Vite and Tailwind CSS
- PostgreSQL database support via `pg`

## Getting Started

### Backend Setup

1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create your environment variables file (`.env`) using the values from `env.txt` as a reference.
4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
   ```

## Available Scripts

### Backend
- `npm start` - run the backend server using Node
- `npm run dev` - run the backend server with Nodemon

### Frontend
- `npm run dev` - start the Vite development server
- `npm run build` - build the frontend for production
- `npm run preview` - preview the production build
- `npm run lint` - run frontend linting with OXLint

## Notes

- Ensure your PostgreSQL database is running and configured correctly.
- Update the backend `.env` file with secrets for JWT, Cloudinary, and database connection.
- This boilerplate is ready to extend with routes, models, and frontend pages.

## License

This project is provided as-is and can be adapted for personal or commercial use.
