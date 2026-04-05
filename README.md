# TravelBooker

TravelBooker is a travel booking platform built with HTML, CSS, and vanilla JavaScript.

The current version is designed for Sri Lanka domestic travel only. All packages, destinations, hotel options, dashboards, and support flows are centered around travel within Sri Lanka.

## Features

- Sri Lanka-only package catalog
- Sri Lanka hotel and destination browsing
- Package filtering by location, duration, budget, and sort order
- Hotel filtering by location, category, budget, and sort order
- Package and hotel detail views
- Booking flow with payment and confirmation UI
- Role-based dashboards for customers, agents, corporate users, and admins
- Group travel coordination views and modals
- AI travel assistant with Sri Lanka-focused canned responses
- Custom dropdown styling applied consistently across the system
- Responsive layout for desktop and mobile

## Tech Stack

- `HTML5`
- `CSS3`
- `Vanilla JavaScript`

No framework or build step is required.

## Project Structure

```text
travel booker/
|-- index.html
|-- styles.css
|-- app.js
|-- README.md
|-- # Code Citations.md
```

## How To Run

Because this is a static frontend project, you can run it with any local web server.

Example with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

If you use VS Code, `Live Server` also works well.

## Main Pages And Modules

The app is organized inside a single HTML entry point with JavaScript-rendered sections:

- `Home`
- `Destinations`
- `Packages`
- `Booking`
- `Login / Signup`
- `Dashboard`
- `Legal / Info pages`
- `AI Assistant`

Core logic lives in:

- [index.html](C:\Users\DELL\Downloads\Agile PM GCW\travel booker\index.html)
- [styles.css](C:\Users\DELL\Downloads\Agile PM GCW\travel booker\styles.css)
- [app.js](C:\Users\DELL\Downloads\Agile PM GCW\travel booker\app.js)

## Current Data Model

The app currently uses in-file JavaScript datasets for:

- `PACKAGES`
- `HOTELS`
- `bookingHistory`
- `AGENT_CLIENTS`
- `ADMIN_USERS`

These are defined in [app.js](C:\Users\DELL\Downloads\Agile PM GCW\travel booker\app.js).

## Sri Lanka Domestic Travel Scope

This project has been cleaned up to support a domestic Sri Lanka travel model.

That means:

- No international destinations should be shown
- No flight or airport-based package logic should remain
- No visa or immigration-based travel flows should remain
- Pricing should reflect local travel components only
- Dashboards and bookings should point to active Sri Lanka package data

## Notes

- This project currently uses mock/static data rather than a live backend
- Dashboard sections include demo content and UI flows
- Payment, booking, and support interactions are frontend simulations

## Future Improvements

- Connect packages, hotels, and bookings to a real backend/database
- Add persistent authentication
- Add real booking validation and payment integration
- Add admin content management for packages and hotels
- Add automated tests for filtering, booking, and dashboard flows

