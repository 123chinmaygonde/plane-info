# Overview
This is a React-based flight status board application built using TypeScript. 
The app retrieves flight details from an API, updates the data at regular intervals, and allows users to view 
detailed information about a flight.

# Features
# Flight Table: Displays flights with real-time updates
#  Detail View: Clicking a flight row navigates to a detailed view.
#  Navigation: Uses React Router for seamless navigation.
#  Error Handling: Provides feedback for API errors or unavailable flight details.

# Tech Stack
 # Frontend: React 
# State Management: useState, useEffect (React Hooks)
 # Routing: React Router
 # API Calls: Axios / Fetch API

 # API Details
 # Fetch All Flights
 GET https://flight-status-mock.core.travelopia.cloud/flights
# Fetch Specific Flight
GET https://flight-status-mock.core.travelopia.cloud/flights/:id

# Install Dependencies
npm install

# Run The Development Server
 npm start

# Deployment On Vercel
https://vercel.com/chinmay-vilas-gondes-projects/plane-info





