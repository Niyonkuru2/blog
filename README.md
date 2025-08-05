# 📝 Modern Blog Website

A full-featured, modern blog platform built with **Next.js**, **Prisma**, **MongoDb**, and **Tailwind CSS**. It supports dynamic content, markdown, comments, search, author dashboard, and SEO optimization.

---

## 🚀 Features

- 📰 Responsive blog listing and detail pages
- ✍️ Author login, post creation & editing
- 🔍 Search and filter by tags/categories
- 💬 Comment system
- 🌗 Dark mode toggle
- 📦 Markdown or rich-text support
- 🔐 Authentication with JWT or NextAuth
- ☁️ Image uploads with Cloudinary
- 📧 Newsletter subscription (Mailchimp/Resend)
- ⚙️ Admin moderation (optional)

---

## 🧱 Tech Stack

| Layer        | Technology                          |
|--------------|--------------------------------------|
| Frontend     | Next.js (App Router) + Tailwind CSS  |
| Backend      | API Routes or RESTful Express        |
| Database     | PostgreSQL + Prisma ORM              |
| Auth         | NextAuth / JWT                       |
| Deployment   | Vercel (frontend) + Railway (backend)|
| Image Upload | Cloudinary                           |
| Extras       | React Hook Form, Zod, Framer Motion  |

---

## 📂 Project Structure

```bash
modern-blog/
├── app/          # Pages & routes (Next.js App Router)
├── components/   # Reusable components
├── lib/          # Prisma, utilities, config
├── prisma/       # DB schema & seeding
├── public/       # Static assets
├── styles/       # Global styles
├── .env          # Environment variables
├── tailwind.config.js
├── tsconfig.json
└── README.md
````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/modern-blog.git
cd modern-blog
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file based on `.env.example`:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/modern_blog
NEXTAUTH_SECRET=your-secret
NEXTAUTH_URL=http://localhost:3000
CLOUDINARY_URL=your-cloudinary-url
```

### 4. Set Up Prisma

```bash
npx prisma generate
npx prisma migrate dev --name init
```

### 5. Run the Dev Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

---

## 📌 To Do (Milestones)

* [x] Define user stories and documentation
* [ ] Set up Tailwind + Prisma + PostgreSQL
* [ ] Build public pages: home, blog, categories
* [ ] Implement search + filter
* [ ] Add auth (login/register)
* [ ] Create author dashboard (CRUD)
* [ ] Add comment system
* [ ] Add newsletter feature
* [ ] SEO meta tags + sitemap

---

## 📜 License

MIT © NIYONKURU Samuel
