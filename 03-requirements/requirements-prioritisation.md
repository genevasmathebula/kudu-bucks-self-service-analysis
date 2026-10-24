# Requirements Prioritisation

## 1. Purpose

This document prioritises the proposed requirements for the Kudu Bucks Self-Service Top-Up Solution using the MoSCoW prioritisation technique.

The objective is to identify which features are essential for the first version and which can be introduced later.

## 2. Prioritisation Approach

The prioritisation is guided by the primary business objective: to allow students to top up their Kudu Bucks balance digitally without relying on physical cash-loading machines.

These priorities are preliminary and should be validated with students, university representatives and relevant system stakeholders.

## 3. MoSCoW Prioritisation

| ID | Requirement | Priority | Reason |
|---|---|---|---|
| FR01 | Students can access the digital top-up service. | Must Have | Students need access to the proposed service. |
| FR02 | Students can enter a top-up amount. | Must Have | Students need to specify how much they want to add. |
| FR03 | Students can initiate a payment using a supported digital payment method. | Must Have | Digital payment is central to reducing reliance on cash-loading machines. |
| FR04 | Students receive a clear transaction success or failure message. | Must Have | Students need to know the outcome of their payment. |
| FR05 | The Kudu Bucks balance reflects a top-up after it is confirmed. | Must Have | The balance must be accurate after a successful transaction. |
| FR07 | The system authenticates the student and associates the transaction with the correct Kudu Bucks account. | Must Have | The system needs to protect accounts and direct funds to the correct student. |
| NFR01 | Student and payment information is protected against unauthorised access. | Must Have | Security is essential when handling payments and personal information. |
| FR06 | Students receive guidance when a top-up fails. | Should Have | Guidance helps students understand the failure and decide what to do next. |
| FR08 | Students can view their previous top-up transactions. | Should Have | Transaction history improves transparency and helps students check past activity. |
| FR09 | Students can receive optional top-up notifications. | Could Have | Notifications add convenience but are not essential to the main journey. |
| FR10 | Students can repeat a previous top-up amount quickly. | Could Have | This may save time for repeat users but is not essential initially. |
| FR11 | The system recommends how much a student should spend on printing. | Won't Have for now | Spending recommendations are outside the core business problem. |
| FR12 | The project redesigns the entire university printing system. | Won't Have for now | This would expand the project beyond its core objective. |

## 4. Dependencies and Feasibility

The proposed solution depends on whether the existing Kudu Bucks system supports digital balance updates and integration with a suitable payment service.

Before implementation, the project would need to investigate:

- Whether an approved integration method exists.
- Which digital payment methods could be supported.
- How student authentication and account identification would work.
- How successful, failed and duplicate transactions would be handled.
- How payment security, privacy and transaction reconciliation would be managed.
- Which university and system stakeholders would need to approve the solution.

If these dependencies cannot be resolved, the proposed solution may need to be revised.

## 5. Scope of the First Version

The first version will focus on the core digital top-up journey:

1. The student accesses the top-up service.
2. The system authenticates the student and identifies the correct Kudu Bucks account.
3. The student enters a top-up amount.
4. The student initiates a payment using a supported digital payment method.
5. The system displays the confirmed transaction outcome.
6. The Kudu Bucks balance reflects the successful top-up.

The first version will not include spending recommendations, a complete printing-system redesign or other non-essential convenience features.

## 6. Limitations

This prioritisation is based on the project's initial objective and personal observations. It has not been validated through formal stakeholder interviews or technical feasibility assessments.

The requirements and priorities may change as additional evidence becomes available.

This is an independent portfolio project and is not an official Wits initiative.
