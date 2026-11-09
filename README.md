# Travel Agency Site

## Overview

This travel agency prototype follows a flight search into a booking workflow. A visitor can filter flights, open a booking detail page, and use an account to access protected pages. The project uses Express and EJS to build pages on the server, with MongoDB records connecting flights, airports, airlines, bookings, and users.

## How it’s built

- **Search and booking.** [Flight routes](routes/flightRoutes.js) turn submitted search criteria into flight queries and handle booking details.
- **Account and navigation.** Express sessions support login and protected routes. [EJS templates](views/) and shared partials render the site.
- **Data modeling.** [Mongoose models](models/) represent the travel and account data behind the interface.

## Run or explore locally

Install dependencies with `npm install`. In [app.js](app.js), point the MongoDB connection to a database you control and populate it with sample travel data to exercise the search. Run `node app.js` and open `http://localhost:3000` after the database connects.
