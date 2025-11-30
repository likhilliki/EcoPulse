# EcoPulse — Air Quality & Health monitoring coin

**EcoPulse** is a decentralized Air Quality & Health monitoring platform that rewards users with **ECO (EcoPulse) tokens** based on verified air-quality data and AI analysis. Built with public AQI APIs, Cardano on-chain tools, Masumi AI agents, and Eternl wallet integration — EcoPulse turns air-quality signals into on-chain incentives.

---

## 🚀 Project Summary

- **Data sources:** OpenWeather Air Pollution API (primary), OpenAQ / AQICN (optional)  
- **Frontend:** React (or static SPA) with Eternl (CIP-30) wallet integration  
- **Backend:** Node/TypeScript (Express) — fetches AQI, runs business logic, interacts with Masumi agent and Blockfrost  
- **Agent:** Masumi AI Agent that evaluates AQI and issues ECO rewards recommendations  
- **Blockchain:** Cardano mainnet (Blockfrost for API), Aiken smart contracts for minting/escrow logic  
- **Token:** **ECO** — native token (EcoPulse) minted according to policy & distributed to users  
- **Theme:** Air quality & health monitoring + tokenized eco-incentives

---

## 🧩 Why EcoPulse?

Air pollution affects billions and is a major health risk. EcoPulse provides:
- Trusted, auditable air-quality readings (from official AQI APIs)  
- On-chain anchoring for transparency and audit trails  
- Tokenized incentives (ECO) to reward contributors and raise awareness  
- AI-driven scoring (Masumi agent) for fair, automated reward decisions

---

## 🔧 Features (MVP)

1. Query AQI by coordinates (OpenWeather) and display on UI.  
2. Masumi Agent analysis: converts AQI → recommended ECO credits.  
3. Wallet connect (Eternl) to view & receive ECO tokens.  
4. Backend creates transaction metadata and coordinates minting (Blockfrost + Aiken).  
5. Audit trail: API reading hashes anchored on-chain for transparency.  
6. Admin interface for controlled minting & distribution.

---

## 📁 Repository Layout (recommended)

