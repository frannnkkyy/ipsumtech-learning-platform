
# IpsumTech Learning Platform

<p>
  <img src="https://img.shields.io/badge/Status-Completed-58A96A?style=flat-square" alt="Completed">
  <img src="https://img.shields.io/badge/React-Frontend-1976D2?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Firebase-Platform-E0A92F?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
  <img src="https://img.shields.io/badge/Tailwind_CSS-Responsive_UI-238FC1?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
</p>

Online learning platform developed for **Ipsum Technology**. Users can explore courses, track their learning progress and obtain completion certificates through a responsive web interface.

This repository is published with permission as part of my professional portfolio.

<p align="center">
  <img
    src="./assets/platform-preview.png"
    width="850"
    alt="IpsumTech Learning Platform"
  >
</p>

## Overview

IpsumTech Learning Platform was created to provide users with a centralized space for accessing online training content.

The application includes user authentication, course visualization, progress management and certificate workflows. Firebase provides authentication and data services, while React and Tailwind CSS power the user interface.

## Main features

### User experience

- User registration and authentication
- Course catalog
- Course content visualization
- Learning progress tracking
- Certificate availability after course completion
- Responsive interface for desktop and mobile devices
- Clear navigation between learning sections

### Platform functionality

- Firebase Authentication integration
- Course and user information stored with Firebase
- Real-time information updates
- Cloud functionality through Firebase
- Protected user-specific information
- Firebase Hosting deployment configuration

## Technology stack

| Area | Technology |
|---|---|
| User interface | React |
| Styling | Tailwind CSS |
| Authentication | Firebase Authentication |
| Data | Firebase |
| Cloud backend | Firebase Cloud Functions |
| Hosting | Firebase Hosting |
| Language | JavaScript |

## Screenshots

<table>
  <tr>
    <td align="center">
      <img src="./assets/login-preview.png" width="390" alt="Login screen">
      <br>
      <sub>Authentication</sub>
    </td>
    <td align="center">
      <img src="./assets/courses-preview.png" width="390" alt="Course catalog">
      <br>
      <sub>Course catalog</sub>
    </td>
  </tr>
</table>

<p align="center">
  <img src="./assets/certificate-preview.png" width="650" alt="Course certificate">
  <br>
  <sub>Completion certificate</sub>
</p>

## My contribution

I participated in the development of this application during my experience with Ipsum Technology.

My work included:

- Building and improving React user interfaces
- Creating responsive layouts with Tailwind CSS
- Integrating Firebase authentication
- Connecting application screens with Firebase data
- Implementing course progress workflows
- Supporting certificate functionality
- Configuring and testing the web application
- Documenting the project setup

## Project structure

```text
ipsumtech-learning-platform/
├── functions/              # Firebase Cloud Functions
├── public/                 # Public static assets
├── src/
│   ├── components/         # Reusable interface components
│   ├── pages/              # Main application pages
│   ├── services/           # Firebase and data services
│   ├── App.js              # Root component
│   └── index.js            # Application entry point
├── assets/                 # README screenshots
├── .env.example            # Environment variable template
├── .firebaserc             # Firebase project configuration
├── firebase.json           # Firebase services configuration
├── package.json            # Frontend dependencies and scripts
└── README.md
````

> The exact folder structure may differ. Update this diagram so it matches the repository.

## Getting started

### Requirements

Install:

* Node.js
* npm
* Git

A Firebase project is also required to use authentication and data services.

### Installation

Clone the repository:

```bash
git clone https://github.com/frannnkkyy/ipsumtech-learning-platform.git
```

Open the project:

```bash
cd ipsumtech-learning-platform
```

Install the dependencies:

```bash
npm install
```

Create your local environment file:

```bash
cp .env.example .env
```

Add your Firebase configuration to `.env`.

Start the application:

```bash
npm start
```

Open:

```text
http://localhost:3000
```

## Environment variables

Create `.env.example` with the names of the variables required by the application:

```env
REACT_APP_FIREBASE_API_KEY=
REACT_APP_FIREBASE_AUTH_DOMAIN=
REACT_APP_FIREBASE_PROJECT_ID=
REACT_APP_FIREBASE_STORAGE_BUCKET=
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=
REACT_APP_FIREBASE_APP_ID=
```

Do not add real credentials to `.env.example`.

If your project uses different variable names, replace these names with the ones actually referenced in the source code.

## Firebase Functions

Install the function dependencies:

```bash
cd functions
npm install
```

The `functions` directory contains the cloud-side functionality used by the platform.

> Document the actual functions here. Do not claim functionality that is not present in the source code.

## Available scripts

### Start the development server

```bash
npm start
```

### Create a production build

```bash
npm run build
```

### Run tests

```bash
npm test
```

Only include commands that exist in `package.json`.

## Security considerations

* Environment files are excluded from Git
* User access is handled through Firebase Authentication
* Database access should be protected with Firebase Security Rules
* Debug logs must not be committed
* Administrative credentials must never be included in frontend code

## Future improvements

* [ ] Add automated component tests
* [ ] Improve accessibility
* [ ] Add loading and error states
* [ ] Improve course search and filtering
* [ ] Add administrative reporting
* [ ] Document Firebase Security Rules
* [ ] Add a CI/CD validation workflow

## What I learned

This project helped me strengthen my experience with:

* Building reusable React interfaces
* Creating responsive designs with Tailwind CSS
* Integrating Firebase Authentication
* Managing application data with Firebase
* Organizing a production-oriented frontend project
* Deploying and configuring a Firebase application
* Documenting a project for other developers

## Project context

This application was developed for Ipsum Technology and is published with permission for portfolio presentation.

The repository demonstrates my contribution to the interface, Firebase integration and course-management experience. Company or user-sensitive information is not included.

## Author

**Carlos Constantino**

* Portfolio: https://portafoliofrann.netlify.app/
* LinkedIn: https://www.linkedin.com/in/fcoocarlos/
* GitHub: https://github.com/frannnkkyy
