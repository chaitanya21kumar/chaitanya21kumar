<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=3DAEFF&center=true&vCenter=true&width=940&lines=Hey%2C+I'm+Chaitanya+Kumar+%F0%9F%91%8B;Bitcoin+%26+Blockchain+Developer;Building+Production-Grade+Systems" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>3rd-Year CSE @ IIITDM Jabalpur</strong><br>
  <em>⚡ Bitcoin Protocol Development • Systems Programming • Blockchain Infrastructure</em>
</p>

<p align="center">
  <a href="mailto:chaitanya21kr@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://www.linkedin.com/in/chaitanya-kumar-071062296/">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://codeforces.com/profile/chaitanya21kumar">
    <img src="https://img.shields.io/badge/-Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/>
  </a>
  <a href="https://chaitanya21kumar.github.io/Portfolio-Website">
    <img src="https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.cloudskillsboost.google/public_profiles/c9ba5dfe-c06d-4315-9f98-486ffadafa34">
    <img src="https://img.shields.io/badge/-Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=chaitanya21kumar&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views"/>
</p>

---

<div align="center">

## 🎯 What I Build

</div>

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Bitcoin & Lightning Network
- **Protocol Development**: BDK, LDK integration
- **Standards**: BIP32/39/44/84, BOLT specs
- **Cryptography**: PSBTs, HD wallets, Schnorr
- **Production**: Self-custodial wallet systems

</td>
<td width="50%" valign="top">

### 🦀 Systems & Blockchain
- **Rust**: Memory-safe, high-performance code
- **Smart Contracts**: Solidity, Ethereum, Hardhat
- **Full-Stack**: Next.js, React, Node.js
- **Problem Solving**: 1000+ DSA problems solved

</td>
</tr>
</table>

<div align="center">

```rust
fn main() {
    let developer = Developer {
        name: "Chaitanya Kumar",
        focus: vec![
            "🔗 Bitcoin Core Development",
            "⚡ Lightning Network Infrastructure", 
            "🦀 Systems Programming in Rust",
            "⛓️ Blockchain Architecture & Security",
        ],
        motto: "Building verifiable, production-ready systems"
    };
    
    println!("{:?}", developer);
}
```

</div>

---

## 🔥 Featured Projects

<div align="center">

### 🌩️ **[Unified Lightning Wallet](https://github.com/chaitanya21kumar/unified-lightning-wallet)** • **[Live Demo](https://unified-lightning-wallet.vercel.app)**

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/chaitanya21kumar/unified-lightning-wallet)
[![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](https://github.com/chaitanya21kumar/unified-lightning-wallet)
[![Lightning](https://img.shields.io/badge/Lightning-792EE5?style=for-the-badge&logo=lightning&logoColor=white)](https://github.com/chaitanya21kumar/unified-lightning-wallet)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://github.com/chaitanya21kumar/unified-lightning-wallet/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/chaitanya21kumar/unified-lightning-wallet?style=for-the-badge&color=yellow)](https://github.com/chaitanya21kumar/unified-lightning-wallet/stargazers)

**Production-ready self-custodial Bitcoin Lightning Network wallet built with Rust**

</div>

<details>
<summary><b>🔍 Technical Architecture & Implementation Details</b></summary>

<br>

**🏗️ Project Structure:**
```
unified-lightning-wallet/
├── crates/
│   ├── core/              # Domain types, traits, error handling
│   ├── bdk-integration/   # Bitcoin on-chain (BIP39, HD wallets, PSBTs)
│   ├── ldk-integration/   # Lightning Network (channels, routing, BOLT11)
│   ├── storage/           # SQLite persistence (thread-safe operations)
│   ├── sync/              # Blockchain synchronization protocol
│   └── cli/               # Interactive command-line interface
├── src-tauri/             # Desktop application (Tauri + React)
├── ui/                    # Frontend React components
├── web-app/               # Web demo interface
├── docker/                # Docker containerization
└── .github/workflows/     # CI/CD pipeline (multi-platform builds)
```

**⚙️ Core Features:**

**Bitcoin Layer (BDK):**
- ✅ BIP39 mnemonic generation & recovery
- ✅ BIP32/44/84 hierarchical deterministic wallets
- ✅ Descriptor-based address generation
- ✅ PSBT (Partially Signed Bitcoin Transaction) creation
- ✅ Electrum server connectivity
- ✅ UTXO management & coin selection
- ✅ Fee estimation & RBF (Replace-By-Fee)
- ✅ Transaction history & balance tracking

**Lightning Network (LDK):**
- ✅ Lightning node implementation
- ✅ Payment channel state management
- ✅ Multi-hop payment routing
- ✅ BOLT11 invoice generation & parsing
- ✅ Onion routing for privacy
- ✅ Network gossip protocol
- ✅ Channel backup & recovery

**Production Features:**
- 🔒 Self-custodial: Full control of private keys
- 💾 SQLite persistence with schema migrations
- 🔄 Thread-safe concurrent operations
- 🧪 Comprehensive test coverage
- 🏗️ Multi-platform releases (Linux, macOS, Windows)
- 🔍 Automated linting (clippy) & formatting
- 🛡️ Security audit integration
- 🐳 Docker containerization
- 📚 Extensive documentation

**Tech Stack:** 
`Rust` • `BDK` • `LDK` • `Tauri` • `React` • `TypeScript` • `SQLite` • `Tokio` • `Docker` • `GitHub Actions`

**Why This Matters:**
This project demonstrates production-grade Bitcoin development with proper cryptographic practices, comprehensive error handling, and professional software engineering standards. It's built to be auditable, maintainable, and secure.

</details>

---

<div align="center">

### 🚀 **[ContestPulse](https://github.com/chaitanya21kumar/contestpulse)** • **[Live Demo](https://contestpulse-chaitanya21kr.netlify.app/)**

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://github.com/chaitanya21kumar/contestpulse)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/chaitanya21kumar/contestpulse)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://github.com/chaitanya21kumar/contestpulse)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/chaitanya21kumar/contestpulse)

**Intelligent CP contest tracker with real-time scraping & automated notifications**

</div>

Automated contest aggregator for Codeforces, CodeChef, LeetCode, AtCoder, and HackerRank with intelligent web scraping, REST API integration, and email alert system.

**Key Features:**
- 🤖 Automated web scraping with Puppeteer
- 📡 Multi-platform REST API aggregation  
- 🔥 Firebase Realtime Database integration
- 📧 Smart email notification system
- 📱 Responsive, modern UI/UX
- ⚡ Server-side rendering (SSR) with Next.js

**Tech Stack:** `Next.js` • `React` • `TypeScript` • `Firebase` • `Puppeteer` • `Node.js` • `REST APIs` • `Netlify`

---

<div align="center">

### 🔐 **[Decentralized Voting DApp](https://github.com/chaitanya21kumar/decentralised-voting-system)**

[![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)](https://github.com/chaitanya21kumar/decentralised-voting-system)
[![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)](https://github.com/chaitanya21kumar/decentralised-voting-system)
[![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logo=hardhat&logoColor=black)](https://github.com/chaitanya21kumar/decentralised-voting-system)

**Secure Ethereum voting platform with cryptographic verification**

</div>

Production-grade blockchain voting system ensuring transparency, immutability, and voter anonymity through smart contract architecture.

**Key Features:**
- 📜 Smart contract-based vote recording
- 🔐 Cryptographic voter verification
- 🧾 Immutable audit trail on Ethereum
- 🔑 JWT authentication & session management
- ⛽ Gas-optimized Solidity implementation
- 🧪 Comprehensive unit testing with Hardhat

**Tech Stack:** `Solidity` • `Hardhat` • `Ethers.js` • `React` • `MongoDB` • `Node.js` • `Express` • `JWT`

---

<div align="center">

### 🎙️ **[Saarthi — AI Collections Studio](https://github.com/chaitanya21kumar/saarthi)** • **[Demo Video](https://youtu.be/eYR_YPnh0v0?si=hVbZ7BRDfUVNIoAN)**

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://github.com/chaitanya21kumar/saarthi)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://github.com/chaitanya21kumar/saarthi)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://github.com/chaitanya21kumar/saarthi)
[![Blockchain](https://img.shields.io/badge/Blockchain-121D33?style=for-the-badge&logo=blockchain.com&logoColor=white)](https://github.com/chaitanya21kumar/saarthi)

**Enterprise AI voicebot with blockchain audit trails**

</div>

Production system for EMI collections combining AI, telephony, and blockchain for verifiable, RBI-compliant operations.

**Key Features:**
- 🎯 **TwinTower ranking algorithm** for customer prioritization
- 🎰 **Multi-Armed Bandit selection** for optimal contact strategy
- 🌐 Multilingual NLP with OpenAI GPT models
- 📞 Twilio integration for automated dialing
- 💬 WhatsApp Cloud API for payment links
- ⛓️ **Blockchain-backed call log hashing** for verifiable audit trails
- 📊 Real-time analytics dashboard
- ✅ RBI-compliant retry windows & regulations

**Tech Stack:** `Node.js` • `Express` • `Twilio` • `OpenAI GPT` • `MongoDB` • `WhatsApp Cloud API` • `Blockchain` • `Redis`

---

## 🛠️ Technology Stack

<div align="center">

### Languages & Core Technologies
<img src="https://skillicons.dev/icons?i=rust,cpp,solidity,python,java,javascript,typescript" alt="Languages"/>

### Web Development
<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,html,css,tailwind" alt="Web Dev"/>

### Databases & Tools
<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,sqlite,git,github,docker" alt="Databases"/>

### Cloud & DevOps
<img src="https://skillicons.dev/icons?i=aws,gcp,linux,vscode,postman" alt="Cloud"/>

</div>

<div align="center">

### 🔧 Specialized Bitcoin & Blockchain Tools

</div>

```yaml
Bitcoin Development:
  - Core: Bitcoin Core, BDK, LDK, Electrum Protocol
  - Lightning: BOLT specifications, LND, CLN
  - Standards: BIP32/39/44/84, PSBTs, Taproot, Schnorr

Cryptography:
  - Primitives: ECDSA, Schnorr signatures, SHA-256, RIPEMD-160
  - Key Management: HD wallets, mnemonic generation, secure derivation
  - Security: Secure random generation, key storage, access control

Smart Contracts & EVM:
  - Tools: Hardhat, Foundry, Truffle
  - Libraries: OpenZeppelin, Ethers.js, Web3.js
  - Testing: Mocha, Chai, Waffle
```

---

## 🏆 Achievements & Recognition

<table>
<tr>
<td width="50%" valign="top">

### 💻 Competitive Programming

- 🧠 **Codeforces**: Max Rating **1206 (Pupil)**
  - 279+ problems solved
  - Active participant in contests
  
- ✅ **CodeChef**: **3★ (1717 rating)**
  - **Global Rank 15** in Starters 192
  - Consistent top performer
  
- 📊 **Overall**: **1000+ problems** solved
  - Platforms: CF, CC, LC, GFG
  - **250+ active days** of practice
  - Strong DSA fundamentals

- 🥉 **Campus**: Top 12 in TPC CP Contest (IIITDMJ)

</td>
<td width="50%" valign="top">

### 🌟 Open Source & Production

- ☁️ **Google Cloud Arcade Champion**
  - 75+ points earned
  - Multiple labs completed
  
- 🚀 **Production Deployments**
  - 4+ live projects with real users
  - Multi-platform releases
  
- 📦 **Open Source Contributions**
  - 1,241+ GitHub contributions
  - Multiple public repositories
  
- 🔒 **Security & Quality**
  - Automated CI/CD pipelines
  - Security audit integration
  - Comprehensive testing

- 🌐 **Live Systems**
  - Vercel, Netlify deployments
  - Docker containerization

</td>
</tr>
</table>

> 💡 **Why These Matter**: Strong algorithmic foundations + consistent practice + production experience = reliable systems engineering capabilities essential for Bitcoin protocol development.

---

## 📊 GitHub Statistics

<div align="center">
  
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=chaitanya21kumar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=chaitanya21kumar&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## 🐍 Contribution Activity

<div align="center">
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chaitanya21kumar/snk/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chaitanya21kumar/snk/output/snake-light.svg" />
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/chaitanya21kumar/snk/output/snake-dark.svg" />
</picture>

</div>

---

## 🏆 Trophy Showcase

<div align="center">
  
<img src="https://github-profile-trophy.vercel.app/?username=chaitanya21kumar&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=15&margin-h=15" alt="GitHub Trophies" />

</div>

---

## 🎯 What Sets My Work Apart

<table>
<tr>
<td width="50%" valign="top">

### 📋 Code Quality Standards

```yaml
Every Project Includes:
  Testing:
    - Unit tests
    - Integration tests
    - End-to-end tests
    
  CI/CD:
    - Automated builds
    - Linting (clippy/eslint)
    - Security audits
    - Multi-platform releases
    
  Documentation:
    - Architecture docs
    - API references
    - Usage guides
    - Code comments
```

</td>
<td width="50%" valign="top">

### 🔐 Security & Production Focus

```yaml
Security Practices:
  - Cryptographic best practices
  - Proper key management
  - Input validation
  - Secure randomness
  - Defense in depth
  
Production Ready:
  - Error handling (Result types)
  - Graceful degradation
  - Performance optimization
  - Async operations
  - Resource management
```

</td>
</tr>
</table>

<div align="center">

### 💎 Bitcoin & Cryptocurrency Expertise

</div>

Not just blockchain buzzwords — real understanding of:

- ✅ **Bitcoin Internals**: UTXO model, transaction structure, Script language, witness programs, segregated witness
- ✅ **Lightning Network**: Channel states, HTLC routing, commitment transactions, penalty mechanisms, gossip protocol
- ✅ **Cryptographic Security**: Proper key management, no key reuse, secure randomness, hierarchical derivation (BIP32)
- ✅ **Standards Compliance**: BIP implementations, BOLT specifications, EIP standards, proper testing

<div align="center">

### 🦀 Systems Engineering Mindset

</div>

- **Rust Proficiency**: Ownership, borrowing, lifetimes, async/await, FFI bindings, unsafe code when necessary
- **Concurrent Systems**: Lock-free data structures, thread-safe operations, async runtimes (Tokio)
- **Modular Architecture**: Clean separation of concerns, trait-based abstractions, workspace management
- **Testing Discipline**: TDD approach, property-based testing, fuzzing for security-critical code

---

## 🎓 Current Focus & Future Goals

<table>
<tr>
<td width="50%" valign="top">

### 🚀 Active Development

- 🌩️ **Completing Lightning integration** in Unified Lightning Wallet
- 🔧 **Building Bitcoin dev tools** for ecosystem
- 📚 **Deep dive into Taproot**, Schnorr, MuSig2
- 🌐 **Contributing to Bitcoin Core** documentation
- 🧪 **Exploring wallet descriptors** and miniscript

</td>
<td width="50%" valign="top">

### 🤝 Open to Collaborate On

- ⚡ Bitcoin protocol development
- 🔗 Lightning Network infrastructure
- 🛠️ Developer tooling for Bitcoin
- 📖 Technical documentation
- 🦀 Rust-based blockchain systems
- 🎓 Educational content creation

</td>
</tr>
</table>

<div align="center">

### 🌟 Ideal Programs & Mentorship

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Summer%20of%20Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Summer of Bitcoin"/>
  <img src="https://img.shields.io/badge/Chaincode%20Labs-000000?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Chaincode Labs"/>
  <img src="https://img.shields.io/badge/Bitcoin%20Core-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Bitcoin Core"/>
  <img src="https://img.shields.io/badge/Lightning%20Network-792EE5?style=for-the-badge&logo=lightning&logoColor=white" alt="Lightning Network"/>
</p>

---

## 💭 Development Philosophy

<div align="center">

```markdown
┌─────────────────────────────────────────────────────────┐
│                                                         │
│  "I believe in building verifiable, auditable code     │
│   that anyone can inspect and trust.                   │
│                                                         │
│   My goal: Create reliable tools that people can       │
│   actually trust with their value."                    │
│                                                         │
│   - Comprehensive testing as first-class citizens      │
│   - Security-first mindset with defense in depth       │
│   - Open development with clear commit history         │
│   - Production-grade quality, not prototypes           │
│   - Community collaboration and knowledge sharing      │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

</div>

---

<div align="center">

## 🤝 Let's Connect & Build Together

<p>
  <a href="mailto:chaitanya21kr@gmail.com">
    <img src="https://img.shields.io/badge/Email-chaitanya21kr@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p>
  <strong>Open to:</strong> Bitcoin development mentorship • Open source collaboration • Technical discussions • Summer of Bitcoin
</p>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling" width="100%" />

<sub>*Built with consistency, technical depth, and genuine passion for decentralized systems.*</sub>

</div>
