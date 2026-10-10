# Hi, I'm Sarfo Clinton

**Full-Stack Software Developer** | React, TypeScript, Next.js, ASP.NET Core, Node.js | Kumasi, Ghana

[LinkedIn](https://linkedin.com/in/clinton-sarfo) | [Portfolio](https://clintonsarfo.vercel.app) | [Email](mailto:clinton.sarfo.dev@gmail.com)

Open to full-stack and backend roles (remote or local).

---

## About Me

I'm a full-stack developer with about 2 years of experience building and supporting production business software. At work I use React, TypeScript, ASP.NET Core and SQL Server, and I handle the whole path from UI and API to database and deployment on Windows Server/IIS. Outside work I build personal projects with Next.js, Node/Express, PostgreSQL and Convex.

I like turning messy real-world workflows into software people actually use. Away from the keyboard I do magic tricks, so ask me for one.

---

## Professional Work (Clockwise Tech Company Ltd, March 2025 to present)

Small team building ERP, payment and receipt software for 20+ client companies. The code is private, so this is a summary.

- **Multi-tenant digital receipt platform.** Built end to end with React/TypeScript, ASP.NET Core (ADO.NET) and SQL Server. Receipts arrive from the company's ERP and POS, customers get an SMS link with a QR code, and each company's data is isolated by tenant. Live for about 3 months with 8 companies and about 174,000 receipts.
- **Desktop and mobile shells for the company ERP.** An Electron app and an Expo (React Native) app that deliver a Blazor-based ERP as native apps, with silent receipt printing (A4 and thermal), automatic updates from a self-hosted server, an NSIS installer, and a protected per-device tenant URL.
- **SchoolMate (school management).** Owned the React frontend from design to deployment, moved report-card generation from one-at-a-time client-side to server-side bulk generation, and built the parent portal.
- **Deployment.** Set up and maintain apps on Windows Server with IIS (sites, domains, SSL).

---

## Tech Stack

| Area                 | Technologies                                                               |
| -------------------- | -------------------------------------------------------------------------- |
| Languages            | TypeScript, JavaScript, C#, SQL                                            |
| Frontend             | React, Next.js, Redux, TanStack Query, Tailwind CSS, Ant Design, shadcn/ui |
| Backend              | ASP.NET Core, ADO.NET, Node.js/Express, REST APIs, Socket.IO, JWT auth     |
| Databases            | SQL Server, PostgreSQL, MySQL, Supabase, Convex                            |
| Desktop and mobile   | Electron, React Native (Expo)                                              |
| Integrations         | Paystack, Clerk, Google Gemini API, AssemblyAI, Twilio                     |
| Deployment and tools | IIS, Vercel, Render, Git/GitHub                                            |

---

## Featured Projects

### Shell POS

Point-of-sale web app built solo with React/TypeScript, Node/Express, PostgreSQL (Supabase), Socket.IO and Paystack. It covers inventory, sales, reporting, authentication, receipts and mobile money payments.

- A companion Expo app turns a phone into a barcode scanner: the POS shows a QR code, the phone scans it to join a Socket.IO room, and scanned products come back with their data from the database.
- The backend uses Helmet, rate limiting and Winston logging. The frontend runs on Vercel and the backend on Render.

**Live demo:** https://shell-pos-frontend.vercel.app/admin

Demo login: `admin@pos.com` / `Admin@1234` (demo data only)

### Transfer Hub

File and text sharing app built with Next.js, Supabase, Cloudflare R2 and Upstash Redis. It supports expiry, size limits, authentication, email sharing and guest access. My colleagues use it at work.

**Live app:** https://shell-transfer.vercel.app

### Classmate (in development)

AI-powered study platform for students, built with Next.js, TypeScript, Convex, Clerk and Google Gemini. This is a private repository and it is not deployed yet.

- AI chat over a student's notes and lecture transcripts, flashcards with spaced repetition, and personalised study plans
- Audio recording (browser and Twilio voice) with transcription through AssemblyAI
- A credit-based usage system with Paystack payments in USD and GHS, subscriptions and referrals
- A shared topic cache to keep AI and API costs down

### Riddle Rush

Real-time multiplayer riddle game built with React and Convex.

**Live demo:** https://riddle-rush-kappa.vercel.app

### School Siren Scheduler

Offline desktop app (React and Electron) that lets schools schedule bells and sirens with custom text-to-speech announcements.

### FashionHub

E-commerce storefront built as a frontend project.

**Live demo:** https://fashion-hub-navy.vercel.app

---

## Contact

- Portfolio: https://clintonsarfo.vercel.app
- LinkedIn: https://linkedin.com/in/clinton-sarfo
- Email: clinton.sarfo.dev@gmail.com

Always happy to talk about interesting projects and opportunities.
