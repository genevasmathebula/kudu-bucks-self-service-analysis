# Risks, Assumptions and Dependencies

## 1. Purpose

This document identifies potential risks, assumptions and dependencies associated with the proposed Kudu Bucks self-service top-up solution. These items are based on the conceptual analysis and would need to be validated before implementation.

## 2. Risks

| ID | Risk | Potential Impact | Proposed Mitigation |
|---|---|---|---|
| R01 | Payment succeeds but the Kudu Bucks balance is not updated. | Students may lose confidence in the service or be unable to print. | Confirm transaction status and reconcile payment records with balance updates. |
| R02 | A pending payment is mistaken for a failed payment. | Students may make duplicate payments. | Display a clear pending status and check the original transaction before allowing a retry. |
| R03 | Unauthorised access to a student account. | Student information or funds could be exposed or misused. | Require secure authentication and verify account ownership. |
| R04 | The proposed service cannot integrate with the existing Kudu Bucks system. | The solution may not be technically feasible as proposed. | Confirm system capabilities and integration options with the relevant technical stakeholders. |
| R05 | Digital payment services become unavailable. | Students may be unable to top up when needed. | Define failure handling and communicate alternative top-up options where available. |

## 3. Assumptions

| ID | Assumption | Validation Required |
|---|---|---|
| A01 | Students would benefit from an alternative to cash-based top-ups. | Gather feedback from students about their current experience. |
| A02 | Students have access to a compatible mobile device and internet connection. | Validate access needs and consider students with limited connectivity. |
| A03 | A digital payment method could be supported by the proposed service. | Confirm available payment methods and technical requirements. |
| A04 | The existing Kudu Bucks system can accept balance updates from an authorised digital service. | Confirm with the system owner and technical team. |
| A05 | Students can be authenticated and linked to the correct Kudu Bucks account. | Validate the identity and account-verification process. |

## 4. Dependencies

| ID | Dependency | Why It Matters |
|---|---|---|
| D01 | Access to the existing Kudu Bucks system or an approved integration method. | Required to reflect successful top-ups in the correct account. |
| D02 | A supported digital payment provider. | Required to initiate payments and receive transaction status information. |
| D03 | Secure student authentication. | Required to protect accounts and prevent incorrect top-ups. |
| D04 | Agreement from relevant university and system stakeholders. | Required to confirm feasibility, ownership and approval before implementation. |
| D05 | Reliable transaction records and reconciliation processes. | Required to investigate failed, pending or disputed payments. |

## 5. Limitations

This is a conceptual portfolio project. No technical integration, payment processing or stakeholder validation has been performed. The risks, assumptions and dependencies are proposed items for further investigation, not confirmed facts about the existing Kudu Bucks system.
