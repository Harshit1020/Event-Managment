
# Task Management Web Application

A full-featured task management application built with **Next.js** as the frontend framework, **Tailwind CSS** for styling, and **Appwrite** for backend services. This app enables users to authenticate, create, and manage events, register attendees, send email notifications, and export data—all with a smooth user interface.

## 🚀 Features

- **🔒 User Authentication**: Secure user registration and login with Appwrite.
- **🗓️ Event Creation**: Admins can easily create new events.
- **📋 Event Listing**: A detailed event list is available for users to browse.
- **👥 Attendee Registration**: Users can register for events, and admins manage attendees.
- **✅ Attendee Management**: Admins can accept or reject attendee registrations.
- **📧 Email Notifications**: Automatic acceptance/rejection emails sent to attendees.
- **🗑️ Event Deletion**: Admins can delete events when needed.
- **📂 Export Data**: Admins can export attendee data to a CSV file for external use.

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Backend**: [Appwrite](https://appwrite.io/)
- **Deployment**: [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/)

## 📦 Installation & Setup

### Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** (v14 or higher)
- **npm** (v6 or higher)
- **Appwrite** account and instance for backend setup

### Steps to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/task-management.git
   ```
   
2. **Navigate to the project directory**:
   ```bash
   cd task-management
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Set up Appwrite**:
   - Follow the Appwrite setup guide to configure authentication, databases, and storage.
   - Add your Appwrite credentials to the `.env` file.

5. **Run the development server**:
   ```bash
   npm run dev
   ```

6. **Visit the app in the browser**:
   Open [http://localhost:3000](http://localhost:3000) to view it.

## 🚀 Deployment

### Vercel

To deploy the app using Vercel:

1. Create a Vercel account.
2. Connect your GitHub repository.
3. Click "Deploy" and follow the prompts.

### Netlify

To deploy using Netlify:

1. Create a Netlify account.
2. Link your GitHub repository.
3. Deploy using their platform.

### Environment Variables

Ensure you configure the following environment variables for production:
- `APPWRITE_PROJECT_ID`: Your Appwrite project ID.
- `APPWRITE_API_ENDPOINT`: The endpoint for your Appwrite API.

## 🤝 Contribution Guidelines

Contributions are always welcome! Here's how you can help:

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature/YourFeature`).
3. **Make your changes** and **commit them** (`git commit -m 'Add new feature'`).
4. **Push to the branch** (`git push origin feature/YourFeature`).
5. Open a **Pull Request**.
