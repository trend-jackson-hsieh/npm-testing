# rdsec-npm-testing

[![npm version](https://img.shields.io/npm/v/rdsec-npm-testing.svg)](https://www.npmjs.com/package/rdsec-npm-testing)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

---

## 📦 About

This repository (`trend-rdsec-poc/npm-testing`) is the **main development repository** for the npm package **`rdsec-npm-testing`**.

- ✅ Actively developed and maintained inside the EMU GitHub Enterprise environment.  
- 🚀 Code here is synced to the public publishing mirror [`trend-jackson-hsieh/npm-testing`](https://github.com/trend-jackson-hsieh/npm-testing) for **Trusted Publishing with provenance**.

---

## 📥 Installation

Using npm:

```bash
npm install rdsec-npm-testing
```

Or with Yarn:

```bash
yarn add rdsec-npm-testing
```

---

## 🔧 Usage

```js
const test = require('rdsec-npm-testing');

console.log(test()); // Example output
```

---

## 👩‍💻 Development

1. Clone this repository (inside EMU GitHub Enterprise):  
   ```bash
   git clone https://github.com/trend-rdsec-poc/npm-testing.git
   cd npm-testing
   ```

2. Install dependencies:  
   ```bash
   npm install
   ```

3. Run tests:  
   ```bash
   npm test
   ```

4. Version bump and tagging (will trigger publishing workflow on mirror repo):  
   ```bash
   npm version patch
   git push origin main --tags
   ```

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).
