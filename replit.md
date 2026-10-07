# Running GARAGE on Replit

This project is a React + Vite demo. The `Start application` workflow runs the Vite development server on port 5000 for the Replit preview.

```bash
npm install
npm run dev -- --host 0.0.0.0 --port 5000
```

To create a production build, run `npm run build`.

The current demo uses mock VIN data and stores garage data in the browser's local storage. Sign-in and SMS verification are simulated; no account or server-side database is configured.
