# ⚡ Community Pulse & Business Showcase Hub

Welcome to the **Community Pulse Hub**, a dynamic, real-time interactive platform designed to connect project planners, industrial engineers, and web developers. This repository hosts the complete source code for a lightweight, high-performance community board that operates without a traditional backend, leveraging the power of **Supabase**.

## ✨ Key Features

*   ** Real-Time Messaging:** Instant message delivery using Supabase Realtime subscriptions. No page refresh required!
*   **👥 Live Presence Tracking:** See exactly how many users are currently online with a custom-built presence counter.
*   **🏪 Business Showcase:** An integrated advertising section where community members can request free ad space to promote their tools, services, or portfolios.
*   ** Modern Dark UI:** A professional, gold-accented dark theme optimized for readability and visual appeal.
*   **⚡ Serverless Architecture:** Fully static frontend hosted on GitHub Pages with a scalable PostgreSQL backend via Supabase.
*   **📱 Fully Responsive:** Optimized for desktop, tablet, and mobile devices.

## ️ Tech Stack

*   **Frontend:** HTML5, CSS3 (Grid/Flexbox), Vanilla JavaScript (ES6+)
*   **Backend/Database:** Supabase (PostgreSQL, Realtime, Auth, Storage)
*   **Hosting:** GitHub Pages
*   **Icons:** Font Awesome 6

##  Purpose

This hub serves as a central gathering point for the **BM Planning** community. It allows users to:
1.  Share insights, ask questions, and discuss project management topics instantly.
2.  Discover new tools and resources through the curated Business Showcase.
3.  Promote their own businesses or projects by requesting free ad slots directly through the interface.

## 🚀 Getting Started

1.  Clone this repository.
2.  Set up your Supabase project and create the `messages` table with Row Level Security (RLS) policies.
3.  Update the `SUPABASE_URL` and `SUPABASE_KEY` in the `hub.html` file.
4.  Deploy to GitHub Pages or any static hosting provider.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---
*Built with ❤️ by Behzad Mousavi | [BM Planning](https://sbmousavices.github.io/Industrial-Tools/)*