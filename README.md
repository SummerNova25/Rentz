# Rentz

Rentz is a full-stack rental platform built with **Next.js**, **Prisma**, **NextAuth**, and **Cloudinary**. It enables users to browse, list, and rent properties with ease, all wrapped in a modern user interface.

---

## Features

- Authentication using GitHub via NextAuth
- Database integration with Prisma and PostgreSQL
- Cloudinary for image uploading and hosting
- Fully typed backend using TypeScript and API routes
- Seamless developer experience using hot reloading via Next.js

---

## Tech Stack

| Technology     | Description                          |
|----------------|--------------------------------------|
| Next.js        | React framework with SSR & SSG       |
| Prisma         | ORM for efficient database access    |
| NextAuth       | Authentication solution              |
| Cloudinary     | Cloud-based media management         |
| TypeScript     | Strongly typed JavaScript            |

---

## Getting Started

1. Clone the Repository
2. 
git clone https://github.com/SummerNova25/Rentz.git
cd Rentz


3. Install Dependencies
npm install


4. Create the Environment File
Create a .env file in the root directory and add the following:

DATABASE_URL=

NEXTAUTH_SECRET=
NEXTAUTH_URL=http://localhost:3000

GITHUB_ID=
GITHUB_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=


You will need to fill in these values based on your setup (GitHub OAuth, Cloudinary, database, etc.).

4. Generate Prisma Client

npx prisma generate


5. Apply Database Migrations

npx prisma migrate dev


6. Start the Development Server

npm run dev




Deployment
This project is ready for deployment on platforms like Vercel.
Make sure to set all required environment variables in the deployment settings.
