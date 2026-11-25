# Requirements and MoSCoW Prioritisation

Thresholds in the wording (15 minutes, 24 hours, "set limit") are placeholders to validate.

| ID | Requirement | Priority | Because |
|---|---|---|---|
| R1 | Rosters shall stay within legal duty and rest limits whenever schedules change. | Must | It is a legal and safety rule; the new FDTL rules triggered the disruption. |
| R2 | The system shall alert planners when a crew member approaches their duty limit. | Should | It supports R1; without it breaches are found after they happen. A workaround exists in manual checks. |
| R3 | Passengers shall be notified within 15 minutes of a cancellation decision, by SMS and in the app. | Must | The DGCA found mandatory information was not provided, and passengers' main fear is having no information. |
| R4 | Passengers shall be able to rebook or receive a refund online without calling. | Must | Without self-service, call volumes become unmanageable; it also delivers the refund approach chosen in section 7. |
| R5 | Customer care shall see the same flight status as operations control. | Should | It closes an information gap, but agents can work from updates for now. |
| R6 | Finance shall see refund and care cost per flight daily. | Should | It supports cost control under section 7; daily manual reports are a workaround. |
| R7 | Where a cancellation is known 24 or more hours ahead, passengers shall be notified within 15 minutes. | Should | It gives passengers time to rebook, but many cancellations were discovered close to departure. |
| R8 | A schedule shall proceed only when the minimum crew, including reserve, is available. | Must | It prevents the root problem (crew shortage) and makes R1 achievable. |
| R9 | Customer care agents shall approve rebooking and refunds up to a set limit without escalation. | Should | It resolves the care-versus-finance conflict, with a limit to protect cost. |
| R10 | The system shall forecast crew shortages in advance. | Won't (this time) | It needs data and modelling effort not available yet; R8 and R2 give partial protection. |

Result: 4 Must, 5 Should, 0 Could, 1 Won't. Test used for a Must: a legal or safety rule, or the solution fails without it.
