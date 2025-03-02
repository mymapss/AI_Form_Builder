# AI Form Builder

![banner](./public/formy.gif)

A modern AI-powered form builder application that enables users to create, customize, and share forms effortlessly. Built with cutting-edge technologies and AI integration.

## 🚀 Tech Stack

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Kinde](https://img.shields.io/badge/Kinde_Auth-000000?style=for-the-badge)
![ShadcnUI](https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge)

## 📌 Project Overview

This AI Form Builder is a comprehensive solution that combines the power of artificial intelligence with modern web technologies to create an intuitive form-building experience. Built following TechWithEmma's excellent tutorial, this implementation adds custom touches while maintaining the core functionality.

## ✨ Key Features

- 🤖 **AI-Powered Form Generation**
  - Intelligent form suggestions
  - Smart field recommendations
  - Context-aware form templates

- 🎨 **Drag & Drop Builder**
  - Intuitive interface
  - Real-time preview
  - Customizable components

- 🔒 **Authentication & Security**
  - Secure user authentication with Kinde
  - Protected form submissions
  - Data encryption

- 📊 **Analytics & Insights**
  - Form performance metrics
  - Response analytics
  - User engagement tracking

- 🌐 **Sharing & Collaboration**
  - Unique form links
  - Embed options
  - Team collaboration features

## 🛠️ Installation

1. Clone the repository
```bash
git clone https://github.com/mymapss/AI_Form_Builder.git
cd ai-form-builder
```

2. Install dependencies
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Configure environment variables
```bash
cp .env.example .env.local
```

Required environment variables:
\`\`\`env

KINDE_CLIENT_ID=your_kinde_client_id

KINDE_CLIENT_SECRET=your_kinde_client_secret

KINDE_ISSUER_URL=your_kinde_issuer_url

KINDE_SITE_URL=your_site_url

KINDE_POST_LOGOUT_REDIRECT_URL=your_logout_url

KINDE_POST_LOGIN_REDIRECT_URL=your_login_url


DATABASE_URL=your_database_url

DIRECT_DATABASE_URL=your_direct_database_url


NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key

NEXT_PUBLIC_APP_URL=http://localhost:3000

\`\`\`

4. Initialize the database
```bash
npx prisma generate
npx prisma db push
```

5. Start the development server
```bash
npm run dev
```

## 🚀 Deployment

This project is optimized for deployment on Vercel:

1. Push your code to GitHub
2. Import your repository to Vercel
3. Configure environment variables in Vercel's dashboard
4. Deploy!

## 👨‍💻 Development

Developed by [mymapss](https://github.com/mymapss)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with ❤️ by mymapss
