# 🤖 polyfact-chat-nextjs-boilerplate

Jumpstart your chat experience using the Polyfact SDK, powered by Next.js and styled using styled-components! TypeScript brings type safety to your Next.js project.

## 📌 Table of Contents

- [🌟 Features](#-features)
- [🔧 Prerequisites](#-prerequisites)
- [🚀 Installation](#-installation)
- [🖥 Usage](#-usage)
- [⚙ Configuration](#-configuration)
- [💬 Using polyfact-cli](#-using-polyfact-cli)
- [🔑 Scripts](#-scripts)
- [📚 Dependencies](#-dependencies)
- [🥞 Stack](#-stack)
- [✨ Contributing](#-contributing)
- [📜 License](#-license)

## 🌟 Features

- Fully customizable chat UI with styled components.
- Seamless integration with Polyfact SDK for chat functionalities.
- Pre-configured themes for chat, header, and footer.
- Easy to adapt and extend within the Next.js framework.

## 🔧 Prerequisites

- Node.js
- npm/yarn

## 🚀 Installation

1️⃣. Clone the repository:
```bash
git clone https://github.com/kevin-btc/polyfact-chat-nextjs-boilerplate.git
```

2️⃣. Navigate to the project directory:
```bash
cd polyfact-chat-nextjs-boilerplate
```

3️⃣. Install the magic (dependencies):
```bash
npm install
```

## 🖥 Usage

1️⃣. Fire up the development server:
```bash
npm run dev
```

2️⃣. Visit `http://localhost:3000` to see your chat bot in action!

## ⚙ Configuration

All configurations can be tinkered with in `src/config.ts`. Adjust colors, name your bot, choose logos, and more.

### 🛠 Polyfact Configuration

1. Register a project at [Polyfact](https://app.polyfact.com).
2. Replace the project ID in `pages/_app.tsx`.
3. Select or provide system prompt IDs.

## 💬 Using polyfact-cli

Want guided setup? Use the `polyfact-cli`:

1️⃣. Summon the CLI:
```bash
npx polyfact
```

2️⃣. Pick "chat".
3️⃣. Follow the breadcrumbs (on-screen instructions).

## 🔑 Scripts

- `npm run dev`: Local development.
- `npm run build`: Prep for production.
- `npm run preview`: Peek at the production build.

## 📚 Dependencies

- Core: `next`, `react`, `react-dom`
- Chat: `@polyfact/chat`, `polyfact`
- Icons: `phosphor-react`
- Dialog: `@radix-ui/react-dialog`
- Types: `typescript`

## 🥞 Stack

- Next.js
- TypeScript
- styled-components

## ✨ Contributing

Have ideas? 🤔 Found a bug? 🐞 Join us! Check out the [issues](https://github.com/kevin-btc/polyfact-chat-nextjs-boilerplate/issues).

## 📜 License

This project is under the MIT License. Check out `LICENSE` for details.

---

If this lights up your day, give us a ⭐ on GitHub!
