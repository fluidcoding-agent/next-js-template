This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).


## Project Setup

This template was generated using the following commands and configuration.  
To reproduce the same environment, follow these steps:

---

### 1. Create a Next.js App

```bash
npx create-next-app@latest my-project --typescript --tailwind --eslint
```
Options selected:

- Use `src/` directory: **No** / Yes

- Use App Router: No / **Yes**

- Use Turbopack: No / **Yes**

- Customize import alias (`@/*` by default): **No** / Yes

### 2. Install TailwindCSS Plugin

```bash
npm install tailwindcss-animate
```

### 3. Initialize Shadcn UI

```bash
npx shadcn@latest init
```
Configuration:
- Base color: **Neutral**

### 4. Install Component

```bash
npx shadcn@latest add dialog button sonner card label
```

### 5. Configure Font Settings

Add Korean font support to `globals.css` in the `@theme` section:
```css
@theme inline {
    --font-sans: var(--font-geist-sans), SamsungOneKoreanNoF, Samsung Sharp Sans, NotoSans, sans-serif;
    // Keep existing configurations
}
```

### 6. Modify Dialog Component

Remove `sm:max-w-lg` class from `components/ui/dialog.tsx` for better responsive behavior.

---

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
