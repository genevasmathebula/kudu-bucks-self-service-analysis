# User Stories and Acceptance Criteria

## 1. Purpose

This document describes the proposed Kudu Bucks Self-Service Top-Up Solution from the student's perspective.

User stories explain what students need and why. Acceptance criteria define the conditions that must be met for each story to be considered complete.

These stories and criteria are preliminary and have not yet been validated with students or system stakeholders.

## 2. User Stories

### US01: Access the Top-Up Service

**User story**

As a Wits student, I want to access the digital top-up service securely, so that I can add funds to the correct Kudu Bucks account.

**Acceptance criteria**

- Given that a student wants to use the service, when they attempt to access it, then the system should provide an appropriate access or authentication process.
- Given that a student has been authenticated successfully, when they continue to the top-up service, then the system should identify the correct Kudu Bucks account.
- Given that authentication fails, when the student attempts to continue, then the system should prevent access to the protected top-up process and display an appropriate message.

### US02: Enter a Top-Up Amount

**User story**

As a Wits student, I want to enter the amount I want to top up, so that I can add the funds I need for printing.

**Acceptance criteria**

- Given that the student has accessed the top-up service, when they enter a valid amount, then the system should accept the amount for the next step.
- Given that the student enters an invalid amount, when they attempt to continue, then the system should explain that the amount needs to be corrected.
- Given that the student has entered a valid amount, when they continue, then the system should display the amount before payment is initiated.

### US03: Make a Digital Payment

**User story**

As a Wits student, I want to pay for a top-up using a supported digital payment method, so that I do not have to rely on a physical cash-loading machine.

**Acceptance criteria**

- Given that the student has entered a valid top-up amount, when they select an available payment method, then the system should allow them to initiate the payment.
- Given that the payment is being processed, when the transaction has not yet been confirmed, then the system should not indicate that the top-up has succeeded.
- Given that the payment cannot be completed, when the failure is confirmed, then the system should communicate the unsuccessful outcome.

### US04: Confirm a Successful Top-Up

**User story**

As a Wits student, I want to receive confirmation that my top-up has succeeded, so that I know my Kudu Bucks balance is ready for use.

**Acceptance criteria**

- Given that the payment has been confirmed as successful, when the top-up is completed, then the system should display a success message.
- Given that the top-up has been successfully applied, when the student checks their balance, then the balance should reflect the confirmed transaction.
- Given that the transaction has not been confirmed as successful, when the student checks the result, then the system must not incorrectly display a successful top-up.

### US05: Understand a Failed Top-Up

**User story**

As a Wits student, I want clear feedback when a top-up fails, so that I understand what happened and what action I can take next.

**Acceptance criteria**

- Given that a top-up fails, when the system receives confirmation of the failure, then it should display a clear message.
- Given that the top-up fails, when the student views the message, then the system should provide an appropriate next step where possible.
- Given that a payment's outcome is still unknown, when the system cannot confirm its status, then it should not incorrectly report success or encourage the student to make a duplicate payment.

## 3. Assumptions and Dependencies

- The existing Kudu Bucks system may need to support integration with the proposed service.
- An approved digital payment method would need to be identified.
- The authentication method has not yet been selected.
- Transaction processing, balance updates and failure handling would need to be validated with the relevant system stakeholders.
- The project uses simulated data and does not process real payments.

## 4. Next Steps

- Review the user stories and acceptance criteria.
- Validate the proposed requirements with potential users and relevant stakeholders where possible.
- Design the proposed future-state process.
- Develop a simple demonstration using simulated data.
