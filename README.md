


FAYDA HACKATHON

---

🪪 Fayda ID Agent

Welcome to the Fayda ID Agent project — a modern, secure, and scalable identity agent built to integrate seamlessly with the Fayda ID ecosystem. Developed by Ananiya and team, this project leverages a powerful stack to ensure performance, security, and developer experience.

🚀 Tech Stack

Frontend: [React](https://reactjs.org/) — Modern, component-based UI
Backend Services:

* [Supabase](https://supabase.com/) — Scalable backend with instant APIs & real-time capabilities
* [Neon](https://neon.tech/) — Serverless Postgres for edge-native performance
* [Drizzle ORM](https://orm.drizzle.team/) — Type-safe, modern SQL toolkit
* [Better Auth](https://github.com/marshallcb/better-auth) — Lightweight and secure authentication

🧠 Project Goals

* Provide a clean interface for users to interact with their Fayda ID
* Enable secure, decentralized verification and data handling
* Ensure maximum privacy and compliance with modern standards
* Offer seamless authentication and session management

📦 Features

* 🔐 End-to-end authentication with Better Auth
* 🌐 Real-time data sync using Supabase
* ⚡ Serverless Postgres on Neon for optimized performance
* 🧬 Strongly-typed queries & migrations via Drizzle ORM
* 💅 Clean and modular React frontend

🛠️ Getting Started

Prerequisites

* Node.js ≥ 18
* Supabase account
* Neon account
* Environment variables set up (see `.env.example`)

Installation

```
git clone https://github.com/your-username/fayda-id-agent.git
cd fayda-id-agent
npm install
```

Running the App

```
npm run dev
```

📁 Project Structure

```
/
├── src/
│   ├── components/       React components
│   ├── pages/            App routes
│   ├── lib/              Drizzle config, Supabase client
│   └── auth/             Better Auth integration
├── drizzle.config.ts     Drizzle ORM setup
├── .env.example          Sample env file
└── README.md
```

🧪 Development Notes

* Drizzle migrations are tracked and committed with schema changes
* Auth is abstracted into reusable hooks for cleaner logic
* Data fetching is cached and reactive via Supabase’s real-time listeners

🤝 Contributors

* Ananiya — Lead Developer
* You — Co-developer, UX engineer, or general badass 😎

📄 License

MIT — free to use, improve, and fork.

---

Let me know if you'd like this saved as a downloadable file or need a version tailored for deployment instructions.
