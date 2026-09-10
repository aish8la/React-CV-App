# React CV App

A small React application for creating and previewing a simple CV or resume. The app lets you edit personal details, manage education entries, and add or update work experience before viewing the final formatted CV.

## Features

- Edit basic profile information such as name, email, and phone number
- Add, update, and delete education entries
- Add, update, and delete work experience entries
- View a live CV preview alongside the editing form
- Built with React and Vite for a lightweight frontend workflow

## Tech Stack

- React
- Vite
- JavaScript
- CSS

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open the local URL shown in the terminal to use the app.

## Production Build

To create a production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Project Structure

- `src/App.jsx` – root application entry
- `src/components/` – CV form and preview components
- `src/logic/dataHandlers.js` – default CV data and helper functions
- `src/styles/` – application styling

## Notes

This project uses a simple in-memory data model for the CV content, so the app is ideal for learning React state management and form-driven UI patterns.
