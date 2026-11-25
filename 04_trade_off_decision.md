# Trade-off Decision: Refund Processing

**Conflict:** passengers and customer care want fast refunds without friction; finance wants checks and cost control.

| | Option A: automatic, at once | Option B: tranches within cash on hand | Option C: finance reviews every refund |
|---|---|---|---|
| Passenger trust and compliance | High | Low (refunds are owed) | Low |
| Speed of refund | Fast | Slow | Slow |
| Cost exposure | High | Low | Low |
| Fraud and error risk | Medium | Low | Low |
| Workload for care and finance | Medium | High | High |

**Recommendation:** Option A with guardrails. Refund cancelled bookings automatically to the original payment method, and send only flagged cases to manual review.
**What we give up:** a sharp cash outflow and some fraud and error exposure.
**Mitigation:** automatic validation rules, a daily cash forecast, and daily reconciliation.
**To confirm:** treasury (can cash cover the peak?) and compliance (what refund deadlines apply?).
**Why not B:** refunds are money owed to passengers, so rationing them by cash on hand risks missing refund deadlines (to be confirmed with compliance).
