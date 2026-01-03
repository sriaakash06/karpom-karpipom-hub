# Karpom Karipipom - Smart Learning Platform for 12th Students

## Overview

**Karpom Karipipom** is an integrated tutor, class, and student management platform specifically designed for **12th standard students**. This application helps track attendance, access subject-wise classes, and manage student performance with AI-powered learning tools.

## Features

- **Student Dashboard**: Comprehensive view of student progress, schedules, and analytics.
- **Subject Management**: Access detailed subject information, chapters, and resources.
- **Attendance Tracking**: View detailed attendance history and reports.
- **User Authentication**: Secure Login and Signup functionality for students and tutors.
- **Responsive Design**: Modern, responsive interface built for all devices.

## Tech Stack

- **Frontend Framework**: [React 18](https://react.dev/) with [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [Shadcn UI](https://ui.shadcn.com/) / [Radix UI](https://www.radix-ui.com/)
- **State & Data Fetching**: [TanStack Query](https://tanstack.com/query/latest)
- **Routing**: [React Router DOM](https://reactrouter.com/)
- **Forms & Validation**: [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)
- **Data Visualization**: [Recharts](https://recharts.org/)
- **Icons**: [Lucide React](https://lucide.dev/)

## Getting Started

### Prerequisites

- **Node.js** (v18 or higher recommended)
- **npm** or **bun** package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd karpom-karipipom-hub-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or if using bun
   bun install
   ```

### Running the Application

Start the development server:

```bash
npm run dev
```

The application will be hosted at `http://localhost:8080` (or the port shown in your terminal).

### building for Production

To create a production-ready build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Project Structure

- `src/pages`: Main application pages (Home, Dashboard, Login, etc.)
- `src/components`: Reusable UI components.
- `src/lib`: Utility functions and helpers.
- `public`: Static assets (favicons, images).

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

© 2024 Karpom Karipipom. All Rights Reserved.
