#  Full-ECommerce Website - Next.js 15 

|                |                                  |
| -------------- | -------------------------------- |
| Frmework       | Next.js 15, React 19             |
| UI             | Tailwind, Shadcn, Recharts       |
| Database       | MongoDB, Mongoose                |
| Payment        | PayPal, Stripe                   |
| Deployment     | Github, Vercel                   |
| Authentication | Auth.js, Google Auth, Magic Link |
| Others         | uploadthing, resend, zod, etc    |

[![Next.js MongoDB Amazona](/public/images/app.png)](https://next-mongo-ecommerce-final.vercel.app/)




This project is a comprehensive, full-stack tutorial designed to help you build a modern e-commerce website inspired by Amazon, using cutting-edge technologies like Next.js 15, MongoDB, Tailwind CSS, and more. Whether you're a developer looking to sharpen your skills or someone aiming to launch a scalable online store, this hands-on guide will walk you through every essential feature.

🚀 What You'll Build
A sleek, responsive storefront with dynamic product listings, categories, and search functionality

A customer-friendly interface with modals for quick product previews and seamless navigation

A secure, scalable backend powered by MongoDB and Mongoose for managing products, users, and orders

A personalized customer dashboard for profile updates and order tracking

A powerful admin dashboard with data visualizations and full control over inventory, users, and transactions


## Run Locally

1. Clone repo

   ```shell
    $ git clone git@github.com:basir/nextjs-amazona.git
    $ cd nextjs-amazona
   ```

2. Create Env File

   - duplicate .example-env and rename it to .env.local

3. Setup MongoDB

   - Cloud MongoDB
     - Create database at https://mongodb.com/
     - In .env.local file update MONGODB_URI to db url
   - OR Local MongoDB
     - Install it from https://www.MongoDB.org/download
     - In .env.local file update MONGODB_URI to db url

4. Seed Data

   ```shell
     npm run seed
   ```

5. Install and Run

   ```shell
     npm install --legacy-peer-deps
     npm run dev
   ```

6. Admin Login

   - Open http://localhost:3000
   - Click Sign In button
   - Enter admin email "admin@example.com" and password "123456" and click Sign In


