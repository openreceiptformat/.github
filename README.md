# .github
Openreceiptformat org level info

# Open Receipt Format (ORF)

The Open Receipt Format (ORF) initiative defines open, interoperable standards and reference implementations for **digital receipts**.

Our goal is to ensure that receipts are:
- Portable
- Privacy-respecting
- Vendor-independent
- Durable over time

ORF is not a payments system, a loyalty platform, or a data broker.  
It is an open foundation for receipt interoperability.

---

## The ORF Ecosystem

The Open Receipt Format ecosystem is composed of **three distinct layers**, each with a clearly defined responsibility.

- **ORF-Specifications**
Standard
- **Tommy-the-Tapi**
Receipt Claim Layer
- **Recipta**
Personal Recipt Vault

---

## 1. Open Receipt Format (ORF)

**ORF** defines *what a receipt is*.

- A vendor-neutral data model
- Designed to work across jurisdictions
- Compatible with:
  - VAT regimes
  - Sales tax systems
  - Fiscal receipt systems
- Focused on **representation**, not enforcement

ORF does not:
- Process payments
- Track consumers
- Mandate storage locations

📦 Repository: `orf-spec`

---

## 2. Tommy the Tapir

**Tommy the Tapir** defines *how receipts are issued and claimed*.

Tommy is a reference framework for enabling:
- NFC / QR / URL-based receipt claims
- In-store and online receipt delivery
- Receipt confirmation workflows (e.g. “this matches the cashier’s copy”)

Key properties:
- Payment-agnostic
- POS-agnostic
- Works with legacy systems
- Open source

Tommy enables modern, cart-like interactions in physical spaces without requiring merchants to replace their POS.

📦 Repository: `tommy-the-tapir`

---

## 3. Recipta

**Recipta** defines *how individuals store and use receipts*.

Recipta is a reference implementation of a:
- Local-first
- Privacy-preserving
- ORF-native receipt vault

Recipta:
- Stores receipts on the user’s device
- Allows user-initiated analysis and export
- Avoids cloud dependency by default

Recipta is not a fintech app or accounting platform.  
It is a personal data tool.

📦 Repository: `recipta`

---

## Design Principles

Across all projects, ORF follows these principles:

- **Separation of concerns**
- **User consent over automation**
- **Local-first by default**
- **Interoperability over lock-in**
- **Open standards, optional implementations**

---

## What This Is (and Is Not)

**This is:**
- A standards-driven ecosystem
- A set of composable building blocks
- Friendly to merchants, developers, and consumers

**This is not:**
- A payments network
- A loyalty platform
- A consumer surveillance system
- A centralized receipt database

---

## Getting Involved

We welcome:
- Standards contributors
- POS vendors
- Payment providers
- Privacy engineers
- Open-source developers

Discussion and design feedback are encouraged before major implementation work.

---

## License

Each repository defines its own license.  
The ORF specification and reference implementations are open source.
