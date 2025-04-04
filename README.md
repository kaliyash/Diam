# 💎 Diamante Blockchain Account Manager

A Node.js CLI tool for interacting with the **Diamante Blockchain (DiamCircle Testnet)**. This project allows developers and enthusiasts to perform a wide range of blockchain operations including account creation, trustlines, payments, asset issuance, offer management, real-time payment streaming, and payment channels using the `diamante-sdk-js`.

---

## 🚀 Features

- 🔐 **Account Management**
  - Create new accounts via Friendbot
  - Login with existing secret keys

- 💸 **Asset Operations**
  - Issue custom assets
  - Setup and manage trustlines
  - Make payments with native or custom assets

- 🔄 **Offer Management**
  - Manage buy and sell offers
  - Submit and track offers programmatically

- 🛁 **Advanced Features**
  - Real-time payment streaming via EventSource
  - Handle transactions with preconditions (time bounds)
  - Perform asset pathfinding between accounts
  - Implement off-chain transactions using **Starlight Payment Channels**

---

## 💪 Technologies Used

- [`diamante-sdk-js`](https://www.npmjs.com/package/diamante-sdk-js) – SDK for interacting with Diamante Blockchain
- [`node-fetch`](https://www.npmjs.com/package/node-fetch) – Fetch API for HTTP requests
- [`readline`](https://nodejs.org/api/readline.html) – Built-in Node.js module for CLI interaction
- [`eventsource`](https://www.npmjs.com/package/eventsource) – For real-time streaming

---

## 🛆 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/diamante-blockchain-cli.git
cd diamante-blockchain-cli
npm install
```

---

## 🧪 Usage

Start the CLI tool with:

```bash
node index.js
```

You'll be prompted to choose an action:

```
Select an action:
1: Create a new account
2: Login to an existing account
```

Then, follow the prompts to perform blockchain operations such as:

- Setting up a trustline
- Issuing custom assets
- Making payments
- Managing buy/sell offers
- Streaming real-time payments
- Using payment channels

---

## 🧬 Example Workflow

1. **Create a new account**
2. **Set up a trustline** to a custom asset
3. **Issue a custom asset** to your account
4. **Make a payment** using native or issued assets
5. **Stream account payments**
6. **Create buy/sell offers**
7. **Test conditional transactions and payment channels**

---

## ⚠️ Notes

- The tool uses the **Diamante Testnet** for safe experimentation.
- Replace testnet URLs and network passphrases to work with the mainnet in production.
- Always keep secret keys secure and never expose them in public repositories.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!


