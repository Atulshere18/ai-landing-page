Here’s a `README.md` file for your **Frontend**:

---

# AI Landing Page Frontend

This repository contains the frontend for an AI Landing Page application. It allows users to submit their details, which are sent to the backend for storage.

## Features

* Interactive form for capturing user leads.
* Responsive design for seamless user experience across devices.
* API integration for storing user data.

## Tech Stack

* **React.js**: Frontend framework.
* **CSS**: Styling for the application.
* **React Hook Form**: Form handling.
* **Deployed on**: https://ai-agent-landing-three.vercel.app/

## Prerequisites

Ensure you have the following installed:

* Node.js (v14 or higher)
* A package manager (npm or yarn)
* A text editor or IDE (e.g., VS Code)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ai-landing-page-frontend.git
   cd ai-landing-page-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Update the API URL in your `LeadForm.js` or appropriate file:

   ```javascript
   const API_URL = "https://ai-landing-page-backend-8.onrender.co/api/store-lead";
   ```

4. Start the development server:

   ```bash
   npm start
   ```

   The app will run at `http://localhost:3000`.

## Usage

1. Open the application in your browser at `http://localhost:3000`.
2. Fill out the lead form with your details (name, email, phone number).
3. Submit the form to store the data.

## Deployment

The frontend is deployed on [Vercel](https://vercel.com/) (or any other platform). You can access it at:

* Deployed URL: `https://vercel.com/atulshere18s-projects/ai-agent-landing

## Troubleshooting

### Common Issues

1. **CORS Errors**:

   * Ensure the backend allows requests from your deployed frontend URL.
   * Check the API URL in your frontend code and ensure it's correct.

2. **Form Submission Issues**:

   * Verify the API endpoint in `LeadForm.js`.
   * Check browser console logs for errors.

3. **Styling Issues**:

   * Ensure CSS files or libraries are correctly imported.

