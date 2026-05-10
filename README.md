# 
<p align="center">
  <img 
    width="50%" 
    alt="logoCertiFi" 
    src="https://github.com/user-attachments/assets/b604af90-8635-46eb-b8ed-88aae9e0ff53" 
  />
</p>

> CertiFi: Your financial reputation, certiFied by you.

[![Demo](https://img.shields.io/badge/demo-live-success)](https://trynoah.ai/shared/69ff87d5f1a82a5c436fabc4)
[![Built on Solana](https://img.shields.io/badge/blockchain-Solana-9945FF)](https://solana.com)

---

## 📖 About the Project

**CertiFi** is a blockchain-powered financial reputation platform for informal workers, freelancers, and rural communities in Latin America. It helps users build a verified financial history through uploaded payment proofs and personal financial data, generating an alternative credit score — the **Financial Health Score** — that they own and can present to any financial institution.

---

## 🔥 The Problem

In Colombia and across Latin America, millions of people are excluded from formal credit because they depend on risk bureaus like Datacrédito or TransUnion — centralized entities that control financial data, charge for access, and ignore the economic reality of informal workers.

- ❌ Freelancers and informal workers have no formal financial history
- ❌ Rural communities rely on predatory informal lenders ("gota a gota")
- ❌ People with variable incomes can't demonstrate real payment capacity
- ❌ Traditional credit scores punish past hardship without recognizing recovery

The result: exclusion, high costs, and a cycle of financial vulnerability.

---

## ✅ The Solution

CertiFi returns control of financial data to the user. Through a simple mobile interface, users can:

- Upload payment proofs (electronic invoices, payroll receipts, loan payments)
- Register income, expenses, and household financial context
- Receive a **Financial Health Score** (0–100) calculated from real behavior
- Store their score on the **Solana blockchain** as an immutable, verifiable record
- Share their certified score with banks, fintechs, or cooperatives — without intermediaries

The system doesn't punish past mistakes. It builds a complete, contextualized history that shows how a person manages and recovers their finances over time.

---

## 🚀 Demo

🔗 **[View live app](https://trynoah.ai/shared/69ff87d5f1a82a5c436fabc4)**

### Key Features

**For Users:**
- Secure registration with auto-generated Solana embedded wallet
- Upload financial documents with AI-simulated validation
- Financial Health Score calculated from payment history, income stability, and financial behavior
- Blockchain certification of each score update with transaction hash
- Shareable score certificate (downloadable image + copy link)
- Personal financial profile with household and credit context

**For Financial Institutions:**
- Access to user-shared, blockchain-verified financial reputation
- Alternative scoring data for populations with variable or informal income
- Trustworthy records that no party can manipulate

---

## 🛠️ Tech Stack

**Frontend:**
- [Noah AI](https://trynoah.ai) — AI-powered development platform
- React + TypeScript (TSX)
- Tailwind CSS

**Backend & Database:**
- Supabase — authentication and financial data storage

**Blockchain:**
- Solana Devnet — immutable score certification via transaction hashes
- Anchor — Solana smart contract framework

**Build Tool:**
- Vite

---

## 📊 How the Financial Health Score Works

The score calculated it's just an example, not a thecnical definition and needs improvement. For this case an scale from 0 to 100 was used, and is calculated from three weighted dimensions:

| Dimension | Weight | What it measures |
|---|---|---|
| Payment History | 40% | Consistency of payments over time |
| Income Stability | 35% | Regularity and volume of verified income |
| Financial Behavior | 25% | Expense management and savings ratio |

Each score update is stored on Solana blockchain with: user ID hash, score value, breakdown, and timestamp. The transaction hash serves as a verifiable proof of certification.

---

## 💡 Inspiration

This project was born from a real observation: a street vendor who sold street food for years, built enough savings to buy her own apartment — but without ever accessing formal credit, because the system never saw her.

CertiFi asks: *what if the system could finally see her?*

The idea connects directly with Colombia's new Open Finance law (Decree 0368, April 2026), which opens the door to alternative financial data infrastructure. CertiFi is built to be part of that future.

---

## 🏆 What We Built

- ✅ Full mobile app with navigation across 7 screens
- ✅ User registration with auto-generated Solana embedded wallet
- ✅ Document upload with AI validation simulation
- ✅ Financial Health Score engine with weighted algorithm
- ✅ Blockchain certification with transaction hash display
- ✅ Shareable score certificate
- ✅ Financial profile form with household, income, and credit context
- ✅ Certification history with copyable transaction hashes

---

## 🎯 Challenges We Faced

**Blockchain for non-crypto users:**
Most Web3 apps assume users know what a wallet is. CertiFi auto-generates an embedded Solana wallet at registration — invisible to the user, powerful under the hood.

**Verifying informal income:**
Real validation would require Colombia's DIAN electronic invoice API. For this MVP, we simulate AI validation while designing the architecture for real integration in production.

**Regulatory complexity:**
Building a financial reputation product in Colombia involves Superfinanciera regulations and data privacy law. For the MVP scope, we focused on the core user experience and flagged compliance as a critical next step.

---

## 💵 Business Model

- **Freemium:** Basic score visible for free; advanced recommendations and detailed insights on premium plan
- **Data insights (anonymized):** Aggregate financial behavior data valuable for fintechs and cooperatives
- **B2B API:** Financial institutions pay to query verified user scores with user consent

---

## 🔮 Next Steps

- [ ] Real DIAN API integration for electronic invoice validation
- [ ] Open Finance API connections (Decree 0368 compliance)
- [ ] ElevenLabs voice agent for financial guidance in low-literacy contexts
- [ ] LI.FI integration for cross-chain score portability
- [ ] Expansion beyond Colombia to broader Latin America

---

## 🌍 Social Impact

CertiFi targets the **estimated 60% of Latin American workers** in the informal economy who are systematically excluded from financial products designed only for salaried employees.

By combining blockchain ownership, alternative scoring, and financial education, CertiFi opens a path toward credit access, housing, and economic stability for those the traditional system has never seen.

---

## 👩‍💻 Team

Created during **Dev3Pack Hackathon — May 2026**

**Built by:**
- Laura Baez — Product Owner & Developer

---

## 📄 License

This project was created for educational and social impact purposes during a hackathon.

---

## 🙏 Acknowledgements

- **Noah AI** for enabling blockchain-connected development
- **Solana** for the infrastructure that makes financial ownership possible
- **Dev3Pack** for the space to build something meaningful

---

**CertiFi — Because your financial story belongs to you. 🟢**
