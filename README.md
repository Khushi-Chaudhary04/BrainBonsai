# 🌱 BrainBonsai

**BrainBonsai** is a gamified Web3 learning platform that helps people understand complex ecosystems in a calm, visual, and non-intimidating way.

Instead of static courses, BrainBonsai uses a **grow-a-tree metaphor** where learning actions grow a digital garden.  
When a tree reaches maturity, users earn an **NFT-based learning credential** as proof of exploration.

> BrainBonsai is about *confidence and understanding*, not certificates or speculation.

---

## ✨ Why BrainBonsai?

Web3 education often fails because:
- Documentation is overwhelming
- Courses get outdated quickly
- Wallets and transactions feel risky
- Beginners fear irreversible mistakes

**BrainBonsai fixes this by:**
- Focusing on *conceptual understanding*
- Using visual, game-like exploration
- Removing fear from first interactions
- Making learning progress verifiable

---

## 🧠 How It Works

### 🌱 1. Plant a Seed
Users choose a topic (e.g. Ethereum, Layer 2s, ZK Proofs).

### 🌿 2. Grow the Tree
- Explore concepts (branches)
- Reinforce with flashcards (leaves)
- Test understanding with quizzes (fruits & flowers)

Each action increases the tree’s **maturity**.

### 🌳 3. Earn a Credential
When maturity reaches 100%:
- A **learning NFT** is minted
- Issued to the user’s wallet
- Gas fees are paid by BrainBonsai (gasless for users)

The NFT represents:
- Topic explored
- Engagement depth
- Completion status

> These NFTs are **proof of learning**, not financial assets.

---

## 🧸 Web3 Sandbox (Fear-Free Onboarding)

To help non-technical users, BrainBonsai includes a **Web3 Sandbox** — an interactive simulation that teaches:

- Wallet addresses
- Sending tokens
- Network fees (gas)
- Transaction approvals
- NFTs and ownership

🟢 **Everything in the sandbox is simulated**
- No real wallets
- No real money
- No private keys
- Nothing can be lost

Think of it as *Web3 with training wheels*.

---

## 🔐 Wallets & Identity

- Users sign in with **Google**
- A wallet is created automatically (custodial by default)
- Private keys are **encrypted**
- Users can later export or migrate to self-custody (planned)

> Goal: remove onboarding friction while respecting ownership.

---

## 🏗️ Tech Stack

### Frontend
- HTML
- CSS
- Vanilla JavaScript
- Runs on Live Server

### Backend
- FastAPI (Python)
- SQLAlchemy
- SQLite / PostgreSQL
- Groq LLM (for content generation)

### Web3
- Ethereum (Sepolia testnet)
- Web3.py
- NFT smart contract (mint function only)
- Gas sponsored by platform

---

## 🚀 Running the Project Locally

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
