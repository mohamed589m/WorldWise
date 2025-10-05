# WorldWise

WorldWise is a modern, professional React application built with Vite that allows users to explore cities and countries with interactive maps and detailed information. It features user authentication, dynamic routing, and a clean, responsive UI.

## Features

- Browse and search cities and countries
- Interactive maps powered by Leaflet and React-Leaflet
- User authentication with protected routes
- Dynamic routing with React Router v6
- Lazy loading of pages for optimized performance
- Form for adding or editing city information
- Responsive design for desktop and mobile
- JSON server for local API simulation

## Technologies Used

- React 18
- Vite (build tool)
- React Router DOM (routing)
- Leaflet & React-Leaflet (maps)
- React Datepicker (date selection)
- JSON Server (mock API)
- ESLint (code linting)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mohamed589m/WorldWise.git
   cd worldwise
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

### Development Server

Start the Vite development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

### JSON Server

To simulate a backend API for city data, run the JSON server:

```bash
npm run server
```

This will start the server at `http://localhost:9000`.

### Build for Production

To build the app for production:

```bash
npm run build
```

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## Project Structure

```
src/
  components/       # Reusable UI components (CityList, CountryList, Form, etc.)
  contexts/         # React context providers (CitiesContext, AuthContext)
  hooks/            # Custom React hooks (useGeolocation, useUrlPosition)
  pages/            # Page components (Homepage, Login, Pricing, Product, etc.)
  App.jsx           # Main app component with routing
public/             # Static assets (images, icons)
data/               # JSON data files (cities.json)
```


Thank you for checking out WorldWise!


https://github.com/user-attachments/assets/8b553089-fde3-4982-b5c9-e55d26b63af5

