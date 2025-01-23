<div align="center">
  <img src="https://raw.githubusercontent.com/yashkumar2603/snipperun/refs/heads/main/public/dark.svg" alt="Snipperun Logo" width="80" />
  <h1>Snipperun</h1>
  <p>A modern code execution and sharing platform</p>
</div>

## 🚀 Overview

Snipperun is a powerful web application that allows developers to write, execute, and share code snippets in real-time. With support for multiple programming languages, syntax highlighting, and collaborative features, it provides a seamless environment for code experimentation and sharing.

## ✨ Features

- **Real-time Code Execution**: Write and run code in 8+ programming languages
- **Smart Editor**: Advanced code editor with syntax highlighting and autocompletion
- **Snippet Sharing**: Share your code snippets with unique URLs
- **Custom themes**: Variety of Themes to choose from when writing code

## 🛠️ Tech Stack

### Frontend
- [Next.js 14](https://nextjs.org/) - React framework with App Router
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Monaco Editor](https://microsoft.github.io/monaco-editor/) - Code editor
- [Framer Motion](https://www.framer.com/motion/) - Animations
- [Zustand](https://zustand-demo.pmnd.rs/) - State management

### Backend & Database
- [Convex](https://www.convex.dev/) - Backend and real-time database
- [Clerk](https://clerk.com/) - Authentication and user management

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/snipperun.git
cd snipperun
```

2. Install dependencies using npm or bun:
```bash
npm install
//or
bun install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

4. Configure the following environment variables:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

5. Run the development server using npm or bun:
```bash
npm run dev
//or
bun run dev
```