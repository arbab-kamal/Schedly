# Calendar Scheduling Platform

A robust calendar scheduling platform built with cutting-edge technologies to manage meetings, bookings, and availability with ease.

## 🌟 Features

- 🌐 **Next.js App Router**: Modern routing and performance.
- 🔍 **Nylas Calendar API**: Real-time calendar management.
- 💪 **Meeting Management**: Create, search, and cancel meetings.
- 🔒 **Custom Authentication**: Powered by NextAuth.
  - **OAuth** with Google and GitHub.
- ✏️ **Dynamic Booking Form**: Real-time updates and availability.
- 📆 **Custom Calendar**: Built from scratch—no plugins.
- 👋 **Availability Integration**: Seamless calendar updates.
- 💿 **Database**: Supabase with Prisma ORM.
- 🌐 **Landing Page**: Fully responsive, with dark mode.
- ✅ **Validation**: Server-side validation using Zod and Conform.
- 😱 **Username Validation**: Unique checks for user identification.
- 📧 **Email Confirmation**: Automatic emails and event syncing.
- 🗂️ **File Upload**: Integrated via Uploadthing.
- 🖥️ **Dashboard**: Manage meetings, settings, and availability.
- 🎨 **Styling**: TailwindCSS with Shadcn UI.
- 😶‍🌫️ **Deployment**: Hosted on Vercel.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- NPM/Yarn
- Supabase Account
- Nylas Account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/arbab-kamal/Schedly.git
   cd <project-directory>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create an `.env` file in the root directory based on the provided `.env.example`.

4. Set up your database:

   - Add your `DATABASE_URL` in `.env`.
   - Run Prisma migrations:
     ```bash
     npx prisma migrate dev
     ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Access the app at [http://localhost:3000](http://localhost:3000).

## 🛠 Environment Variables

Create a `.env` file with the following keys:

```env
# Authentication Secrets
AUTH_SECRET=your_secret_here
AUTH_GOOGLE_ID=your_google_id_here
AUTH_GOOGLE_SECRET=your_google_secret_here
AUTH_GITHUB_ID=your_github_id_here
AUTH_GITHUB_SECRET=your_github_secret_here

# Database URL
DATABASE_URL=your_database_url_here

# Application URL
NEXT_PUBLIC_URL=http://localhost:3000

# Nylas API
NYLAS_CLIENT_ID=your_nylas_client_id_here
NYLAS_API_SECRET_KEY=your_nylas_api_secret_key_here
NYLAS_API_URL=https://api.us.nylas.com

# Uploadthing API
UPLOADTHING_SECRET=your_uploadthing_secret_here
UPLOADTHING_APP_ID=your_uploadthing_app_id_here
```

## 🎨 Technologies Used

- **Framework**: Next.js
- **Database**: Supabase Postgres + Prisma ORM
- **API Integration**: Nylas Calendar API
- **Styling**: TailwindCSS and Shadcn UI
- **Validation**: Zod and Conform
- **File Upload**: Uploadthing
- **Deployment**: Vercel

## 📧 Contact

For any inquiries, feel free to contact Arbab Kamal at arbabkamal9@gmail.com.
