# Gym Website Template 💪

A reusable full-stack gym website template built with HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB.

## Features

* Responsive gym website design
* Home, About, Programs, and Membership sections
* Interactive program details
* Membership plan selection
* Enquiry form with server-side validation
* MongoDB integration for storing enquiries
* Admin login and protected enquiry dashboard
* Session-based authentication
* MongoDB-backed session storage
* Rate limiting for login and enquiry endpoints

## Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication & Sessions:** express-session, connect-mongo
* **Configuration:** dotenv

## Getting Started

### Prerequisites

* Node.js and npm
* A MongoDB database (local MongoDB or MongoDB Atlas)

### Installation

1. Install the project dependencies:

   ```bash
   npm install
   ```

2. Create a `.env` file in the project root using `.env.example` as a reference.

3. Add your MongoDB connection string, admin credentials, and a strong, unique session secret to `.env`.

4. Start the server:

   ```bash
   node server.js
   ```

5. Open `http://localhost:3000` in your browser.

## Security Notes

* Never commit `.env` or expose database credentials.
* Use strong admin credentials and a unique session secret.
* Configure HTTPS and secure cookies for production.
* Review database permissions and environment variables before deployment.

## Project Status

Reusable starter template. Test the configuration and all features after customizing it for a new gym. Production deployment and live-environment testing are pending.

## Author

Aditya Gautam

GitHub: [@adityagtm2407-cloud](https://github.com/adityagtm2407-cloud)

