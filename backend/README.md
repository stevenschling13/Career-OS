# Backend

This directory contains the backend of the Career OS application, built with Node.js, Express, and integrated with Gmail, Google Calendar, and job source APIs. It provides REST or GraphQL endpoints for frontend consumption and handles authentication, job data, and scheduling.

## Structure

* `src/` - Source code for the Express server, API routes, services, and utilities.
* `scripts/` - Automation and seed scripts.
* `prisma/` - Database schema and migrations (if using Prisma).

## Development

Install dependencies and run the development server:

```
npm install
npm run dev
```

The API server will run at http://localhost:4000 or the configured port.
