# ☁️ Cloud Storage Smart Contract (Soroban - Stellar)
<img width="1914" height="883" alt="Screenshot 2026-04-09 151355" src="https://github.com/user-attachments/assets/5d5bf46d-968b-4c2f-92ad-34f9086b15b6" />

## 📌 Project Description

This project is a decentralized cloud storage smart contract built using **Soroban** on the **Stellar blockchain**. It provides a simple, secure way for users to store and manage their data on-chain using a key-value model.

Instead of relying on centralized cloud storage services, this solution ensures that users retain full ownership and control over their data in a trustless environment.

---

## 🚀 What It Does

* Allows users to upload and store data using unique keys
* Stores data on-chain linked to the user's wallet address
* Enables users to retrieve their stored data anytime
* Provides the ability to delete stored entries

This contract is ideal for storing:

* File hashes (for decentralized storage like IPFS)
* Metadata
* Small text-based data

---

## ✨ Features

* 🔐 **User Authentication** – Only the owner can modify their stored data
* 📦 **Persistent Storage** – Data is securely stored using Soroban persistent storage
* 🔑 **Key-Value Structure** – Flexible and simple storage model
* 🗑️ **Delete Support** – Users can remove their stored data
* ⚡ **Lightweight Design** – Optimized for low resource usage

---

## 🧱 Tech Stack

* **Rust**
* **Soroban SDK**
* **Stellar Blockchain**

---

## 📜 Smart Contract Functions

### 1. `upload(user, key, value)`

Stores a value under a specific key for a user.

### 2. `get(user, key)`

Retrieves stored data associated with a key.

### 3. `delete(user, key)`

Removes stored data for a given key.

---

## 🔗 Deployed Smart Contract Link

👉 *Add your deployed contract link here*

Example:
(https://stellar.expert/explorer/testnet/contract/CBGPIC5W5TGLJJPI4TD2KDJKEIP6VMSRCQA6QTNNA7T3AUBAMZ4WEYZ6)

---

## ⚠️ Limitations

* Not suitable for storing large files directly on-chain
* No built-in encryption (should be handled client-side)
* Basic implementation without advanced storage features

---

## 🔮 Future Improvements

* 🔗 IPFS / Arweave integration for real file storage
* 🔐 End-to-end encryption before upload
* 📂 File versioning system
* 👥 Access control (private/public/shared files)
* 💰 Storage pricing or quota system

---

## 🧪 How to Run

1. Install Soroban CLI
2. Build the contract:

```
cargo build --target wasm32-unknown-unknown --release
```

3. Deploy the contract:

```
soroban contract deploy ...
```

---

## 👨‍💻 Author

Sankhadip Mondal

---

## 📄 License

MIT License
