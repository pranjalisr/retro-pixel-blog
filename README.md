# 👾 retro-pixel-blog

A retro pixel-themed blog built with **Next.js 15**, **React 19**, and **TypeScript** — featuring a fully component-driven UI powered by shadcn/ui and Radix UI primitives, with dark/light theme support.

---

## 📁 Project Structure

```
retro-pixel-blog/
├── app/               # Next.js App Router pages & layouts
├── components/        # Reusable UI components (shadcn/ui + custom)
├── hooks/             # Custom React hooks
├── lib/               # Utility functions & helpers
├── public/            # Static assets (images, fonts, icons)
├── styles/            # Global CSS styles
├── components.json    # shadcn/ui component config
├── next.config.mjs    # Next.js configuration
├── tailwind.config.js # Tailwind CSS configuration
├── tsconfig.json      # TypeScript configuration
└── package.json       # Project metadata & dependencies
```

---

## 🛠 Tech Stack

| Category        | Technology                              |
|-----------------|-----------------------------------------|
| Framework       | Next.js 15.1.0                          |
| Language        | TypeScript 5                            |
| UI Library      | React 19                                |
| Styling         | Tailwind CSS 3 + tailwindcss-animate    |
| Component Kit   | shadcn/ui (Radix UI primitives)         |
| Icons           | Lucide React                            |
| Theming         | next-themes (dark/light mode)           |
| Forms           | React Hook Form + Zod                   |
| Charts          | Recharts                                |
| Date Utilities  | date-fns                                |
| Package Manager | pnpm                                    |

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/) — install via `npm install -g pnpm`

### Installation

```bash
# Clone the repository
git clone https://github.com/pranjalisr/retro-pixel-blog.git
cd retro-pixel-blog

# Install dependencies
pnpm install
```

### Running the Dev Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command        | Description                              |
|----------------|------------------------------------------|
| `pnpm dev`     | Starts the development server            |
| `pnpm build`   | Builds the app for production            |
| `pnpm start`   | Starts the production server             |
| `pnpm lint`    | Runs ESLint across the project           |

---

## ✨ Features

- 🎮 **Retro pixel aesthetic** — unique pixelated visual design
- 🌙 **Dark / Light mode** — powered by `next-themes`
- 📱 **Fully responsive** — mobile-first layout
- ♿ **Accessible** — built on Radix UI primitives
- 📝 **Form validation** — React Hook Form + Zod schemas
- 📊 **Charts support** — Recharts integration
- ⚡ **App Router** — Next.js 15 file-based routing

---

## 📦 Key Dependencies

| Package                    | Purpose                        |
|----------------------------|--------------------------------|
| `next`                     | React framework (App Router)   |
| `react` / `react-dom`      | UI rendering                   |
| `tailwindcss`              | Utility-first CSS              |
| `@radix-ui/*`              | Accessible UI primitives       |
| `lucide-react`             | Icon library                   |
| `next-themes`              | Theme switching                |
| `react-hook-form` + `zod`  | Form handling & validation     |
| `recharts`                 | Data visualization             |
| `date-fns`                 | Date formatting utilities      |
| `clsx` + `tailwind-merge`  | Conditional class utilities    |
| `sonner`                   | Toast notifications            |
| `cmdk`                     | Command palette                |
| `vaul`                     | Drawer component               |
| `embla-carousel-react`     | Carousel / slider              |

---

## 👩‍💻 Author

**Pranjali** — [@pranjalisr](https://github.com/pranjalisr)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
