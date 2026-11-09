# S-01: Stripe Payment Feasibility

**Risk addressed:** R2, Payment Processor Integration

**Question:** Can Stripe's hosted checkout accept a sandbox textbook payment without BookBridge collecting card details?

**Set-up:** Stripe sandbox, one $25 "Calculus Textbook" product, one-time payment, hosted checkout.

**How measured:** One test checkout completed; payment status confirmed in the Stripe dashboard.

**Result:** 1 successful test payment for $25. No real money was transferred and no card details touched BookBridge.

**Decision confirmed:** ADR-02 (payment through Stripe's hosted checkout page).

**Not yet tested:** actual BookBridge integration and webhook handling.

**Full report:** [docs/payment-feasibility.md](../../docs/payment-feasibility.md)
