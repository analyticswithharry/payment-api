# Payment API Lab

Build secure payment flows with idempotency, webhooks, and auditable transaction state.

## Core concepts

- Payment intent/state machine design
- Idempotency keys for safe retries
- Webhook signature validation
- Settlement/reconciliation workflows
- PCI and secret management boundaries

## Suggested Stack

- Stripe/PayPal sandbox APIs
- Express.js or FastAPI

## Learning Tasks

- Implement checkout/session creation
- Store payment status transitions
- Verify and process provider webhooks
- Add refund and failure handling paths
- Create audit trail for every payment event

## Validation checklist

- [ ] Duplicate payment requests are safe
- [ ] Webhook signature validation works
- [ ] State transitions are consistent
- [ ] Refund path is tested
