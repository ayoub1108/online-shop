
# 🛒 Shopcart Ecommerce Website


<img width="1920" height="863" alt="image" src="https://github.com/user-attachments/assets/837094f8-6747-436d-bcf7-cde6e633c2b8" />

## ✨ Hosted with Vercel 
https://shopcart.reactbd.com/
>>>>>>> c4652f041ef1dc4b02f5bba2cefcb99262de4d68

*Shopcart - A modern e-commerce interface for gadgets and appliances*

Shopcart is a full-stack e-commerce platform built with **Next.js**, featuring a product catalog, shopping cart functionality, and integration with **Sanity.io** for content management. The project includes secure payment processing and is optimized for performance with modern web technologies.

---

## ✨ Features

- 🏠 **Homepage with Promotional Banner**: Engaging hero section with "Hot Deal" promotions and call-to-action buttons as shown in the screenshot above.
- 🛍️ **Product Categorization**: Browse products by categories like Gadget, Appliances, and Refrigerators.
- 🚧 **Smart Empty States**: Displays user-friendly messages like "No Product Available" with guidance when categories are empty.
- 🛒 **Shopping Cart Functionality**: Add/remove items, manage quantities with a seamless cart experience.
- 💳 **Payment Integration**: Secure checkout process (implementation visible in commit history).
- 📱 **Fully Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- 🧠 **Headless CMS**: Content managed via **Sanity.io** for easy product updates.
- ⚡ **Modern Tech Stack**: Built with Next.js 15, React, TypeScript, and Tailwind CSS.
- 🔒 **Authentication**: Secure user authentication and management.

---

## 🚀 Tech Stack

| Category          | Technologies                                                                 |
| ----------------- | ---------------------------------------------------------------------------- |
| **Framework**     | [Next.js 15](https://nextjs.org/) (React framework with App Router)          |
| **Language**      | [TypeScript](https://www.typescriptlang.org/)                                |
| **Styling**       | [Tailwind CSS](https://tailwindcss.com/)                                     |
| **CMS**           | [Sanity.io](https://www.sanity.io/) (Headless CMS with GROQ queries)         |
| **State Management** | [Zustand](https://github.com/pmndrs/zustand) (Lightweight state management) |
| **Payments**      | Payment gateway integration (from commit history)                            |
| **Authentication**| [Clerk](https://clerk.com/) (User management)                               |
| **UI Components** | Custom components with [Radix UI](https://www.radix-ui.com/) primitives     |
| **Deployment**    | Optimized for [Vercel](https://vercel.com/)                                  |

---

## 📁 Project Structure

```
shopcartyt/
├── app/                 # Next.js App Router pages and layouts
├── components/          # Reusable UI components
├── constants/           # Application constants and configuration
├── hooks/               # Custom React hooks
├── lib/                 # Utility functions and libraries
├── sanity/              # Sanity CMS configuration and schemas
├── images/              # Static image assets
├── public/              # Public assets (favicon, etc.)
├── .env.local           # Environment variables (not in repo)
├── next.config.ts       # Next.js configuration
├── sanity.config.ts     # Sanity studio configuration
├── store.ts             # Zustand store setup
└── middleware.ts        # Next.js middleware for auth
```

---

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm
- Sanity.io account and project
- Clerk account for authentication
- Payment gateway credentials (for full functionality)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/noorjsdivs/shopcartyt.git
   cd shopcartyt
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory with the following variables:

   ```env
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key

   # Sanity Configuration
   NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   NEXT_PUBLIC_SANITY_DATASET=production
   NEXT_PUBLIC_SANITY_API_VERSION=2024-01-01
   SANITY_API_READ_TOKEN=your_sanity_api_token
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

5. **Open the application**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🔧 Sanity Setup

The project uses Sanity as a headless CMS. To manage your content:

1. **Install Sanity CLI globally** (if needed)
   ```bash
   npm install -g @sanity/cli
   ```

2. **Link your Sanity project**
   The project already contains Sanity configuration files (`sanity.config.ts`, `sanity.cli.ts`). Ensure your `.env.local` has the correct `NEXT_PUBLIC_SANITY_PROJECT_ID`.

3. **Run Sanity Studio locally**
   ```bash
   npx sanity dev
   ```
   This will start the Sanity Studio at `http://localhost:3333` where you can manage products and content.

4. **Seed initial data** (optional)
   The repository includes seed data in `seed.tar.gz` and `schema.json` to help you get started with sample products.

---

## 🚢 Deployment

### Deploy to Vercel (Recommended)

The easiest way to deploy this Next.js application is to use the [Vercel Platform](https://vercel.com/).

1. Push your code to a GitHub repository.
2. Import the project into Vercel.
3. Add all environment variables from your `.env.local` to your Vercel project settings.
4. Deploy!

For more details, check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment).

---

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - Interactive Next.js tutorial.
- [Sanity Documentation](https://www.sanity.io/docs) - Guide to Sanity CMS.
- [Clerk Documentation](https://clerk.com/docs) - Authentication setup.
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Styling framework.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/noorjsdivs/shopcartyt/issues) if you want to contribute.

---

## 📄 License

This project is open-source. Please refer to the repository for specific license details.

---



