# Business Requirements

## 1. Purpose

This document identifies the needs and requirements for a proposed self-service solution that would allow Wits students to top up their Kudu Bucks balance digitally for printing.

The requirements are preliminary and are based on personal observations of the current process. They would need to be validated with students and relevant stakeholders.

## 2. Business Problem

Students who need to print may experience difficulties topping up their Kudu Bucks balance when cash-loading machines reject cash or are unavailable.

These challenges may delay printing, require students to find another machine, or lead them to ask another student for assistance.

## 3. Business Objective

Explore a convenient and reliable way for students to add funds to their Kudu Bucks balance without depending entirely on physical cash-loading machines.

## 4. Stakeholders

- **Students:** Need a convenient way to fund their printing balance.
- **University or system administrators:** Would need to assess whether a digital top-up solution could be supported.
- **Kudu Bucks system provider:** Would need to confirm whether integration with an external payment solution is possible.
- **Payment service provider or bank:** May be involved in securely processing payments, depending on the proposed design.

These stakeholders are preliminary and have not yet been consulted.

## 5. Functional Requirements

Functional requirements describe what the proposed solution should do.

| ID | Requirement |
|---|---|
| FR01 | The system should allow a student to access a digital top-up service. |
| FR02 | The system should allow a student to enter the amount they want to add to their Kudu Bucks balance. |
| FR03 | The system should allow the student to initiate a payment using a supported digital payment method. |
| FR04 | The system should display whether the payment was successful or unsuccessful. |
| FR05 | The system should display the updated Kudu Bucks balance after a successful top-up, once the transaction has been confirmed. |
| FR06 | The system should provide clear feedback when a top-up fails and explain what the student can do next. |

These are proposed requirements, not confirmed capabilities of the existing Kudu Bucks system.

## 6. Non-Functional Requirements

Non-functional requirements describe qualities the solution should have.

- **Security:** Student and payment information should be protected.
- **Usability:** The top-up process should be simple to understand and navigate.
- **Reliability:** Students should receive accurate transaction status information.
- **Privacy:** Personal information should only be collected and used where necessary.
- **Accessibility:** The service should be usable on commonly available mobile devices.

## 7. Constraints and Assumptions

- The existing Kudu Bucks system may have technical or institutional restrictions.
- Digital payment integration has not been confirmed.
- The solution would require appropriate security, privacy and payment controls.
- This is an independent portfolio concept and is not an official Wits project.
- No real payments or student data will be used in the demonstration.

## 8. Next Steps

- Prioritise the requirements based on student needs and business value.
- Identify questions that need to be answered through stakeholder research.
- Develop user stories and acceptance criteria.
- Design a proposed future-state process.
- Create a simple demonstration or mock-up using simulated data.
