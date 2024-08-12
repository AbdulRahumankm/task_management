# task_management

This is a web-based Task Management Application built using modern technologies. It allows users to create, manage, and track their tasks efficiently.

#Features
User Authentication: Secure authentication with Clerk.
Task Management: Create, update, delete, and manage tasks.
Responsive Design: Fully responsive design using Tailwind CSS.
Database Integration: Data persistence with MongoDB.
Real-Time Updates: Dynamic user experience with real-time updates.
Technologies Used
Next.js: A powerful React framework for building server-side rendered applications.
Clerk: Authentication and user management service.
MongoDB: NoSQL database for storing tasks and user data.
Tailwind CSS: Utility-first CSS framework for styling the application.
Getting Started
Follow these instructions to set up the project locally.

#Prerequisites
Node.js installed on your machine.
MongoDB instance running (either locally or using a service like MongoDB Atlas).
Clerk account for managing authentication.
Installation
Clone the repository:


git clone https://github.com/yourusername/task-management.git
cd task-management
Install the dependencies:


npm install
Set up environment variables:

Create a .env.local file in the root directory with the following content:


NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
CLERK_API_KEY=<your-clerk-api-key>
MONGODB_URI=<your-mongodb-uri>
Run the development server:


npm run dev
The application will be available at http://localhost:3000.

Deployment
The application is ready to be deployed to a platform like Vercel.


