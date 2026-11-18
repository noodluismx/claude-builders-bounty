# CLAude.md for Next.js + SQLite SaaS Project

## Stack & Versions
- **Next.js**: 15 App Router
- **SQLite**: better-sqlite3 or Turso

## Folder Structure
- `pages`: Contains the main application routes.
- `components`: Reusable UI components.
- `lib`: Utility functions and logic.
- `styles`: CSS stylesheets.

## SQL / Migration Conventions
- Use of better-sqlite3's transactional migrations to ensure data integrity.

## Component Patterns
- Encourages the use of functional components, hooks, and context API for state management.

## What We Don't Do (and Why)
- Avoids complex state management libraries like Redux or MobX in favor of Next.js built-in features.

## Dev Commands
- `npm run dev`: Starts the development server.
- `npm run build`: Builds the project for production.
- `npm run test`: Runs tests using Jest.

## Testing
A new Next.js project was created, the `CLAUDE.md` was pasted into the project, and Claude Code confirmed it understood the context without asking clarifying questions.