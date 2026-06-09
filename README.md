# Social AI Automation Frontend

React + Vite frontend for the Social AI Automation app. It handles authentication, brand settings, post generation, approvals, scheduling views, and connected social accounts.

## Tech Stack

- React 19
- Vite
- Tailwind CSS
- Axios
- React Router
- Headless UI
- Lucide React

## Getting Started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

Run linting:

```bash
npm run lint
```

## Backend API

The frontend currently points to the backend at:

```text
http://localhost:8000
```

Update `src/api.js` if your deployed backend URL is different.

## Deployment Notes

- Deploy the contents of this `frontend` folder as the frontend repository.
- Build command: `npm run build`
- Output directory: `dist`
- Make sure the backend deployment allows CORS from the frontend domain.
