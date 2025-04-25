<h1>Journey jolt</h1>

Journeyjolt is an intelligent trip planning app designed to make travel smoother and smarter. With AI at its core, it delivers personalized travel itineraries based on your preferences and needs.

### 🔑 Key Features:
- **Tailored Suggestions:** Based on your input, the app recommends the best destinations, hotels and experiences.
- **Automated Itineraries:** No need to plan manually. Get a complete plan with travel times, sequences and preferences considered.
- **Clean & Responsive UI:** Built for a smooth user experience across all screen sizes.

---

## 🛠️ Tech Stack

This project is built with modern web technologies and powerful APIs:

* ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
* ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
* ![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
* ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
* ![Gemini AI](https://img.shields.io/badge/Gemini%20AI-FF5F00?style=for-the-badge&logo=google&logoColor=white)
* ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
* ![Auth0](https://img.shields.io/badge/Auth0-000000?style=for-the-badge&logo=auth0&logoColor=white)
* ![React Hot Toast](https://img.shields.io/badge/React%20Hot%20Toast-FF5733?style=for-the-badge&logo=react&logoColor=white)

---

## ⚙️ Local Setup

### Prerequisites
Make sure you have:
- Node.js (v16 or higher) → [Download](https://nodejs.org/en)
- Visual Studio Code → [Download](https://code.visualstudio.com/)

### API Config

You’ll need to set up these APIs to make full use of journey-jolt:

- **Google Cloud (Maps, Places, Geocoding)**
- **Gemini AI**
- **Auth0 for authentication**

Paste your credentials in the `.env` file like this:

```env
 VITE_GOOGLE_MAP_API_KEY = "your-google-api-key"
     VITE_GEMINI_API_KEY = "your-gemini-api-key"
     VITE_AUTH0_CLIENT_ID = "your-auth0-client-id"
     VITE_DOMAIN_NAME = "your-auth0-domain-name"
     VITE_FIREBASE_API_KEY = "your-firebase-api-key"
     VITE_FIREBASE_AUTH_DOMAIN = "your-firebase-auth-domain"
     VITE_FIREBASE_PROJECT_ID = "your-firebase-project-id"
     VITE_FIREBASE_STORAGE_BUCKET = "your-firebase-storage-bucket"
     VITE_FIREBASE_MESSAGING_SENDER_ID = "your-firebase-messaging-sender-id"
     VITE_FIREBASE_APP_ID = "your-firebase-app-id"
     VITE_MEASUREMENT_ID = "your-firebase-measurement-id"
```

### 🧪 Run Locally

```bash
git clone https://github.com/AtharvaKulkarniIT/journey-jolt.git
cd journey-jolt
npm install
npm run dev
```

