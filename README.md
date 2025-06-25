
# 🌐 Socially

**Socially** is a full-stack modern web app built using the latest features of **Next.js App Router**, powered by **PostgreSQL**, **Prisma**, **Clerk**, and **TypeScript**. It’s a social platform with smooth UI, scalable backend, and fast interactions.

---

## 🚀 Tech Stack

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Database**: PostgreSQL + Prisma ORM
- **Authentication**: Clerk
- **Styling**: Tailwind CSS + Shadcn/UI
- **File Uploads**: UploadThing
- **Data Handling**: Server Actions, Route Handlers, Optimistic Updates
- **Rendering**: Server & Client Components
- **Routing**: Dynamic & Static Routes

---

## ✨ Features

- ✅ App Router with layouts and nested routing
- 🧩 Special files: `loading.tsx`, `error.tsx`, `not-found.tsx`
- 🔐 Auth with Clerk (Login, Signup, Protect Routes)
- 📤 File Uploads via UploadThing
- ⚡ Optimistic UI updates
- 📡 API Integration using Next.js Route Handlers
- 🔄 Smart data fetching, caching & revalidation
- 🧠 Fully typed with TypeScript
- 🎨 Clean UI using Tailwind CSS & shadcn/ui

---

## 📁 Project Structure

```
/socially
├── app/                  # App Router directory
│   ├── layout.tsx
│   ├── page.tsx
│   ├── loading.tsx
│   ├── error.tsx
│   └── not-found.tsx
├── components/           # Reusable UI components
├── lib/                  # Utilities and helpers
├── prisma/               # Prisma schema and client
├── public/               # Static files
├── styles/               # Global styles
├── uploadthing/          # Upload config
├── middleware.ts         # Clerk middleware
└── ...
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/socially.git
cd socially
```

### 2. Install dependencies

```bash
pnpm install   # or npm install
```

### 3. Set up environment variables

Create a `.env` file in the root directory:

```env
DATABASE_URL=your_postgres_url
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
UPLOADTHING_SECRET=your_uploadthing_secret
UPLOADTHING_APP_ID=your_uploadthing_app_id
```

### 4. Set up Prisma

```bash
npx prisma generate
npx prisma migrate dev --name init
```

### 5. Run the development server

```bash
pnpm dev   # or npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

---

## 🚀 Deployment

Deploy to **Vercel** in 3 steps:

1. Push to GitHub
2. Import your repo into Vercel
3. Add your `.env` values in Vercel dashboard

---
---

## 👨‍💻 Author

Learnt with @burakorkmez
