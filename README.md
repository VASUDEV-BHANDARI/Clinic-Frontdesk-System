# Clinic Management Frontend

A Next.js frontend for the clinic management system.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

The frontend will run on `http://localhost:3000`

## Features

- **Authentication**: Login with username/password
- **Dashboard**: View and manage patient queue and available doctors
- **Queue Management**: Add patients to queue, update status and priority
- **Doctor List**: View all doctors and their current status
- **Appointment Management**: Schedule, view, and update appointments
- **Responsive Design**: Works on desktop and mobile devices

## Pages

- `/` - Login page
- `/dashboard` - Main dashboard with queue and doctors
- `/appointments` - Appointment management page

## Default Login Credentials
- Username: `admin`
- Password: `admin123`

## Technologies Used

- Next.js (Pages Router)
- React Context API for state management
- Tailwind CSS for styling
- Fetch API for backend communication 