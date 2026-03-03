# N-COIN: Stateless Consensus Currency
### "The Completion of Absence" — A New Standard for Value Exchange

N-COIN is a stateless digital currency that eliminates historical ledgers entirely. Instead of maintaining a traditional blockchain, N-COIN stores only the **latest state** for each user and validates transactions through a **Seven-Party Unanimous Protocol (SUP)**.

---

## 🚀 Overview

N-COIN represents a new direction for digital money, addressing the scalability and centralization issues inherent in current blockchain systems. 

* **Lightweight Operation:** Optimized for smartphones and edge devices.
* **Zero Historical Storage:** No growing chain data to store or sync.
* **High Security:** Achieved through unanimous verification from randomly selected nodes.
* **Fair Participation:** Decentralized value exchange without the need for mining or staking.

---

## 🛠 Key Features

### 1. Stateless Architecture
N-COIN maintains no historical ledger. Each user has only one verifiable state:
* **UID:** Public Key
* **Balance:** Current amount
* **Trust Score:** Reputation index
* **State Hash:** Cryptographic proof of current state
* **MuSig2:** Aggregated signature for compact verification

### 2. Seven-Party Unanimous Protocol (SUP)
Inspired by the integrity of Akira Kurosawa’s *Seven Samurai*, every transaction requires signatures from:
* **The Sender** (1)
* **The Receiver** (1)
* **VRF-Selected Mediators** (5)
* **Condition:** **All seven** must sign for the transaction to be valid. This prevents majority attacks and ensures absolute correctness.

### 3. Trust-Score Incentives (Proof-of-Honesty)
Nodes earn trust by participating honestly. Low-trust nodes are excluded from the mediator pool, creating a natural incentive for network integrity without the energy waste of Proof-of-Work.

### 4. MuSig2 Signature Aggregation
Seven signatures are compressed into one single compact signature, drastically reducing bandwidth and enabling seamless mobile-friendly operation.

---

## 🎨 Philosophy & Symbolism

N-COIN draws its soul from the principles of **Anonymity, Integrity, and Mutual Verification**. 

The **N-COIN logo** embodies this duality:
> A lowercase **“n”** that reveals the Japanese character **“七” (Seven)** upon deeper reading.

It signifies that while the network appears as a single entity ("n"), its strength is held together by the silent, unanimous protection of the seven participants.

---

## 📂 Repository Structure

/docs
    ├── [N_COIN_Stateless_Consensus_Currency(English).pdf](./docs/N_COIN_Stateless_Consensus_Currency(English).pdf)
    └── [N_COIN_Stateless_Consensus_Currency(Japanese).pdf](./docs/N_COIN_Stateless_Consensus_Currency(Japanese).pdf)

---

## ⚖️ License
This project is published under the **MIT License**.  
*(Subject to final definition by the author, NS.)*

---

## 🙏 Acknowledgements
N-COIN is inspired by the pioneering work of:
* **Isamu Kaneko** — For expanding the possibilities of P2P technology.
* **Satoshi Nakamoto** — For establishing decentralized value exchange.

*Their contributions made this project possible.*

---

## 📬 Contact
The author publishes under the pseudonym **NS**.  
No personal information is associated with this project. Integrity remains in the code.
