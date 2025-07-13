# 🚀 my_icp

![GitHub Repo stars](https://img.shields.io/github/stars/Webgh0st/my_icp?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/Webgh0st/my_icp)
![Made with DFINITY](https://img.shields.io/badge/DFINITY-ICP-orange?logo=internet-computer)

Welcome to the `my_icp` project – a decentralized application (dApp) built on the Internet Computer using DFINITY’s SDK. This project includes both frontend and backend canisters to provide a full-stack Web3 experience.

---

## 🌐 Deployed Links

- **Frontend Canister**  
  🔗 [https://schzy-iyaaa-aaaab-aafoq-cai.icpe.io](https://schzy-iyaaa-aaaab-aafoq-cai.icpe.io)

- **Backend Canister (Candid UI)**  
  🔗 [https://a4gq6-oaaaa-aaaab-qaa4q-cai.raw.icpe.io/?id=sfg7m-faaaa-aaaab-aafoa-cai](https://a4gq6-oaaaa-aaaab-aafoa-cai.raw.icpe.io/?id=sfg7m-faaaa-aaaab-aafoa-cai)

---

## 📁 Project Structure

\`\`\`
my_icp/
├── src/
│   ├── my_icp_backend/      # Rust backend canister
│   └── my_icp_frontend/     # React frontend
├── .dfx/                    # DFINITY config and cache
├── dfx.json                 # Project configuration
├── package.json             # Node.js dependencies
└── README.md                # This file
\`\`\`

---

## 💻 Local Development

\`\`\`bash
# Start local replica
dfx start --background

# Deploy canisters locally
dfx deploy

# Generate Candid interfaces
npm run generate

# Start frontend dev server
npm start
\`\`\`

Then open:  
🖥️ http://localhost:8080  
API proxy: http://localhost:4943

---

## 📦 Built With

- 🦀 Rust (Backend)
- ⚛️ React+Vite (Frontend)
- 🧠 DFINITY SDK (dfx)
- 🔐 Internet Identity

---

## 🙋‍♂️ Author

Made with 💙 by  
**Webgh0st** aka **DevManoj19**

[![GitHub](https://img.shields.io/badge/GitHub-Webgh0st-blue?logo=github)](https://github.com/Webgh0st)  
[![GitHub](https://img.shields.io/badge/GitHub-DevManoj19-black?logo=github)](https://github.com/DevManoj19)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
