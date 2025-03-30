# Sher - The Ultimate Calendly Clone

Sher is a modern, full-stack call booking application designed to streamline meeting scheduling with seamless automation, a responsive UI, and robust authentication. Built from scratch, this project showcases innovative implementations and integrations for an efficient and user-friendly experience.

## 🚀 Key Features

- **Google Authentication**: Secure login via Clerk for effortless access using Google accounts.
- **Event Creation**: Users can create public/private events with customizable durations, descriptions, and availability settings.
- **Google Calendar Integration**: Meetings sync automatically with both users' and invitees' Google Calendars, with Google Meet links generated instantly.
- **Custom User Pages**: Each user gets a unique URL for easy meeting scheduling.
- **Meeting Management**: View, cancel, and manage past/upcoming meetings with email notifications.
- **Production-Grade Error Handling**: Ensures reliability in username validation and meeting scheduling.
- **Fully Responsive UI**: Built with Next.js, Tailwind CSS, and Shad CN UI for modern aesthetics.

## 🛠️ Tech Stack & How It’s Used

### **Frontend:**
- **Next.js**: Server-rendered React framework used for optimal performance and seamless navigation.
- **Shad CN UI**: Pre-built, customizable UI components (buttons, avatars, carousels, modals) for fast and modern design.
- **Tailwind CSS**: Utility-first CSS framework enabling dynamic and visually appealing designs.

### **Backend:**
- **Neon DB (PostgreSQL)**: Cloud-native database for efficient storage and retrieval of user data, events, and availability.
- **Google Calendar API**: Automates event creation and scheduling directly into Google Calendar with Meet link generation.

### **Authentication:**
- **Clerk**: Provides secure, scalable authentication and user management with Google sign-in support.

### **Form Handling & Validation:**
- **React Hook Form**: Ensures optimal form state management.
- **Zod Validation Library**: Enforces strict validation rules for reliable data entry.

## 🔥 What’s Innovative?
- **Automated Calendar Syncing**: Google Calendar API integration ensures frictionless scheduling.
- **Dynamic Event Pages**: Each user has a personalized scheduling page with real-time availability.
- **Optimized UI/UX**: Leveraging Shad CN UI and Tailwind CSS, the design maintains a clean, intuitive user experience.
- **Advanced Error Handling**: Ensures smooth functionality even in production environments.

## 🏃‍♂️ How to Run the Project

### **Prerequisites:**
- Install [Node.js](https://nodejs.org/)
- Set up a PostgreSQL database on Neon
- Create a Google API project for Calendar integration

### **Steps to Set Up & Run:**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sher.git
   cd sher
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables by creating a `.env` file:
   ```bash
   DATABASE_URL=<your_neon_db_url>
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
   CLERK_SECRET_KEY=<your_clerk_secret_key>
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📌 Final Thoughts
Sher is a testament to the power of modern web technologies and efficient scheduling automation. Developed entirely from scratch, this project demonstrates mastery of Next.js, database integrations, authentication handling, and real-world API usage. 🚀

