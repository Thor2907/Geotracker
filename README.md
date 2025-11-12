```tsx
import React from 'react';

export const GeoTrackerLogo: React.FC<{ isLight?: boolean }> = ({ isLight = false }) => (
  <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" className="w-full h-full">
    <path d="M12 21C16.9706 21 21 16.9706 21 12C21 7.02944 16.9706 3 12 3C7.02944 3 3 7.02944 3 12C3 16.9706 7.02944 21 12 21Z" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
    <path d="M12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15Z" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
    <path d="M21 12H19" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
    <path d="M5 12H3" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
    <path d="M12 5V3" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
    <path d="M12 21V19" stroke={isLight ? "#FFFFFF" : "#007BFF"} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
  </svg>
);
```

---

## ✨ Features

GeoTracker provides a seamless experience for both administrators and employees with role-based access and a rich set of features.

### 👨‍💼 Admin Features

- **Dashboard Overview:** A comprehensive dashboard to monitor all employee activities.
- **Attendance Logs:** View detailed attendance records for all employees, including check-in and check-out times.
- **CSV Export:** Export attendance logs to a CSV file for reporting and analysis.
- **Employee Management:** Add and remove employees with ease.
- **Geofence Management:** Set and update custom geofences for each employee to define their work area.

### 👷 Employee Features

- **Simple Check-in/Check-out:** Mark attendance with a single click.
- **Geolocation Validation:** The application automatically verifies if the employee is within the designated geofence during check-in.
- **Attendance History:** View personal attendance records.
- **Real-time Feedback:** Receive instant feedback on attendance status and geofence validation.

---

## 🚀 Tech Stack

GeoTracker is built with a modern and robust technology stack to ensure a high-quality user experience.

- **Frontend:** [React](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Mapping:** [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/)
- **Data:** JSON files with `localStorage` caching

---

## 🏁 Getting Started

Follow these instructions to get a local copy of GeoTracker up and running on your machine.

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v14 or higher)
- [npm](https://www.npmjs.com/) (or any other package manager like [Yarn](https://yarnpkg.com/) or [pnpm](https://pnpm.io/))

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/geotracker.git
    cd geotracker
    ```

2.  **Install the dependencies:**

    ```bash
    npm install
    ```

### Running the Application

1.  **Start the development server:**

    ```bash
    npm run dev
    ```

2.  **Open the application in your browser:**

    Navigate to `http://localhost:5173` (or the URL provided by Vite) in your web browser to use the application.

---

## 📸 Screenshots

*Please provide screenshots of the application to be included here.*

---

<div align="center">
  <p>Open Source Attendance Tracking Solution</p>
</div>
