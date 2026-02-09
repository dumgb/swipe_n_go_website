# Swipe N Go - Dublin Activity Planner

Hi! This is Swipe N Go! It's a web app that helps people plan trips in Dublin.

Created by Dubem Mgbakor and Ian McCormac.

**Run locally (VS Code / Windows)**

Prerequisites:
- Node.js (v18+ recommended)
- npm (comes with Node)
- Git (optional)
- VS Code

1. Open the project in VS Code (File → Open Folder).
2. Open an integrated terminal (Terminal → New Terminal).
3. Install dependencies:

   npm install

4. Start the app (development): choose one of the options below depending on your terminal.

  - Recommended (Git Bash, WSL, macOS):

    npm run dev

  - PowerShell (Windows):

    $env:NODE_ENV = "development"; npx tsx server/index.ts

  - Cross-platform (works on Windows, macOS, Linux):

    npx cross-env NODE_ENV=development tsx server/index.ts

Notes:
- The server listens on port `5000` by default. You can set `PORT` to use a different port.
- When the server starts you'll see a message like: `Server running on http://127.0.0.1:5000` — open that URL in your browser.
- If you prefer to run the client only (Vite dev server):

  npm run dev:client


Production build:

1. Build the app:

   npm run build

2. Start production server:

   npm start

Tech stack

- React, Vite, Tailwind CSS, Express (Node) and Drizzle ORM.

Credits

- Images sourced from stock libraries.
- Navigation simulates Google Maps but doesn't use a paid API.
