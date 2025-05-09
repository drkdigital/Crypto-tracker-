## Deployment Documentation

This document provides instructions for deploying the Blockchain Tracker web application.

### Prerequisites

*   Node.js (version 14 or later)
*   npm (Node Package Manager)

### Running the Application Locally

1.  Clone the repository: `git clone https://github.com/example/blockchain-tracker.git`
2.  Navigate to the project directory: `cd blockchain-tracker`
3.  Install dependencies: `npm install`
4.  Start the development server: `npm run dev`
5.  Open your web browser and go to `http://localhost:3000`

### Deployment to Production

For production deployment, you can use platforms like Vercel, Netlify, or AWS Amplify. These platforms often provide seamless integration with Next.js projects.

1.  **Build the application:** Run `npm run build` to create an optimized production build in the `out` directory.
2.  **Deploy the build:** Follow the specific instructions for your chosen hosting platform to deploy the contents of the `out` directory.

### Important Notes

*   Ensure that the backend API is running and accessible by the frontend application.
*   Configure environment variables for API keys and other sensitive information.
*   For optimal performance, consider using a Content Delivery Network (CDN) to serve static assets.
