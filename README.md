This is a demo-app created for workshop Fullstack Development with Next.js 14 and Prisma ORM

Notes: https://florentine-chocolate-a58.notion.site/Full-stack-Development-with-Next-js-14-and-Prisma-ORM-Part-1-0bff6c1aeb0c4370b18cf82d713e75c9?pvs=25

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

Migrate and seed db
```bash
npx prisma migrate dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

Topics Covered

```
1. Routing and Navigation
  <Link />
2. Metadata
3. Styling (Tailwind css)
4. Client vs Server component
    - Data-fetching (GET requests)
5. Server Actions (POST/PUT/DELETE)
6. Suspense and Streaming
7. Caching
8. Static and dynamic rendering
9. Middleware
```