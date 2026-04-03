# 🌾 Supply Chain Transparency System (Blockchain-Based)
A decentralized application (DApp) designed to enhance **transparency, traceability, and trust** in agricultural supply chains.
Developed as part of **Smart India Hackathon (SIH) 2025**.

---

## 🚀 Overview
This project leverages blockchain technology to track agricultural produce across every stage of the supply chain — from farmers to end consumers.
By storing immutable transaction records on-chain, the system ensures:
* 🔍 Full traceability of produce batches
* 🔐 Tamper-proof data storage
* 🤝 Increased trust among stakeholders

---

## 🛠️ Tech Stack
* **Blockchain Platform:** Ethereum (Testnets: Sepolia / Polygon Mumbai)
* **Smart Contracts:** Solidity
* **Development Environment:** Remix IDE
* **Wallet Integration:** MetaMask
* **Test Tokens:** Sepolia ETH / Mumbai MATIC

---

## ⚙️ Features
* 📦 Create and track agricultural batches (`createBatch`)
* 🔄 Transfer ownership across supply chain (`transferBatch`)
* 📜 Retrieve complete batch history (`getHistory`)
* ✅ Verify authenticity and origin of produce

---

## 🧑‍💻 Getting Started
### 1. Open Remix IDE
Access the online IDE:
👉 https://remix.ethereum.org/

---

### 2. Write / Load Smart Contract
* Create a new Solidity file
* Paste or upload your contract code

---

### 3. Compile the Contract
* Go to **Solidity Compiler** tab
* Select appropriate compiler version
* Click **Compile**

---

### 4. Deploy Smart Contract
Using MetaMask
1. Connect MetaMask:
   * Install extension
   * Create / import wallet
2. Switch to Test Network:
   * Sepolia or Polygon Mumbai
3. Get Test Tokens:
   * Copy wallet address
   * Use faucet to request tokens
4. Deploy Contract:
   * In Remix → Environment: `Injected Web3`
   * Connect MetaMask
   * Click **Deploy** and confirm transaction

---

### 5. Interact with Contract

After deployment:
* Contract appears under **Deployed Contracts**
* Use generated UI buttons to:
  * `createBatch`
  * `transferBatch`
  * `getHistory`

---

### 6. Retrieve Contract Details
* 📍 **Contract Address:** Copy after deployment
* 📄 **ABI:**
  * Go to Solidity Compiler → Compilation Details
  * Copy the JSON ABI
  * Use in frontend integration

---

## 📌 Workflow
```text
Farmer → Distributor → Retailer → Consumer
   ↓           ↓            ↓            ↓
Create      Transfer     Transfer     Verify
Batch       Ownership    Ownership    Product
```

---

## 🌟 Key Advantages
* ✔ Eliminates data manipulation
* ✔ Enables real-time tracking
* ✔ Improves supply chain accountability
* ✔ Enhances consumer trust

---

## 📈 Future Enhancements
* 📱 Frontend dashboard for users
* 📊 Analytics for supply chain insights
* 🌐 Integration with IoT sensors (temperature, storage conditions)
* 🔗 Multi-chain deployment

---
## 📄 License

This project was developed for the Smart India Hackathon (SIH) 

---

## 🔗 Useful Links
* Remix IDE: https://remix.ethereum.org/
* MetaMask: https://metamask.io/
* Sepolia Faucet: https://cloud.google.com/application/web3/faucet/ethereum/sepolia

---

## 💡 Note
This project is deployed on test networks for development and demonstration purposes only.
Ensure proper security audits before deploying on mainnet.

---
