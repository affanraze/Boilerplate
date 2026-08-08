# MERN Stack Boilerplate

A lightweight MERN stack boilerplate with a React + Vite frontend and an Express + MongoDB backend.

## Features

- React frontend built with Vite
- Tailwind CSS ready setup
- Express server using ES modules
- MongoDB support via Mongoose
- JWT authentication and cookie parsing
- File upload handling with Multer
- Cloudinary support for media uploads
- Error handling middleware and reusable API helpers

## Folder Structure

- `backend/`
  - `src/`
    - `controllers/`
    - `db/`
    - `middlewares/`
    - `models/`
    - `routes/`
    - `utils/`
  - `app.js`
  - `index.js`
  - `env.txt`
- `frontend/`
  - `src/`
  - `public/`
  - `index.html`
  - `vite.config.js`

## Prerequisites

- Node.js 18+ (recommended)
- npm or yarn
- MongoDB instance or MongoDB Atlas cluster
- Cloudinary account if using media upload features

## Setup

1. Clone the repository

```bash
git clone <your-repo-url>
cd MERN-STACK
```

2. Install backend dependencies

```bash
cd backend
npm install
```

3. Install frontend dependencies

```bash
cd ../frontend
npm install
```

4. Configure environment variables

Create a `.env` file in `backend/` or update `env.txt` with your values:

```bash
PORT=5000
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
CLOUDINARY_CLOUD_NAME=<your-cloud-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
```

5. Start the backend server

```bash
cd ../backend
npm start
```

6. Start the frontend development server

```bash
cd ../frontend
npm run dev
```

## Available Scripts

### Backend

- `npm start` — starts the backend with `nodemon` watching `src/index.js`

### Frontend

- `npm run dev` — starts Vite development server
- `npm run build` — builds the production frontend
- `npm run preview` — previews the production build
- `npm run lint` — runs `oxlint`

## Notes

- The backend uses ES modules (`type": "module"`).
- Update CORS and API base paths in the frontend as needed.
- Ensure MongoDB and Cloudinary credentials are valid before running.

## License

This boilerplate is open source and free to use.
