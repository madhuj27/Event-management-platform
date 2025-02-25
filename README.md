# Event Management Platform

## Overview
The **Event Management Platform** is a web-based application designed to streamline the process of event planning, registration, and management. It provides users with an intuitive interface to create, manage, and track events efficiently.

## Features
- **User Authentication**: Secure login and registration system.
- **Event Creation**: Easily create and customize events.
- **Event Registration**: Allow users to register for events.
- **Dashboard & Analytics**: View event details, attendee data, and analytics.
- **Notifications & Reminders**: Send automated reminders to attendees.
- **Payment Integration**: Support for event ticket purchases.
- **Admin Panel**: Manage events, users, and settings.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: Supabase (PostgreSQL-based backend-as-a-service)
- **Authentication**: Supabase Auth
- **Hosting**: Vercel / Netlify for frontend, Supabase for backend

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/madhuj27/Event-management-platform.git
   cd Event-management-platform
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
3. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add the following environment variables:
     ```env
     REACT_APP_SUPABASE_URL=your_supabase_url
     REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
     ```
4. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
5. Open `http://localhost:3000/` in your browser.

## Deployment
The platform can be deployed using services like Vercel or Netlify for the frontend and Supabase for the backend.

### Deploy to Vercel
1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Deploy:
   ```bash
   vercel
   ```

## License
This project is licensed under the [MIT License](LICENSE).


