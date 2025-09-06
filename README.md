# 🛒 Full Stack E-commerce Website

This is a **Full Stack E-commerce application** built with [Next.js](https://nextjs.org/).  
It includes **user authentication** with [Clerk](https://clerk.com/), background job management with [Inngest](https://www.inngest.com/), and an **Admin Dashboard** for managing products and orders.  
The project uses **MongoDB** for data storage and **Cloudinary** for product image hosting. Finally, it is deployed on [Vercel](https://vercel.com/).

👉 **Live Demo:** [Shop Cart](https://shop-cart-two-indol.vercel.app/)

---

## 🚀 Features

- 🔐 **User Authentication** with Clerk (sign up, login, sessions)
- 📦 **Product Management** (Admin can add, update, and list products)
- 🛍️ **Cart Functionality** (users can add items to cart and place orders)
- 📑 **Order Management** (Admin can view orders placed by users)
- ⚡ **Background Jobs** with Inngest (handle Clerk webhooks and async tasks)
- 🖼️ **Image Storage** using Cloudinary
- 🌐 **API Integration** (backend built with Next.js API routes)
- 📊 **Admin Dashboard** for product & order management
- ☁️ **Deployment** on Vercel (free hosting)

---

## 🏗️ Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Next.js API Routes
- **Authentication:** Clerk
- **Background Jobs:** Inngest
- **Database:** MongoDB (Mongoose ODM)
- **Storage:** Cloudinary
- **Deployment:** Vercel

---

## 📂 Project Structure
├── app/ # Next.js app directory
│ ├── (auth)/ # Clerk authentication pages
│ ├── (store)/ # Storefront pages
│ ├── (admin)/ # Admin dashboard
│ └── api/ # API routes (products, orders, webhooks)
├── components/ # Reusable UI components
├── lib/ # DB connection, helpers
├── models/ # Mongoose models (User, Product, Order)
├── public/ # Static assets
├── styles/ # Global styles
└── utils/ # Utility functions


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install dependencies
npm install
# or
yarn install

