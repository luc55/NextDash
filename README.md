# Next.js Dashboard Application

A modern and responsive admin dashboard built with Next.js, TypeScript, Tailwind CSS, and shadcn/ui.

## 🚀 Features

- **Authentication Pages**  
  - **Login Page**: A clean login form with email and password fields, validation, and a link to the registration page.  
  - **Register Page**: A registration form with name, email, password, and password confirmation fields with validation.  

- **Dashboard Layout**  
  - **Sidebar**: A responsive sidebar with navigation links to different sections of the dashboard.  
  - **Header**: A top navigation bar with search functionality, notifications, and a user profile dropdown.  

- **Dashboard Pages**  
  - **Main Dashboard**: Features overview charts, recent sales, and key statistics.  
  - **Users Page**: A data table showing user information with sorting and pagination.  
  - **Settings Page**: User profile and notification settings.  

- **Additional Features**  
  - ✅ **Responsive Design** – Works on mobile and desktop devices.  
  - 🌗 **Dark/Light Mode** – Theme toggle with system preference detection.  
  - 📊 **Interactive Charts** – Using Recharts for data visualization.  
  - ✅ **Form Validation** – Using React Hook Form and Zod.  
  - 🔔 **Toast Notifications** – For user feedback.  

## 🛠️ Tech Stack

- **Frontend:** [Next.js](https://nextjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) with [shadcn/ui](https://ui.shadcn.com/)
- **State Management:** React Context API / Zustand
- **Charts:** [Recharts](https://recharts.org/)
- **Form Validation:** [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)
- **Notifications:** [react-hot-toast](https://react-hot-toast.com/)

## 🔧 Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
2. **Install dependencies:**
    npm install
3. **Start the development server:**
    npm run dev
4. **Open the app in your browser:**
    http://localhost:3000

## 📂 Project Structure

├── 📁 components     # Reusable UI components
├── 📁 pages          # Next.js pages (Login, Register, Dashboard, etc.)
├── 📁 hooks          # Custom React hooks
├── 📁 lib            # Utility functions
├── 📁 styles         # Global and component styles
└── 📄 README.md      # Project documentation