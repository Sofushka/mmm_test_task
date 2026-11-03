# Marketing Mix Model: Where to Invest the Next Pound?

This project answers the main business question: **where a brand should increase or decrease its advertising budget** to efficiently attract new customers while keeping the target cost per acquisition (CPA) at or below **£40**.

---

## 📌 Key Findings

* **All channels are profitable:** At current spending, every channel acquires customers cheaper than the £40 limit — Bing (£15), Meta (£29), Google (£32), Pinterest (£33).
* **The main driver is Meta:** The channel has virtually no diminishing returns effect. It is the best tool for scaling: a 20% budget increase for 30 days will bring about 530 new customers (approximately £29 per customer).
* **Channel limitations:** Google starts to get sharply more expensive when the budget grows by about 1.5x. Pinterest is the weakest and least predictable channel.
* **Cutting the budget makes no sense:** A 10% reduction in spending will cost 616 customers (you save only £28 on each lost customer). Reallocating money between channels yields a minimal effect.
* **Important caveat:** These are model estimates, not guarantees. Only a controlled split test will show the exact result.

---

## 🛠 Tech Stack
* **Python 3.13**
* **PyMC 6.3 & PyMC-Marketing 1.3** (Bayesian marketing mix modeling)