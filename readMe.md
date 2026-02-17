# Ahjoor Frontend Dashboard

**Ahjoor** is a trustless community savings platform built with transparency in mind. This repository contains the frontend application, which provides real-time dashboards for savings groups to manage their circles, track contributions, and monitor payout status. It offers a user-friendly interface to interact with the Ahjoor platform, visualize round milestones, and keep every participant informed.

## 💰 Overview of Frontend Functionalities

The Ahjoor Frontend provides the following key features:

- 📊 **Real-time dashboards** for group organizers and participants to track savings circle status.
- 👁️ **Visualization of immutable records** of contributions, round history, and payout events stored on-chain.
- 📈 **Display of automated payout status** triggered when all participants have contributed and the round duration has elapsed.
- 📱 **Responsive interface** designed for optimal viewing and usability on all devices (mobile, tablet, desktop).

## ⚙️ Key Frontend Components

| Component | Description |
|---|---|
| **Frontend Dashboard** | Next.js interface for organizers and participants to track savings circle status in real time. |
| **User Authentication Module** | Handles wallet connection, session management, and participant verification. |
| **Savings Circle View** | Displays all active groups with their current round, contribution status, and next payout. |
| **Detailed Circle View** | Shows a comprehensive overview of a single group, including round history, participant contributions, and payout schedule. |
| **Notification System** | Provides real-time alerts for round completions, missed contributions, or upcoming payouts. |
| **Payout History / Status** | Displays a record of past payouts and their on-chain transaction details. |
| **Organizer Dashboard** | Specific views and functionalities for group organizers to manage circles and participants. |
| **Participant Dashboard** | Specific views for members to track their individual circle progress and contribution history. |

## 🛠️ Frontend Setup and Initialization

### ✅ Prerequisites

- NodeJS (v16+)
- npm

### 🔧 Installation

```bash
# Clone the frontend repo
git clone https://github.com/Ahjoor/ahjoor-frontend.git
cd ahjoor

# Install dependencies
npm install
# or if you hit peer dependency issues:
npm install --legacy-peer-deps

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser and you'll see the app running.

## ✨ What You Can Do

- 🔗 **Connect Your Wallet** — works with Freighter and other Stellar-compatible wallets
- 👥 **Create a Savings Circle** — start a new group with your friends or community
- 💰 **Make Regular Contributions** — save your agreed XLM amount each round
- 🎯 **Receive Your Payout** — claim the full pool amount when it's your turn
- 📊 **Track Progress** — see how your circle is doing with a clean, easy-to-use interface

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 15, TypeScript |
| UI | Tailwind CSS |
| Blockchain | Stellar, Soroban |
| Wallets | Freighter |
| State | React Hooks |


## 🤝 Contributing

We welcome contributors of all experience levels!

### 🧰 Getting Started

- Look for **good first issues**
- Fork the repository
- Create a feature branch
- Open a pull request

### 🌳 Branching Strategy

- `main` → stable release branch
- `dev` → active development
- `feature/*` → for individual features or fixes

### 📂 Code Guidelines

- Keep PRs small and focused
- Write clear commit messages
- Update docs when necessary

### ✍️ Commit Convention

We use **Conventional Commits** to standardize commit messages.

- `feat`: new feature
- `fix`: bug fix
- `docs`: documentation only
- `refactor`: code changes without feature/fix
- `chore`: maintenance tasks

## 🔗 Resources

- [Stellar Documentation](https://developers.stellar.org/)
- [Soroban Smart Contracts](https://soroban.stellar.org/)
- [Stellar CLI Reference](https://developers.stellar.org/docs/tools/developer-tools)
- [Next.js App Router](https://nextjs.org/docs/app)

## 🛡️ License

This project is licensed under the **MIT License**.

---

**Built with ❤️ to help communities save money together through Ahjoor Savings**