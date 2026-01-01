# Smart Job 🚀

A modern, high-performance job board platform built with React 19, Vite, and Tailwind CSS v4. This platform provides a seamless experience for both job seekers and recruiters with role-based access control and real-time state management.

## ✨ Features

### 👤 For Job Seekers
- **Smart Job Search**: Filter and find jobs based on categories, location, and keywords.
- **Profile Management**: Build your professional profile, upload resumes, and manage avatars.
- **Application Tracking**: Keep track of all your applications and their current status.
- **Saved Jobs**: Save interesting opportunities to apply later.

### 🏢 For Recruiters
- **Job Management**: Create, edit, and manage job listings with ease.
- **Candidate Pipeline**: View and manage applications for your posted jobs.
- **Recruiter Verification**: Secure verification process for posting official job listings.
- **Company Profile**: Showcase your company to attract the best talent.

## 🛠️ Tech Stack

- **Frontend**: [React 19](https://react.dev/), [Vite 7](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) (using `@tailwindcss/vite`)
- **State Management**: [TanStack Query v5](https://tanstack.com/query/latest)
- **Routing**: [React Router v7](https://reactrouter.com/)
- **API Client**: [Axios](https://axios-http.com/)
- **Backend/Auth**: FastAPI + [Supabase](https://supabase.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **UI Components**: Headless UI + Custom components with `class-variance-authority`

## 🚀 Getting Started

### Prerequisites
- Node.js (Latest LTS recommended)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ASTU-group/smartjob_frontend.git
   cd job-portal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory and add your Supabase credentials:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   VITE_API_URL=your_backend_api_url
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

## 🏗️ Project Structure

```text
src/
├── api/          # Axios instance and API hooks
├── components/   # Reusable UI components
├── contexts/     # React Contexts (Auth, etc.)
├── layouts/      # Page layout wrappers
├── lib/          # Utility functions and shared instances
├── pages/        # Route components (Auth, Dashboard, Seeker, Employer)
├── types/        # TypeScript interfaces and types
└── utils/        # Helper functions
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
