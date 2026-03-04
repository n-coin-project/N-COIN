# N‑COIN: Stateless Consensus Currency  
A new value‑exchange model based on Seven‑Party Unanimous Protocol (SUP)

N‑COIN is a stateless digital currency protocol that maintains **no historical ledger**.  
Instead of accumulating past transactions like traditional blockchains, N‑COIN updates only the **latest state** using a Seven‑Party Unanimous Protocol (SUP) combined with:

- Device‑rooted UID keys  
- VRF‑based mediator selection  
- MuSig2 aggregated signatures  
- Trust‑score incentives  
- Stateless verification with temporary hash retention  

This design eliminates storage bloat, enables smartphone‑level operation, and provides strong resistance to fraud—even under adversarial conditions.

---

## Features

- Stateless architecture — only the latest state is stored  
- Seven‑Party Unanimous Protocol (SUP) — all 7 signatures required  
- VRF‑based mediator selection — unpredictable and fair  
- Trust‑score mechanism — honest behavior is always rewarded  
- MuSig2 aggregation — reduces 7 signatures to 1  
- Double‑spend prevention without historical data — via transaction locks  
- Lightweight — suitable for mobile devices  
- Resilient — stable even under 60–80% malicious nodes (simulation result)

---

## Documentation

All research papers are available in the `docs/` directory.

### Core Protocol Specification
- **N‑COIN: Stateless Consensus Currency (English)**  
  Formal definition of UID, SUP, trust‑score model, security assumptions, and stateless design.

### Simulation Studies
- **N‑COIN Report II: Simulation & Resilience Evaluation (Japanese)**  
  1,000,000‑round practical simulation under realistic and adversarial conditions.

- **N‑COIN Report II: Simulation & Resilience Evaluation (English)**  
  English version of the simulation report for international readers.

These documents together provide both the **theoretical foundation** and **empirical validation** of the N‑COIN protocol.

---

## Repository Structure
/docs
- [N_COIN_Stateless_Consensus_Currency(English).pdf](./docs/N_COIN_Stateless_Consensus_Currency(English).pdf)
- [N_COIN_Stateless_Consensus_Currency(Japanese).pdf](./docs/N_COIN_Stateless_Consensus_Currency(Japanese).pdf)
- [N_COIN_Report2_Simulation(English).pdf](./docs/N_COIN_Report2_Simulation(English).pdf)
- [N_COIN_Report2_Simulation(Japanese).pdf](./docs/N_COIN_Report2_Simulation(Japanese).pdf)
---

## Conceptual Inspiration

N‑COIN’s SUP model draws inspiration from Akira Kurosawa’s *Seven Samurai*:  
seven independent participants protecting the integrity of a village—not through authority, but through mutual verification and personal honesty.

In N‑COIN, the “seven samurai” are the seven participants who must unanimously validate each transaction, forming a decentralized foundation of trust.

---

## License

You may choose any license you prefer.  
If undecided, the **MIT License** is a common choice for open research projects.
