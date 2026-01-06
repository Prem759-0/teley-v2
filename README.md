# Teley‑v2 – Simple Board Collaboration App

## What is this?
Teley‑v2 is a web app that lets you create a digital whiteboard, write or draw on it, and invite friends or teammates to work together in real time. Think of it as an online sketchpad you can share instantly.

## Key Features (in plain language)
- **Create a board** – Start a new blank canvas with one click.
- **Invite others** – Share a simple link and anyone can join to draw or type together.
- **Live updates** – Changes appear instantly for everyone, no refresh needed.
- **Save your work** – Boards are automatically saved so you can come back later.
- **Easy sign‑in** – Uses Clerk for quick email or social‑login.

## Demo (what you’ll see)
When you open the app you’ll land on a clean home page with a **"Create Board"** button. After clicking, a fresh whiteboard appears with a toolbar for drawing, adding text, and a share button to copy the board link.

## How to run it locally (step‑by‑step)
1. **Install Node.js** – Download from [nodejs.org](https://nodejs.org) if you don’t have it.
2. **Open a terminal** and go to the project folder:
   ```
   cd "C:/Users/Admin/OneDrive/Desktop/working website/full working website/teley-v2/teley-v2"
   ```
3. **Install dependencies**:
   ```
   npm install
   ```
4. **Start the Convex backend** (used for real‑time data):
   ```
   npx convex dev
   ```
5. **Run the web app**:
   ```
   npm run dev
   ```
6. Open your browser and go to `http://localhost:3000` – you’ll see the home page.

## Using the app
- Click **Create Board**.
- Use the toolbar on the left to draw, add text, or change colors.
- Click **Share** to copy the board link and send it to a friend.
- Everyone with the link can see and edit the board at the same time.

## Contributing
If you have ideas or find a bug, feel free to open an issue or submit a pull request on the GitHub repo. We welcome any feedback that makes the app easier to use.

## License
This project is licensed under the MIT License – you’re free to use, modify, and share it.

---
*Created with love for simple, collaborative creativity.*

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

second run 
```bash
npx convex dev
```

```bash
.env.local
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
CLERK_JWT_ISSUER_DOMAIN=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_API_SECRET_KEY=
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

